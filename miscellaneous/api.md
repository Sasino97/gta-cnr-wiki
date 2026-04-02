---
authors: 
  - "xBytez"
lastEdit: "02/04/2026"
---
<!-- toc -->

# Introduction

The CNRV server provides two types of APIs:

1. **Official CnR V API** - A web API for getting server status and player information
2. **FiveM Server API** - Direct server endpoints for detailed server information

> [!DANGER]
> ⚠️ No support will be offered by the wiki team.

# Official CnR V API

The official API provides server status and player information through web endpoints.

## Server Status

### Get All Servers Status

```bash
curl https://api.gtacnr.net/cnr/servers
```

Response:
```json
[
  {
    "Id": "EU2",
    "Players": 34,
    "MaxPlayers": 100,
    "QueuedPlayers": 0,
    "LastHeartbeatDateTime": "2025-03-24T17:05:12.1049978Z"
  },
  {
    "Id": "US1",
    "Players": 91,
    "MaxPlayers": 100,
    "QueuedPlayers": 0,
    "LastHeartbeatDateTime": "2025-03-24T17:05:06.7868125Z"
  },
  {
    "Id": "US2",
    "Players": 24,
    "MaxPlayers": 100,
    "QueuedPlayers": 0,
    "LastHeartbeatDateTime": "2025-03-24T17:05:09.8976388Z"
  },
  {
    "Id": "EU1",
    "Players": 99,
    "MaxPlayers": 100,
    "QueuedPlayers": 0,
    "LastHeartbeatDateTime": "2025-03-24T17:05:06.5222571Z"
  }
]
```

### Example Usage

#### Get Total Players Across All Servers

```bash
curl https://api.gtacnr.net/cnr/servers | jq '[.[].Players] | add'
```

Response:
```json
248
```

#### Find Least Populated Server

```bash
curl https://api.gtacnr.net/cnr/servers | jq 'min_by(.Players) | {Id, Players}'
```

Response:
```json
{
  "Id": "US2",
  "Players": 24
}
```

#### Check Server Status

```bash
curl https://api.gtacnr.net/cnr/servers | jq '.[] | select(.Id == "EU1") | {Id, Players, MaxPlayers, IsFull: (.Players >= .MaxPlayers)}'
```

Response:
```json
{
  "Id": "EU1",
  "Players": 99,
  "MaxPlayers": 100,
  "IsFull": false
}
```

## Player Information

### Get Players for a Specific Server

```bash
curl https://api.gtacnr.net/cnr/players?serverId=EU1
```

Response:
```json
[
  {
    "Uid": "072D51B8FA964658AE9BBCA0B7766FA9",
    "Username": {
      "Username": "[BCŚP] Baldy",
      "Timestamp": "2025-03-23T21:39:10.9279399+00:00"
    }
  },
  {
    "Uid": "usr-9E7353VT1USbrY8wy-d-Mg",
    "Username": {
      "Username": "[BCŚP] KETTAMA",
      "Timestamp": "2025-03-24T14:55:53.7320299+00:00"
    }
  }
]
```

### Example Usage

#### Get Player Count for a Specific Server

```bash
curl https://api.gtacnr.net/cnr/players?serverId=EU1 | jq '. | length'
```

Response:
```json
2
```

#### Find Players by Username Pattern

```bash
curl https://api.gtacnr.net/cnr/players?serverId=EU1 | jq '.[] | select(.Username.Username | contains("BCŚP")) | .Username.Username'
```

Response:
```json
"[BCŚP] Baldy"
"[BCŚP] KETTAMA"
```

#### Get Most Recent Player Join

```bash
curl https://api.gtacnr.net/cnr/players?serverId=EU1 | jq 'max_by(.Username.Timestamp) | {Username: .Username.Username, JoinTime: .Username.Timestamp}'
```

Response:
```json
{
  "Username": "[BCŚP] KETTAMA",
  "JoinTime": "2025-03-24T14:55:53.7320299+00:00"
}
```

<Aside type="tip">The `LastHeartbeatDateTime` field can be used to check if a server is down - if it's more than 30 seconds old, the server is likely offline.</Aside>

<Aside type="caution">For safety reasons, IPs are logged. Please don't spam/flood the API.</Aside>

<Aside type="tip">You can use these APIs to create Discord bots, website widgets, or other tools to display server status and player information.</Aside>

# FiveM Server API

The FiveM server also exposes direct endpoints that provide detailed server information:

- `https://eu.gtacnr.net:30121/info.json` - Server information and configuration
- `https://eu.gtacnr.net:30121/players.json` - List of currently connected players

<Aside type="tip">
These endpoints are available on all CNRV servers. The ports vary by server:
- EU1 and US1: Port 30120
- EU2 and US2: Port 30121

Just replace `eu.gtacnr.net` with the appropriate server domain and port.
</Aside>

## Server Information API

The `/info.json` endpoint provides detailed information about the server configuration, including:

- Server version and build
- Server rules and configuration
- Available resources
- In-game time
- Server variables

### Example Usage

#### Get Server Time

```bash
curl -v https://eu.gtacnr.net:30121/info.json -k | jq '.vars.Time'
```

Response:
```json
"Friday 16:22"
```

#### Get Server Name

```bash
curl -v https://eu.gtacnr.net:30121/info.json -k | jq '.vars.sv_projectName'
```

Response:
```json
"^4Cops and Robbers V EU #2 HARDCORE"
```

#### Get Server Description

```bash
curl -v https://eu.gtacnr.net:30121/info.json -k | jq '.vars.sv_projectDesc'
```

Response:
```json
"Hardcore CnR V Gameplay ● 20% Bonus Money ● No Name Tags ● No Radar Blips ● Reduced Health and Armor ● Longer Healing Times"
```

## Players API

The `/players.json` endpoint provides information about currently connected players, including:

- Player names (these are usernames configured in FiveM, not the CnR V character name)
- Player IDs
- Ping values

### Example Usage

#### Get List of Connected Players

```bash
curl -v https://eu.gtacnr.net:30121/players.json -k | jq
```

Response:
```json
[
  {
    "endpoint": "127.0.0.1",
    "id": 130,
    "identifiers": [],
    "name": "xBytez",
    "ping": 42
  },
  {
    "endpoint": "127.0.0.1", 
    "id": 128,
    "identifiers": [],
    "name": "Mihaaawk",
    "ping": 69
  }
]
```

#### Count Number of Players

```bash
curl -v https://eu.gtacnr.net:30121/players.json -k | jq '. | length'
```

Response:
```json
2
```

#### Get Player Names Only

```bash
curl -v https://eu.gtacnr.net:30121/players.json -k | jq '.[].name'
```

Response:
```json
"xBytez"
"Mihaaawk"
```