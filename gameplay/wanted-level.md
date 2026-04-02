---
authors: 
  - "Mihaaaawk"
  - "Reivun"
  - "Nezoka"
  - "Monke.M"
lastEdit: "02/04/2026"
---
<!-- toc -->

# Introduction
The base gameplay is **cops chasing criminals**: which means that **for criminals to exist**, there must exist a **wanted level** to grade their dangerousity to others.

On this page you will find how this wanted level works.

# Criminal
Once **a crime has been committed**, a civilian will get a **wanted level ranked by stars** depending on the severity of the crime they did.

Once they get a wanted level, <Color id="police" href="../emergency/cops">Police Officers</Color> are **allowed to track and arrest them for their crimes**, and if they committed a <Color id="violent" href="#violent-crimes">violent felony</Color> they are also **allowed to use lethal force to take down** the criminal.  
  
Each wanted level comes with **its own colour representation** and **reward for the cops** that can catch them :
- <Color id="1">1★</Color>: yellow nametag & blip on the map.
- <Color id="2">2★</Color>: dark yellow nametag & blip on the map.
- <Color id="3">3★</Color>: light orange nametag and blip on the map.
- <Color id="4">4★</Color>: orange nametag and blip on the map.
- <Color id="5">5★</Color>: red nametag and blip on the map.

Once you get to <Color id="5">most wanted level</Color>, you also get a **default bounty** of <Color id="money">$20,000</Color> which will **rise if you commit more crimes**.

