# Crimes
Crimes are the illegal actions you commit while you play Cops and Robbers V. Committing crimes causes your wanted level to increase, and the police to be dispatched.

Players on a *public service* job are unable to commit crimes.

## Crime System
Each crime has a minimum and maximum wanted level. When you commit a crime, you will receive at least the minimum wanted level for that crime. If you are already above that threshold, then you will receive one wanted level instead, but it's capped at the maximum wanted level.

## Violent Crimes
Some crimes are defined as *violent*. According to the [rules](/rules/full#part-two-police-officers), officers are allowed to shoot and kill a suspect who has committed a violent crime in their presence, or it was committed very recently and they received information about it.

## List
The following is a list of the current crimes, as of version 0.3.300.

| Crime                            | Minimum WL  | Maximum WL | Violent | Description |
| ---                              | --- | --- | --- | --- |
| Pickpocketing                    | 2   | 2   | No  | Pickpocket a player or NPC |
| Shoplifting                      | 2   | 2   | No  | Steal an item from a store |
| Grand Theft Auto                 | 2   | 2   | No  | Steal a locked vehicle |
| Carjacking                       | 2   | 4   | Yes | Forcibly remove the driver from a vehicle |
| Emergency Vehicle Theft          | 3   | 3   | No  | Steal an emergency vehicle |
| Armored Police Vehicle Theft     | 5   | 5   | No  | Steal an armored police vehicle |
| Military Vehicle Theft           | 5   | 5   | No  | Steal a military vehicle |
| Illegal Vehicle Exportation      | 2   | 3   | No  | Sell a vehicle to the exporters at the docks |
| Threatening with a Weapon        | 2   | 4   | Yes | Point a weapon at a player or NPC |
| Threatening an Officer           | 4   | 4   | Yes | Point a weapon at a police officer |
| Damaging a Vehicle               | 2   | 2   | No  | Cut off part of a vehicle with a powersaw |
| Damaging an Emergency Vehicle    | 3   | 4   | No  | Damage an unoccupied emergency vehicle without a firearm |
| Shooting at an Emergency Vehicle | 3   | 4   | Yes | Shoot at an emergency vehicle with firearm |
| Shooting at a Vehicle            | 2   | 3   | Yes | Shoot at a vehicle with a firearm |
| Evading an Officer               | 2   | 2   | No  | Refuse to stop after a police officer has ordered you to freeze or pull over |
| Refusing a Ticket                | 2   | 2   | No  | Refuse to receive a ticket from a police officer |
| Resisting Arrest                 | 2   | 4   | No  | Resist being handcuffed |
| Freeing a Suspect                | 2   | 4   | No  | Free a suspect from police custody |
| Harboring a Fugitive             | 2   | 4   | No  | Drive with a suspect as a passenger |
| Hit and Run                      | 1   | 2   | No  | Hit a player or NPC with a vehicle |
| Assault                          | 2   | 4   | Yes | Hit someone with your bare hands |
| Assault with a Deadly Weapon     | 2   | 4   | Yes | Shoot at someone with a firearm |
| Assault on an Officer            | 4   | 5   | Yes | Hit or shoot at a police officer |
| Murder (NPC)                     | 2   | 4   | Yes | Kill an NPC |
| Murder                           | 4   | 5   | Yes | Kill a player who is not a police officer |
| Murder of an Officer             | 5   | 5   | Yes | Kill a police officer |
| Killing a Pet                    | 1   | 1   | No  | Kill a domestic animal |
| Killing a Protected Species      | 2   | 2   | No  | Kill a protected species (eagle) |
| Hunting without a License        | 1   | 1   | No  | Kill a game animal without a hunting license (not obtainable as of 0.3.300) |
| Fishing without a License        | 1   | 1   | No  | Kill a fish without a fishing license (not obtainable as of 0.3.300) |
| Armed Robbery                    | 2   | 4   | Yes | Threaten a clerk with a weapon |
| Jewelry Robbery                  | 5   | 5   | Yes | Participate in a jewelry robbery |
| Burglary                         | 3   | 4   | Yes | Break into someone else's property (warehouse or garage) |
| Unlawful Hacking and Theft       | 3   | 4   | No  | Hack an ATM and steal the money |
| Drug Trafficking                 | 2   | 4   | No  | Sell illegal drugs in presence of a police officer |
| Arms Trafficking                 | 2   | 4   | No  | Sell illegal weapons in presence of a police officer |
| Attempted Bribery                | 2   | 4   | No  | Attempt to bribe a police officer who then refuses the offer |
