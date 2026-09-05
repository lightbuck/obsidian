Player gear is used to determine the base attributes of your attacks, to aid with skill actions, to recover health, to increase [[Health and Stamina]] 
### Prepared Gear List
Some actions might require you to bring up specific gear pieces even if you don't have them on you, in this list you report pieces of gear you might use. You can't change this list during combat. If an action calls for prepared gear but you don't have any you may ask your party members but you can't make any new. This list exists to prevent the deceleration of combat from actions with the [[Traits#^2d7726|Create Trait]]

### Inventory
This are the pieces of gear your character lugs around and is able to equip on the fly
# v1
## Equipped Gear
This are the pieces of gear your character is currently using 
### Slots
There are two slots for equipped items:
- Armor Slot
	The armor worn by the character
- Weapon Slot
	The weapon(s) currently used by the character
## Weapon Conditions ^f56678

When Gear Breaks it becomes **Scrapped**, which can be returned to its original form with the [[Actions#^19f82e|Combat Repair]] or used by certain actions. When a piece of gear is scrapped it is no longer equipped
When your character throws a weapon or is made to drop their weapon it becomes **Lost**, a token or marker must be place where the weapon is. To equip it up again they must move into its square. If they threw the weapon they can take the generic action [[Actions#^bb3ce4|Catch]]

## Weapons
### Creating A Weapon
To create a weapon first chose an archetype

| Archetype Name | Examples                                  | Range                                       | Effect                                                   |
| -------------- | ----------------------------------------- | ------------------------------------------- | -------------------------------------------------------- |
| Close Quarters | Short Swords, sawed off shotguns, shields | This weapon has a target radius of 1        | /                                                        |
| Large Melee    | Claymores, whips, long flails, staves     | This weapon has a target radius of 2        | -1 speed                                                 |
| Thrown Melee   | Axes, daggers, throwing stars, javelins   | This weapon has a scene wide target radius  | Lose the weapon upon making an attack above a range of 1 |
| Medium Ranged  | Automatic rifles, short bows, pistols     | This weapon has a scene wide  target radius | Attacks to targets above zeroed range deal -1 damage     |
| Far Ranged     | Long bows, sniper rifles,                 | This weapon has a scene wide  target radius | Attacks to targets below zeroed range deal -1 damage     |

Then you have 7 points to spend on traits for your weapon

#### Weapon Traits
If the cost is listed with a + at the end it means you may spend more points for that trait, increasing its effects as specified in its Effect section.

| Trait Name  | Cost | Description                                                                                                                                                                                                                                                         | Effect                                                                                                                                                                                            |
| ----------- | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Independent | 4+   | This weapon acts on its own in some way. For example it could be a floating set of drones or it could be a loyal animal companion.                                                                                                                                  | Add a token on the field that represents your weapon, actions that invoke your weapon must be taken from the position of that token. Extra points spend on this trait add extra tokens.           |
| Inherent    | 4    | Your weapon is always with you in some way. For example it could be your flaming palms if you wield [[Powers#^22318f\|The Phoenix Talon]]. Or it could be an endless supply of throwing darts you never seem to run out of.                                         | Your weapon cannot become lost or scrapped                                                                                                                                                        |
| Bifurcated  | 4    | This weapon can change shape or in some way transform into another type of weapon. For example it could be as simple as a rifle changing ammunition types from bullets to shotgun shells. Or it could be a sword and a shield that can be combined into a great axe | When creating the weapon chose another archetype for it. You can take a [[Actions#^644f38\|Swap Action]] to change archetypes. You can take this trait multiple times.                            |
| Defending   | 4    | This weapon helps you defend yourself. For example it could be a parrying dagger, or a rifle with an energy barrier mounted on the barrel                                                                                                                           | With this weapon equipped, you gain a [[Health and Stamina#^0823c9\|Gate]] that you can manually trigger as a reaction to taking damage to your stamina, halving the damage you would have taken. |
| Mounted     | 3+   | Your weapon allows you to move faster in some way. For example your hammer could have a jet engine strapped to its head. Or your weapon could be your mechanic wings with which you fly.                                                                            | You gain a movement speed bonus equal to the points spent on this trait                                                                                                                           |
| Agile       | 3    | This weapon is easy to move around                                                                                                                                                                                                                                  | Once per turn you may [[Actions#^644f38\|Swap]] to this weapon for free.                                                                                                                          |


## Armor
Armor is subdivided by how heavy it is:
- Nimble
	You could be wearing very little or no protective gear, allowing you to move freely. This grants +4 [[Health and Stamina#^7170e3|Recovery Die Size]]
- Medium
	You could be wearing a partial shield generator , a layer Kevlar or chainmail with your clothes, Etc. This grants you +2 [[Health and Stamina#^7170e3|Recovery Die Size]] and +2 [[Health and Stamina|Health]]
- Heavy
	You could be wearing a full suit of riot armor or iron plating. +3 [[Health and Stamina|Health]]
- Super-Heavy
	You could be wearing a full shield generator or some sort of armored exosuit. This grants you -2 [[Health and Stamina#^7170e3|Recovery Die Size]] and +4 [[Health and Stamina|Health]]



# v2
From the start you have 7 gear points, these points determine the amount of gear you can bring into battle. A single piece of gear costs 1 points per archetype it possesses but any gear can be given additional traits which increase its cost. The amount of gear points increases with character level

## Weapons
Weapon archetypes:
- Close quarters  ^b81917
- Ranged
A weapon's base damage bonus is dictated by the level of the weapon ^c2d71c

| Level | Cost  | Base Damage |
| ----- | ----- | ----------- |
| 1     | 1 GP  | +1          |
| 2     | 2  GP | +2          |
| 3     | 4  GP | +3          |
| 4     | 6 GP  | +4          |
| 5     | 8 GP  | +5          |
| 6     | 10 GP | +6          |
| 7     | 12 GP | +7          |
%%
Alt version with no vertical scaling

| Tier | Cost | Bonus |
| ---- | ---- | ----- |
| S    | 6 GP | +5    |
| A    | 4 GP | +3    |
| B    | 2 GP | +2    |
| C    | 1 GP | +1    |
%%

### Weapon Traits
- Bifurcated
	This weapon can transform into another piece of gear that also has this trait and costs the same amount of GP
#### Critical Traits
These traits add effects to maximum and minimum critical rolls that invoke this weapons
- Precise
	Max Crits deal +2 damage
- Reliable
	Min Crits deal +1 damage, Max Crits deal +1 damage ^43881e
- Heavy
	Max Crits have [[Fling Trait|Fling(5)]] ^09d0cb
- Unstable
	Min Crits deal +1 damage to the wielder, Max Crits Deal +3 damage
- Impacting
	Max Crits inflict the [[Impacted Condition]] ^1106e9
- Cool
	Max Crits make you gain 1 stack of [[Adrenaline|Adrenaline]] ^045bf7
- Fast
	Max Crits make you gain 5 stacks of [[Energized Condition|Energized]] ^356c77
## Armor
Armor Archetypes
- Sleek Armor(1)
	*Small pieces of armor that might be undistinguishable from clothes*
	-2 Stamina +1 Health  ^05cbc7
- Medium Armor(2)
	*Thick armor plates that cover your most important body parts* 
	-5 Stamina +3 Health  ^773a2c
- Heavy Armor(3)
	*Armor the fully protects your body at the cost of mobility*
	-5 stamina -1 Speed +4 Health  ^8c39ce
## Other Equipment
Equipment Archetypes
- Tool (1-?)
	A tool grants a +1 per GP spent to a specific skill
- Resource (1)
	A resource grants a +2 to an applicable situation once and then it is removed.

## Universal traits

^65bdbe

- Inherent(1)
	This piece of gear is a part of you and cannot be lost. ^2e8c83
- Agile(1)
	This piece of gear can be swapped for free.
- Ride(1-?)
	This piece of gear increases your speed by +1. This trait can be acquired multiple times. ^885fe3
- Self Repairing(1)
	This piece of gear reconstructs itself at the beginning of your turn.
- Auxiliary(1)
	This piece of gear moves independently of you and is represented by another token. It has the same speed as you and moves when you take a move action.
- Returning(1)
	This piece of gear removes its lost condition at the beginning of your turn
- Unbreakable(1)
	This piece of gear cannot be broken ^7c9600