---
authors: 
  - "Mihaaaawk"
  - "Reivun"
lastEdit: "02/04/2026"
---
<!-- toc -->

# Introduction

Mechanic is a [**civilian**](../civilian/civilian)-**based job** which allows a player to **buy mechanic supplies** and use them to help other players to **customise their vehicles at a mod shop**, by using their own set prices, you will get a **daily paycheck at 12:00** (<Color id="money">$20,000</Color>). 

They can also **tow vehicles parked illegally** by other players around the map to get a reward at the impound.

As it is a civilian based job, it also means that **every feature available for civilians are also available for mechanic players**, with only some small differences : 
- The ability to offer services to mod or repair vehicles
- The ability to tow & impound vehicles
- Unique mechanic clothing
- <Color id="mechanic">Grey colored</Color> nametag / map blip colour

## How to become a mechanic ?

If you want to become a <Color id="mechanic">Mechanic</Color>, you'll have to :

- Be **Level 3+** on the server.
- Go to a **Mod Shop**:car_mod_shop:
- Speak to the NPC and select "Switch to <Color id="mechanic">mechanic</Color>"

You are now a <Color id="mechanic">Mechanic</Color>! **Congratulations**!

missing_picture switch_to_mechanic.webp

# How to mod vehicles ?
Everything you need to know **to mod vehicles**!

## Buy mechanic supplies

The first step to being able to modify other player's vehicles is to buy some mechanic supplies at a **Hardware Store** :hardware_store:

Once you get **in the hardware store**, you can buy all kinds of mechanic supplies which will **get added to your mechanic stock**. 
Here are **all the mechanic supplies you can buy**, and there uses for players:

