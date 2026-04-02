---
authors: 
  - "Reivun"
lastEdit: "02/04/2026"
---
<!-- toc -->

As you play on CNR and make friends, you need a way to play and speak with them more easily: there is no friends system here, but there is still a **Party system to create groups with your friends !**

# The purpose of Parties

Parties allows you lots of feature to allow you to play with other players more easily, such as: 
- **See each other on the map** *(even on hardcore servers)* 
- Speak on a **[custom radio channel](#radio)**
- **Not get any [felonies](../gameplay/wanted-level#crimes-list) on each other as [Civilians](../jobs/civilian)** *(such as Assault, carjacking, etc)*
- **Auto-join [robberies](../criminal/robberies)** as **[Civilians](../jobs/civilian)**
- Share **[bribes as Police Officers](../emergency/cops###bribes) only with party members** *(and not others nearby)*

party_blip_map.png

## Create a Party

To create a Party you must first not be in a party, then type <kbd>/pcreate</kbd> in the chat to create the party.

> [!NOTE]
> Alternatively, you can open your phone using <kbd>↑</kbd> → Party → Create

## Invite to the party

To invite players to join in the party, type <kbd>/pinvite [id]</kbd> in the chat *("ID" being the number besides the username of the player you want to invite)*
Invited players must then type <kbd>/pjoin [your ID]</kbd> to accept your invite.

> [!NOTE]
> You can also do it by using your phone : <kbd>↑</kbd> → Party → Invite players → Choose who to invite

> [!WARNING]
> Only the leader of the party can invite players to join it.

## Join a party

To join a party, you must be invited by the leader of this party, then type <kbd>/pjoin [Leader ID]</kbd> in the chat to join the party.

> [!TIP]
> If you weren't invited by the leader to join, you can still type <kbd>/pjoin [Leader ID]</kbd> to request to join the party: the leader will then have to type <kbd>/pinvite [your ID]</kbd> to accept your request.

## Manage the party as leader

The leader of the party (usually the player that created the party) has some specific interactions available only to him to manage the party as a whole.

### Give leader to someone else

As only the leader can invite people to the party, you can transfer leadership to another player in the party using <kbd>/pleader [their ID]</kbd> in the chat if you are busy or unavailable.

> [!NOTE]
> Can also be done from the phone : <kbd>↑</kbd> → Party → Transfer leadership

### Kick members

As the leader, you are able to kick players you don't want in the party anymore by using <kbd>/pkick [ID]</kbd> in the chat. *("ID" being the number besides the username of the player you want to invite)*

> [!NOTE]
> Can also be done from the phone : <kbd>↑</kbd> → Party → Kick players

## Leave a party

If you wish to leave a party *(to join another party for example)*, type <kbd>/pleave</kbd> in the chat.

> [!NOTE]
> Can also be done from the phone : <kbd>↑</kbd> → Party → Leave

> [!WARNING]
> If you leave a party as the Leader, party leadership will automatically be transferred to the oldest invited player in the party.

## Access member list

Both as a leader or a regular member, you can access the list of players in your party by typing <kbd>/plist</kbd> in the chat.

It will then tell you the list in the chat.

> [!NOTE]
> Can also be accessed from the phone : <kbd>↑</kbd> → Party → Members list

# Radio
You have access to a custom radio channel to speak with your party in text/voice radio.
By default after joining a party, you are automatically put inside the Party radio channel.

To manage your radio settings,you must type <kbd>/radio</kbd> in the chat to open the radio menu:

You can turn the radio <Color id="non_violent">on</Color>/<Color id="violent">off</Color>, switch the radio channel *(for cops/EMS)* and select the volume of the radio inside this menu.

radio_management.png

> [!TIP]
> If you don't want to speak in the voice chat, you can send text messages in radio channels: prefix your message with an exclamation mark <kbd>!</kbd><br />
> **Example**: <kbd>!</kbd>**I need backup in Grove Street, 1 active shooter**