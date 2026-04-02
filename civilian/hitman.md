---
authors: 
  - "Mihaaaawk"
  - "Reivun"
lastEdit: "02/04/2026"
---
<!-- toc -->

# Introduction
**Hitman** is a **[Civilian](../civilian/civilian)-based** job in which you can **hunt players who have a hit contract on their head** for a huge **cash and XP reward**.

Hits can come from 2 sources:
- A hit given **randomly by the server depending on your notoriety** *(see [Server hit](#server-hit))*
- A hit **given from a player** as **revenge** *(see [Player hit](#player-hit))*

As it is a civilian based job, it also means that **every feature available for civilians are also available for hitman:** 

They have the same vehicles, blips and color as regular civilians / criminals, the only added feature is to **be able to receive calls for hit contracts**, respond to those calls and **claim the reward from those hit contracts**

## How to become a hitman?

To be a Hitman, you will have to:

- Be **level 12+** on the server.
- Go to any **Hitman** :hitman_job_icon:
- Speak to the NPC and select "**Switch to Hitman**"

You are now a **Hitman**! **Congratulations**!

missing_picture switch_to_hitman.webp

## How to take contracts

Once you become a hitman, you can access the **list of hit contracts available currently**.

To do so, press <kbd>M</kbd> / hold :VIEW: to go to CnRV menu, then go to **Job → Contracts**

You will then be able to see all available hit contracts with all their information:

| 🔍 Menu                 | 💬 Description                                                                              |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| 🎯 **Target Name**      | Includes the **player's name and ID**, with color coding for their **job or wanted level**. |
| ⏳ **Expires**          | Shows how long the contract is still available.                                             |
| 💰 **Reward**           | The **payment** you'll receive if you succeed in eliminating the target.                    |
| 🧑‍💼 **Placed by**        | Name of the **player who issued the contract**.                                             |

missing_picture contract_menu.webp

Once on this list, you just have to choose your target (<kbd>ENTER</kbd> / :A:) to select them as active target.

Alternatively when a new hit contract is contracted while you are a Hitman, you can get a **call for it which you can accept**:

Just press <kbd>Y</kbd> / hold :UP: when the prompt pops up to accept.

If you successfully accepted a contract, you should get some information about the next step to accomplish the contract: **track and kill your target !**

### Track a target

Once a contract has been selected as active, you have to go to a **Payphone** :hitman_payphone_blip: to reveal the **area in which your current target is**.

You can find payphones on populated streets across the city or **in some POI** *(grocery stores, ammu-nation, etc)*

When you find a payphone, you have to **get right next to it on foot** then press <kbd>E</kbd> / :RIGHT: to interact with the payphone

missing_picture payphone_use.webp

Doing so will play a **small animation**, which will give you the <Color id="target_area">hit target's current area on the map</Color>.

missing_picture area_map.webp

There is a **1 minute cooldown between payphones call to get the target's area**, so make sure to use this information wisely !

> [!WARNING]
> The area you get **doesn't change until you do another call**: if the target hasn't left the area, he might still be inside of it, else **you'll have to predict where they went** or **do another payphone call to get their new area**.

### Claim a bounty

Once you see your target you should be able to **see their hit amount right besides their head**.

missing_picture target_bounty.webp

If you manage to kill them, you **will claim the bounty reward** on their head for yourself and **some XP as reward**!
missing_picture contract_success.webp

> [!TIP]
> **Hits** and <Color id="5">most wanted bounties</Color> stack together, so if you manage to kill someone having them at the same time, **you get both rewards** at once !

# Player hit

If a **civilian** player has a **revenge** against another player or **a good enough and justifiable reason for revenge**, they are able to **create a hit contract on that player** so hitman can do the revenge in their stead!

> [!WARNING]
> Giving **hit contracts without revenge** and **randomly / without any good reason** is **punisable**: please refer to the [**CNRV full rules**](https://gtacnr.net/full_rules#rule01) for more information on this topic.

To do so, **players have 2 ways of creating a contract**:

Either go to one of the two **Hitman** :hitman_job_icon: which are located in :
- **Little Seoul** near the **LS mall / Cubby**
- **El Burro Heights** near the **Illegal gun dealer** :illegal_gun_store:

Then **speak to the job NPC** using <kbd>E</kbd> / :RIGHT:, select **Create new hit contract** then choose the target and the amount of money reward for fulfilling the contract.

> [!NOTE]
> Placing a hit contract using hitman NPC will cost you an **additional 10% fee on contract payement**: which means that if for example you put a **<Color id="money">$1,000,000</Color> reward**, you'll have to pay **<Color id="money">$1,100,000</Color> with the fee**

You can also place a contract by pressing <kbd>M</kbd> / holding :VIEW: to access CNRV Menu, then go to **Services → Hitman** and finally choose the target and amount of money reward for fulfilling the contract. 

> [!TIP]
> It is also possible to use your **Phone** to call for a hitman quickly by pressing <kbd>↑</kbd><br/ >
> *For more information, check out the [Phone page](../gameplay/phone).*

A hit can be placed if:

- the hit reward is between <Color id="money">$50,000</Color> and <Color id="money">$1,000,000</Color>
- you have **enough money in bank to pay the reward and fees**
- **hit target has less than 3 hits on them**
- **you didn't place a hit on that person already**
- **you aren't on a cooldown for placing a hit on them** *(15 minutes cooldown)*

missing_picture create_new_contract.webp

# Server hit

In CNRV, there is a hidden **"Notoriety" stat for criminals which raises depending on the number and gravity of crimes you did:** 

The more crimes you did in a short period, the more your notoriety will raise according to the degree of violence of those crimes.

This "Notoriety" stat will **increase the chance of you getting a randomly generated hit from the server** *(up to **5% chance of getting a hit every 10 minutes at max notoriety**)*

However, those random hits will only happen if:

- you are a civilian-based job (civilian, drug dealer, hitman, etc)
- there is at least 20 players online on the server
- you currently have less than 3 hits on your head currently

If you meet the criteria and are unlucky enough, server will issue a hit on your head with a reward between <Color id="money">$100,000</Color> and <Color id="money">$1,500,000</Color>.

# Tips & tricks for hitman

- **Work with teammates to track a target's location**: with multiple people using payphones one after the other, it's easier to figure out where the target is heading!
- **Be wary of other hitmen**: since you all want to claim the same target, you are **allowed to kill competiting hitman hunting the same target**, but the same can also be done to you.
- **If you have a hit on your head, stay on the move**: since hitman can only see vaguely the area in which you are, if you keep on moving it will be hard for them to hunt you. 