| 🛠️ **Item**              | 🔧 **Use**                                                                                                 | 🔍 **Notes**                                             |
| ------------------------- | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| **Engine Repair Kit**     | Repairs a **broken engine** (up to **75% health**)                                                         | Can be sold and used by other players                    |
| **Tire Repair Kit**       | Fixes **flat tires**                                                                                       | Can be sold and used by other players                    |
| **Cleaning Kit**          | Washes a **dirty vehicle**                                                                                 | Can be sold and used by other players                    |
| **Helicopter Repair Kit** | Repairs **helicopters**                                                                                    | 🚧 *Not implemented yet*                  |
| **Plane Repair Kit**      | Repairs **planes**                                                                                         | 🚧 *Not implemented yet*                  |
| **Modding Kit**           | Mods **other player's vehicles**                                                                           |                                                          |
| **Window Tint Kit**       | Tints the **windows** of another player's vehicle                                                          |                                                          |
| **Paint**                 | Changes the **color** of another player's vehicle                                                          |                                                          |
| **Lockpick**              | Uncuffs **yourself or another player**<br/>*(see [lockpicking](../gameplay/wanted-level###lockpicking))*   | Can be sold and used by other players                    |
| **Power Saw**             | Cuts the door of a **locked personal vehicle**                                                             | ⚠️ 30% chance to **break after use**      |


## Set your services prices

Using the job menu (<kbd>M</kbd>/holding :VIEW:) you can **access your mechanic stock** and **adjust your prices** for your services and sellable items. 

| 💡 **Service**        | 🔧 **Description**                     | 🔍 **Notes**                                              |
| --------------------- | --------------------------------------- | ---------------------------------------------------------- |
| **Repair**            | Price to **repair a vehicle**           | Consumes 1 **Engine Repair Kit** & 1 **Tire Repair Kit**   |
| **Wash**              | Price to **clean a vehicle**            | Consumes 1 **Cleaning Kit**                                |
| **Respray**           | Price to **change the vehicle's color** | Consumes 1 **Paint**                                       |
| **Mod**               | Price to **apply mods**                 | Consumes 1 **Modding Kit**                                 |
| **Repair Boat**       | Price to **repair boats**               | 🚧 *Not implemented yet*                    |
| **Repair Airplane**   | Price to **repair airplanes**           | 🚧 *Not implemented yet*                    |
| **Repair Helicopter** | Price to **repair helicopters**         | 🚧 *Not implemented yet*                    |
| **Windows Tint**      | Price to **change window tint**         | Consumes 1 **Window Tint Kit**                             |


Those prices can be adjusted from **-50%** to **+50%** of the default market price.

missing_picture services_price.webp <kbd>M</kbd> / holding :VIEW: → Job Menu → Services

> [!TIP]
> That means you can either be a **good samaritan** with **low prices** and **low profit** when modifying vehicles, or be a **businessman** by using **high prices** for **high profit**.

## Set your sellable items price

You can also choose the price to sell every items in the **Stock** menu:
- **Engine / tire / helicopter / plane repair kits**
- **Cleaning kits**
- **Lockpicks**
- **Power saws** 

missing_picture sales_inventory_setprice.webp <kbd>M</kbd> / holding :VIEW: → Job Menu → Stock

## Go to a mod shop and offer your services

With your supplies, you can now go to one of the **8 mod shops** :car_mod_shop: around the map to mod the cars of other players:

**For each service sold** *(paint / respray / repair, etc)* that isn't an item, the mod shop you're using will take a **small percentage fee from your profits**. 

For instance with the default market price of modifying a front bumper, it's <Color id="money">$12,000</Color>.

Here's how much money you'll get depending on the mod shop:

| 🏪 **Mod Shop**                                      | 📍 **Location**        |
| ----------------------------------------------------- | ---------------------- | 
| **Benny's Modding Shop** :car_mod_shop:               | Davis *(3/8)*          | 
| **Mosley's** :car_mod_shop:                            | Davis *(6/8)*          | 
| **LS Custom La Mesa** :car_mod_shop:                   | La Mesa *(5/8)*        | 
| **LS Custom Rockford** :car_mod_shop:                  | Rockford Hills *(1/8)* | 
| **Hayes Auto** :car_mod_shop:                          | Davis *(4/8)*          | 
| **LS Customs Airport** :car_mod_shop:                  | LSIA *(2/8)*           | 
| **LS Customs Route 68** :car_mod_shop:                 | Route 68 *(7/8)*       | 
| **Beeker's Garage** :car_mod_shop:                     | Paleto Bay *(8/8)*     | 


Players can use your services from the **mechanic menu** (<kbd>E</kbd> / :RIGHT:)
> You can also press <kbd>Y</kbd> / hold :UP: while near them to **offer your services directly**.
  
When a player uses your services, **you will get a prompt on the top-left** of your screen telling you they are using your services.

> [!WARNING]
> Modifying your prices **while someone is using your services** will **refresh their menu** with the new prices. It will also **notify them of the prices change**.

You can also **offer your services outside of a mod shop**, but they won't be able to respray / mod their vehicle *(only repair, wash and buy the regular items)*.

> [!TIP]
> Players **can access your services directly from the mechanic shop menu**, without you offering them: this allows you **to be AFK at mod shops** if you have enough stock!

# How to tow vehicles ?

To tow a vehicle, you need to go to one of the **8 mod shops**:car_mod_shop: on the map and **wait for the towing truck to spawn** besides them *(at the entrance most of the time)*

missing_picture tow_truck_front_bennys.webp

Once you have the towing truck, all you have to do is to patrol around the city and watch out for all **illegally parked vehicles**:
you will see a <Color id="1">yellow arrow</Color> on **top of illegally parked vehicles**.

Hold <kbd>H</kbd> / :RIGHT: **while the car is aligned with your tow truck** to tow the vehicle.

It will appear at the back of your truck like this:

missing_picture yellow_arrow_impound.webp

The amount of money you get **depends on the distance you travelled** between where you towed the car and which **Impound** :impound: you brought it to: 

The longer the distance, the more money you get, **capped at <Color id="money">$50,000</Color> for regular vehicles**.

## Personal vehicles towing

You can somtimes catch **other player's personal vehicle being parked illegally**!

If you tow them, you have a **2 minutes period in which the player cannot recall their vehicle**, giving you enough time to bring it to an **impound** :impound:
> Past this period **they will be able to recall their vehicle**, even if it's still on the truck.

> [!TIP]
> If an **emergency vehicle** has the **siren on** while parked, **they are considered legally** parked so **you cannot tow them** to an impound.

You get a **bonus** *(≈50% increase to the reward)* **for towing a personal vehicle** to an **Impound**:impound:up to <Color id="money">$85,000</Color> at best.

missing_picture tow_personal_vehicle.webp

## Criminal use vehicles towing

If a criminal has been arrested and **used a car for his crimes before getting arrested**, their vehicle **can be towed even when parked legally**.

> [!NOTE]
> You will sometimes get **tow calls for those criminals vehicles**, which you can accept by pressing <kbd>Y</kbd>/holding :UP: to get a <Color id="gps">GPS waypoint</Color> to the vehicle.

Those vehicles will have an <Color id="4">orange arrow</Color> instead of the usual <Color id="1">yellow arrow</Color>.

missing_picture tow_orange_arrow.webp

**Bringing a vehicle used in a crime** to an **Impound**:impound: also gives a **small bonus** *(≈20%)* compared to towing a regular car, up to <Color id="money">$85,000</Color> at best.

> [!TIP]
> **Both bonuses** from towing *(crime car + personal vehicle)* **can be stacked** together to give an **80% increase to the reward** (up to <Color id="money">$120,000</Color> at best).

## What happens to a personal vehicle when it's impounded ?

When a **personal vehicle is impounded**, the player whose vehicle got impounded will have to go to any **Impound** :impound: to **pay the impound fee** *(price depending on the vehicle's value)*. 

Until this fee is paid, the **vehicle cannot be delivered** or **be found inside garages**.
> [!NOTE]
> Check the [**personal vehicle**](../gameplay/personal-vehicles) page for more information.

# Clothing

With the exception of some accessories / hats, **mechanic players cannot purchase and use civilian clothing as mechanics**: 

They instead have some **mechanic clothing and uniforms** available at the **hardware store** :hardware_store:
> [!NOTE]
> Check the [**appearance**](./../gameplay/appearance) page for more information.