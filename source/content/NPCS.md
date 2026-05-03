# Unit Types
There are several types of Units, a type determines the amount of characters needed to make a Unit of this Type and the amount of AP the Unit has access to each turn. It also determines the Health and Stamina of the characters within the Unit and the skills they have access to.
## Grunts
Grunt Units have 1 AP and are made to make use of Actions with the Group Trait
- Bandits: 1 Health | 0 Stamina | 5 Speed | 4 Characters
- Raiders: 1 Health | 5 Stamina | 4 Speed | 4 Characters
- Troopers: 2 Health | 0 Stamina | 3 Speed | 3 Characters
- Horde: 1 Health | 0 Stamina | 1 Speed | 8 Characters
## Specialists
Specialist Units have 2 AP and have access to Actions with the Save Trait
- Bandits: 3 Health | 12 Stamina | 5 Speed | 1 Character
## Officers

# NPC Actions
- **Ranged Barrage**, 1 AP
	- Effect: Each Character Targets one Foe, dealing 1d4+2 damage.
	- [[NPCS#^1998e7|Group]] [[Attack Trait|Attack]] [[Ranged Trait|Ranged]]
- **Running Gun**, 1 AP
	- Effect: Each character takes a move action and Targets one Foe, dealing 1d4 damage.
	- [[NPCS#^1998e7|Group]] [[Attack Trait|Attack]][[Ranged Trait|Ranged]]
- **Melee Fest**, 1 AP
	- Effect: Each character targets an adjacent Foe, dealing 1d6+2 damage.
	- [[NPCS#^1998e7|Group]] [[Attack Trait|Attack]][[Melee Trait|Melee]]
- **Rushdown**, 1 AP
	- Effect: Each characters takes a move action and then targets an adjacent Foe, dealing 1d6 damage.
	- [[NPCS#^1998e7|Group]] [[Attack Trait|Attack]][[Melee Trait|Melee]]
- **Body Shot**, 1 AP
	- Effect: Target one Foe, dealing 1d6+4 damage.
	- [[Attack Trait|Attack]][[Ranged Trait|Ranged]]
- **Snipe**, 2 AP
	- Effect: Target one Foe, dealing 3d4+6 damage.
	- [[Attack Trait|Attack]][[Ranged Trait|Ranged]]
- **Aim for the Knee**, 2 AP
	- Effect: Target one Foe, dealing 2d4 damage.
	- [[Attack Trait|Attack]][[Ranged Trait|Ranged]] [[NPCS#^157812|Save(10)(Impacted)]]
- **Concussing Wave**, 2 AP
	- Effect: Target a cone of 3, dealing 2d4 damage.
	- [[Attack Trait|Attack]][[Area Trait|Area]] [[NPCS#^157812|Save(8)(Impacted)]]

## NPC Traits
- Group: All characters within this unit count as taking this action ^1998e7
- Save(DC)(Condition): This action causes affected Foes to make a skill check of the chosen skill against the DC, if they fail they gain the listed Condition ^157812
# Declarations