## Fines
**Each crime** or **felony** will **give you a fine** depending on the type of crime you just did. 
You will have to **pay this fine** if you [**get arrested**](##getting-arrested), [**turn yourself in**](##Turning-yourself-in) or [**get killed**](##getting-killed). 

Those fines can **stack up to <Color id="money">$50,000</Color> at most**.

> [!TIP]
> You can check **your current fine amount** as a wanted player by typing <kbd>/crimes</kbd> in the chat.

## Most wanted criminals
The <Color id="5">most wanted level</Color> is a **special wanted level** reached only after having gone past the point of no return, via: 

- having **killed** a <Color id="police">police officer</Color>.
- **stolen** a **military vehicle** or **police armored vehicle**.
- **killing** another **non-cop player** while having <Color id="4">4★ wanted level</Color>.

Once you reach the <Color id="5">most wanted level</Color>, you receive a <Color id="money">$20,000</Color> bounty which **will rise depending on commited crimes**: 

**Every player**, except the <Color id="paramedic">paramedics</Color>, on the server **can hunt and kill you to get your bounty**.

> In the case of <Color id="police">Police Officers</Color>, they can also **try to arrest you alive to get a bigger reward**.

Having a **most wanted level** has some unique effects on you: 

- **bright red colour** for your **nametag** and **map blip**. 
- **increases the range** you need **without cops** around you **to lose your wanted level**. 
- **spawns AI cops** in the blinking area **around your last commited crime**: those cops **will shoot you on sight**.

> [!NOTE]
> It's also impossible to [**bribe**](##bribing-a-police-officer) a police officer or [**turn yourself in**](##Turning-yourself-in) at a <Color id="police">Police Department</Color>:police_station: while being <Color id="5">Most Wanted</Color>.

missing_picture /civilian/wanted-level.webp **A** <Color id="5">most wanted player</Color> **attacked by AI cops**.

## Offenders
If you manage to get at a <Color id="1">1★ wanted level</Color> (after **losing your other wanted levels** or doing a <Color id="1">misdemeanor</Color>), <Color id="police">Police Officers</Color> won't be able to **arrest you**, and **will instead have to give you a ticket**, which you can choose to:

- **pay immediatly** *(-30% discount will apply)*
- **try to contest** *(70% chance to not pay anything, else you pay the whole ticket price)*
- **bribe the cops**

You can also just **stay away from cops to [lose your wanted level](##lose-your-wanted-level)** after a while.

**Tickets** can go as low as <Color id="money">$750</Color> to <Color id="money">$25,000</Color> maximum.

> [!TIP]
> You can **check your current ticket value** as an offender by typing <kbd>/crimes</kbd> in the chat.

> [!WARNING]
> Getting away from a cop that gave you a ticket / asked you to pull over for a ticket will give you the <Color id="2">Resisting Arrest</Color> felony.

# Crimes list
This list **may not contain all** of the **crimes** or **felony** possible on CNRV.

> [!NOTE]
> Some crimes listed here are <Color id="non_violent">non-violent</Color> by default, but **CAN** become <Color id="violent">violent</Color> depending on the context it happens.
> 
> Example: Doing one "Hit and Run" is considered a <Color id="1">1★ Dismeanor</Color> and <Color id="non_violent">non-violent</Color> if done by mistake, however **doing it on purpose** makes it a <Color id="violent">violent felony</Color>

## Dismeanors

Those crimes are usually petty/not very important crimes, considered as <Color id="non_violent">non-violent</Color> that still needs to be punished, but only via giving [**Fines**](#fines) to pay as a "civic" lesson to not do them again!

| **Dismeanor**                              | **Description**                                                                                        |
| ------------------------------------------ | -----------------------------------------------------------------------------------------------------  |
| Hunting without a permit                   | <Color id="1">1★</Color> - Hunting wildlife animals without the permit<br />*(not implemented yet)*   |
| Killing a pet                              | <Color id="1">1★</Color> - Killing domesticated cats, dogs, and so on...                              |
| Killing endangered species                 | <Color id="1">1★</Color> - Killing protected wildlife animals                                         |
| Hit and Run                                | <Color id="1">1★</Color> - Hitting someone while driving<br />*Can become a felony if already wanted* |
| Damaging an emergency vehicle              | <Color id="1">1★</Color> - Damaging an emergency vehicle while driving                                |


## Non-violent felonies

Although those felonies are "hurting" others by commiting harm to their goods, money or mental health, those felonies are usually not considered **physically harmful to others** to the point of making use of lethal weapons to protect others.

Cops will try to arrest you for doing them, but are **not allowed** to shoot you unless you do something **threatening to them or others** while they are chasing you.
> For more detail, check out [**"Takedowns"**](../emergency/cops#takedowns) on the <Color id="police">Police Officer</Color> page.

| **Felonies**                               | **Description**                                                                                                                                      |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Eluding an Officer            | <Color id="2">2★</Color> - Evading a police officer trying to issue you a ticket<br />*+1★ ONLY* at <Color id="1">1★ wanted level</Color><br />If you are already at <Color id="2">2★</Color>, it will **not increase** your wanted level. |
| Refusing a Ticket             | <Color id="2">2★</Color> - Refusing to pay a ticket will get you *+1★ ONLY* at <Color id="1">1★ wanted level</Color>                                              |
| Resisting arrest              | <Color id="2">2★</Color> - Resisting a police officer cuffing you<br /> *(see [**Resisting arrest**](#resisting-arrest))*                                        |
| Attempted Bribery             | <Color id="2">2★</Color> - Trying to bribe a police officer<br /> *(see [**Bribes**](#bribing-a-police-officer))*                                                |
| Grand Theft Auto              | <Color id="2">2★</Color> - Stealing a parked and unoccupied vehicle                                                                                              |
| Pickpocket                    | <Color id="2">2★</Color> - Get caught stealing a player's or NPC's wallet                                                                                        | 
| Illegal Vehicle Exportation   | <Color id="2">2★</Color> - Exporting vehicles illegaly at the Docks:export_vehicle:<br />*(see [Vehicle exporting](../criminal/vehicle-export))* |
| Damaging a vehicle            | <Color id="2">2★</Color> - Damaging a vehicle by ramming it with your own                                                                                        |
| Drug Trafficking              | <Color id="2">2★</Color> - Being caught or snitched selling drugs<br />*(see [**Snitching**](../civilian/drug-dealer#snitching))*                              |
| Arms Trafficking              | <Color id="2">2★</Color> - Being caught selling weapons to players as [**Arms Dealer**](../civilian/arms-dealer)                                               |
| Shoplifting                   | <Color id="2">2★</Color> - Being caught stealing items at a cash counter                                                                                         |
| Harboring a felon             | <Color id="2">2★</Color> - Taking in a criminal in your car **as the driver**                                                                                    |
| ATM Hacking                   | <Color id="3">3★</Color> - Hacking an ATM:atm: to steal its money<br />*(see [**ATM Hacking**](../criminal/atm))*                                |
| Stealing an emergency vehicle | <Color id="3">3★</Color> - Stealing a <Color id="police">Police Officer</Color> or <Color id="paramedic">Paramedic</Color> vehicle                               |

## Violent felonies

Those crimes are considered harmful to the life of other NPCs or Players, which will allow cops to <Color id="violent" href="../emergency/cops#takedowns">take you down</Color> if given valid reasons to do so, such as seeing you commit these felonies or responding to such felonies calls.
| **Felonies**                               | **Description**                                                                                                                                                                                                                                                                  |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  |
| Carjacking                                 | <Color id="2">2★</Color> - **Forcefully** steal a car occupied by an **NPC** or **player**                                                                                                                                                                                      |
| Armed Robbery                              | <Color id="2">2★</Color> - **Rob or get caught robbing** a store with a **lethal weapon**                                                                                                                                                                                       |
| Attempted Armed Robbery                    | <Color id="2">2★</Color> - Fail to rob a store                                                                                                                                                                                                                                  |
| Murder                                     | <Color id="2">2★</Color> - Kill a **player** or **NPC**<br />*Becomes <Color id="5">5★</Color> if you kill a **player** at <Color id="4">4★ wanted level</Color>*                                                                                                              |
| Shooting at a vehicle                      | <Color id="2">2★</Color> - Shoot at a vehicle with a **firearm**                                                                                                                                                                                                                |
| Shooting at an emergency vehicle           | <Color id="3">3★</Color> - Shoot at a <Color id="police">Police Officer</Color> or <Color id="paramedic">Paramedic</Color> vehicle                                                                                                                                              |
| Threatening with a deadly weapon           | <Color id="3">3★</Color> - Aiming a **lethal weapon** at any **NPC** or **player**                                                                                                                                                                                              |
| Assault *(on regular civilians)*           | <Color id="3">3★</Color> - Hurting another player or NPC without killing them                                                                                                                                                                                                   |
| Assault on a Police Officer                | <Color id="4">4★</Color> - Hurting a <Color id="police">Police Officer</Color> **player** or **NPC** without killing them<br />*Becomes <Color id="5">5★</Color> if you shoot a <Color id="police">Police Officer</Color> **player** at <Color id="4">4★ wanted level</Color>* |

## Major felonies

Those kind of felonies are crimes that grants Police Officers the right to kill you <Color id="violent">on sight</Color> because of the gravity & harm caused by those felonies.

Unless you surrender or cops manage to immobilise you, there is no way to survive those crimes alive.
| **Felonies**                               | **Description**                                                                                                    |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------   |
| Armored vehicle theft                      | <Color id="5">5★</Color> - Steal a heavy & bulletproof vehicle from police stations                               |
| Military vehicle theft                     | <Color id="5">5★</Color> - Steal military vehicles from Fort Zancudo, the Aircraft near Cayo Perico or NOOSE base |
| Attempted Jewelry Robbery                  | <Color id="5">5★</Color> - Attempting to rob the **Vangelico Jewelry**:jewelry: but failling        |
| Jewelry Robbery                            | <Color id="5">5★</Color> - Leave the robbed **Vangelico Jewelry**:jewelry: with stolen jewelry      |

## Misdemeanor
- **Hunting without a permit** → <Color id="1">1★</Color> <Color id="non_violent">non-violent crime</Color>
- **Killing a pet** → <Color id="1">1★</Color> <Color id="non_violent">non-violent crime</Color>
- **Killing endangered species** → <Color id="1">1★</Color> <Color id="non_violent">non-violent crime</Color>
- **Hit and Run** → <Color id="1">1★</Color> <Color id="non_violent">non-violent crime</Color> - can become a <Color id="violent">violent felony</Color> depending on the situation
- **Damaging an emergency vehicle** → <Color id="1">1★</Color> <Color id="non_violent">non-violent crime</Color> - can become a <Color id="violent">violent felony</Color> depending on the situation

## Non-violent felonies
- **Resisting arrest** → adding <Color id="1">1★</Color> <Color id="non_violent">non-violent felony</Color> *(you need to already have stars)*
- **Attempted bribery** → adding <Color id="1">1★</Color> <Color id="non_violent">non-violent felony</Color> *(you need to already have stars)*
- **Grand Theft Auto** *(stealing a parked car)* → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Pickpocket** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Illegal Vehicle Exportation** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Damaging a vehicle** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Drug Trafficking** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color> 
- **Arms Trafficking** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Shoplifting** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **Harboring a felon** → <Color id="2">2★</Color> <Color id="non_violent">non-violent felony</Color>
- **ATM Hacking** → <Color id="3">3★</Color> <Color id="non_violent">non-violent felony</Color>
- **Stealing an emergency vehicle** → <Color id="3">3★</Color> <Color id="non_violent">non-violent felony</Color>

## Violent felonies
- **Carjacking** *(stealing an occupied vehicle)* → <Color id="2">2★</Color> <Color id="violent">violent felony</Color>
- **Shooting at a vehicle** → <Color id="2">2★</Color> <Color id="violent">violent felony</Color>
- **Murder** → <Color id="2">2★</Color> *(NPCs)* or <Color id="4">4★</Color> **(players)** <Color id="violent">violent felony</Color> 
  - Can go to <Color id="5">5★</Color> if you had <Color id="4">4★</Color>
- **Armed Robbery** → <Color id="2">2★</Color> <Color id="violent">violent felony</Color>
- **Attempted Armed Robbery** → <Color id="2">2★</Color> <Color id="violent">violent felony</Color>
- **Shooting at an emergency vehicle** → <Color id="3">3★</Color> <Color id="violent">violent felony</Color>
- **Threatening with a deadly weapon** → <Color id="3">3★</Color> <Color id="violent">violent felony</Color>
- **Assault** *(on a regular civilian)* → <Color id="3">3★</Color> <Color id="violent">violent felony</Color>
- **Assault on a Police officer** → <Color id="4">4★</Color> or <Color id="5">5★</Color> depending on your wanted level, <Color id="violent">violent felony</Color>
- **Armored police vehicle theft** → <Color id="5">5★</Color> <Color id="violent">violent major felony</Color>
- **Military vehicle theft** → <Color id="5">5★</Color> <Color id="violent">violent major felony</Color>
- **Attempted Jewelry Robbery** → <Color id="5">5★</Color> <Color id="violent">violent major felony</Color>
- **Jewelry Robbery** → <Color id="5">5★</Color> <Color id="violent">violent major felony</Color>

# Lose your wanted level
There are **multiple ways** of **losing your wanted levels**:

## Vanishing

**Vanishing** is the act of **staying away** from <Color id="police">cops</Color> **long enough to lose your wanted level** over time. 

The **more stars you have**, the **longer it will take for them to vanish** and the **farther you will need to be from cops**, especially for the **most wanted level**.

-   <Color id="1">1★</Color> → ≈5 minutes of waiting, 200m away from cops
-   <Color id="2">2★</Color> → ≈1 minute of waiting, 300m away from cops
-   <Color id="3">3★</Color> → ≈1 minute and 20 seconds of waiting, 400m away from cops 
-   <Color id="4">4★</Color> → ≈1 minute and 40 seconds of waiting, 500m away from cops
-   <Color id="5">5★</Color> → ≈5 minutes of waiting, 800m away from cops

> [!NOTE]
> Once you **start vanishing**, your last obtained ★ will **start blinking slowly**, and will **blink faster and faster** the more you wait until you **eventually lose it**.

## Getting arrested
Once **you get a wanted level**, <Color id="police">police officers</Color> can **cuff** and **arrest you**.

**When you are arrested**, a police officer can either call a **Quick Arrest** to bring an AI cop car that will **take and escort you to prison**, or they **can bring you to a police station themselves** by putting you in the back of their patrol vehicle.

**You will then be teleported to a random** <Color id="police">Police Department</Color>:police_station:, and **you will pay a bail fee**, which will depend on your [**fine**](#fines) value.

## Lock-picking
If there are **no nearby cops**, you can use lock-picks to **free yourself from your cuffs**.

To do this, either go to your inventory (using <kbd>F2</kbd> or pressing <kbd>M</kbd> / holding :VIEW:) → tools → lock-picks then press <kbd>Enter</kbd> / :A: to use them.
> You can also use the <kbd>/use lockpick</kbd> command in chat.

> [!NOTE]
> If **there is an officer nearby**, you **cannot use lock-picks** as they are watching you.

If another criminal has some lock-picks, they can get close to you, press <kbd>E</kbd> / :RIGHT: to open the interaction menu, then press **Use lock-pick** to free you, **even if police officers are around and watching you** (**<kbd>/use lockpick</kbd>** also works in this case).

> [!NOTE]
> **Your friend will** also get the <Color id="2">Harboring a felon</Color> felony and **get a wanted level** for doing this.

You can purchase Lock-picks from **Convenience stores** :convenience_store:, **Hardware stores**:hardware_store: and from <Color id="mechanic" href="./mechanic">mechanic</Color> players.

## Resisting arrest
During the cuffing process, **you can try to resist the arrest** by **clicking as fast as you can** on left mouse click: 

A successful attempt **will trigger a shaking-off** animation and **will ragdoll the cuffing police officer**, giving you a bit of time to **get away** or **fight back**.

> You will however get the <Color id="2">Resisting arrest</Color> **if you successfully broke out of your cuffs**.

> [!NOTE]
> You can only **resist arrest once every ≈20s**, and it also has a low chance of failing.

missing_picture /civilian/resisting_arrest.webp

## Bribing a police officer
You **can give cash** to a <Color id="police">police officer</Color> to **lose your wanted level**, at the cost of an XP loss for them: it is **entirely up to the police officer to accept** or **refuse** the **bribe offer**. 

It's a **pretty good strategy to use** if you have some <Color id="5">illegal items</Color> on you *(ATMs devices, illegal ammo, etc)* you don't want to lose, or to **skip the waiting time** for the arrest.

It's possible to **give a bribe in those cases**:
- while uncuffed, get close to a <Color id="police">police officer</Color> and press <kbd>E</kbd> / :RIGHT: then go to **Send a bribe offer** with the amount of money you want to offer.
- while cuffed press <kbd>E</kbd> / :RIGHT: to a nearby <Color id="police">police officer</Color> then choose the **amount of money** you want to give as a bribe offer.
- press <kbd>Y</kbd> / holding :UP: if a cop **sends you a bribe offer** while you are cuffed.

> [!NOTE]
> If a <Color id="police">police officer</Color> **refuses your bribe offer**, you will get an <Color id="2">Attempted bribery</Color> felony, which will give you one more wanted level until <Color id="4">4★</Color>.

You can bribe between <Color id="money">$15,000</Color> to <Color id="money">$500,000</Color>, no matter your wanted level and as long as you have enough cash in your balance to pay it.

There are **cases in which you cannot bribe** officers :
- you are a <Color id="5">most wanted criminal</Color>.
- you **already bribed** the same officer **less than 10 minutes ago**.
- you **got revived less than 30 seconds ago** by a <Color id="paramedic">paramedic</Color>, **while near a police officer**.

## Turning yourself in
If there **are no police officers** around a <Color id="police">Police Department</Color>:police_station:, you can **turn yourself in by speaking to the Police NPC** inside or in front of the department. 

You **will only have to pay a bail fee** which depends on your [**fine**](#fines) value before turning yourself in.

## Getting killed
When you are killed, **you will lose your wanted level every time**: you will **have to pay for your medical fees** and on top of this you will have to **also pay the bail fee**, which depends on your [**fine**](#fines) value before getting killed.

> This **also applies** even **if you respawn somewhere else** as a <Color id="mechanic" href="../civilian/mechanic">mechanic</Color> or as a [**delivery driver**](../civilian/delivery-driver).

# Jewelry Robbery

After starting or joining a Jewelry robbery in progress, if you manage to rob some items, you will have to **leave the city** to start losing your wanted level: 

There will be a very huge <Color id="4">Orange</Color> area on the map represented on the map to show you the area you must leave in order to successfully escape the cops. 

missing_picture /wanted-level/jewerly_area.webp

Until you leave this area, you will be stuck at Most wanted level unless you die and respawn at an Hospital or get arrested: you will also lose all robbed items at the same time.