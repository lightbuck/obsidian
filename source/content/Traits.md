#PhotonTTRPG  ^14b61d

## Action Traits
Traits are used to described basic functions of an Action along side the Action Description
Trait List: 
(N = can be a number or a roll)

- Attack: This action deals the listed damage to the target ^8f40c8
- Area: This action targets an area in some way described by the effect. ^e6b705
- Surprising: This action's target becomes impacted ^ed045c
- Risky(N): This action has a risk to deal N stamina damage, which you take if you fail a [[Health and Stamina#^77a09d|Tank Or Flank?]] check against a DC of 10+N #PH . You roll this check after resolving the action ^6ed443
- Fling(N): This action **forces** the target move N spaces in a horizontal direction of your choice or straight up. ^7c76e1
- Push: This action forces movement in a manner described by the effect
- Create: This action creates something. If it's a piece of gear it can be automatically swapped to by a character in the same space as it. If it's a piece of gear or companion it must be chosen from your [[Gear#Prepared Gear List|Prepared Gear]] ^2d7726
- Immobile: You can't move for the rest of this turn. ^be2d6b
- Consumed: This action ends your turn. ^74b16d
- Aid: This action aids someone in some way. Allies characters affected by this action lose the [[Conditions#^471f1e|Impacted Condition]] ^e327ca
- Burning(N): The next time this character takes damage they take extra N damage after resolving the action that caused them to take damage. ^c65353
- Step(N): At any point during this action you can move one space N times. [[Conditions#^868aeb|Quickened]] can be consumed to increase N. ^77bf53
- Mobile: Before taking this Action you can take a 0 AP [[Actions#^642a2c|Move Action]] ^9e3f4f
- Move: This action makes you move in some way determined by the effect, you must take this movement. ^c90f08
- Protected: After this action resolves roll your recovery die. ^7b905e
- Role: This action is a Role Action. ^c39ead
- Spend(N): This action spends N [[Meter]] after resolving its rolls. However if the action did not specify an effect for the spent [[Meter]], you may add the amount spent to its results ^69bd9b
- Gain(N): This action adds N [[Meter]] after resolving its rolls ^d02161
- Expend(N): This action drains N stamina from you and gain one stack of [[Conditions#^685a66|Adrenaline]]. If you have no stamina you instead gain N stacks of the [[Conditions#^9ed920|Stressed Condition]]. ^deed79
- Charging: You gain or sustain the [[Conditions#^f57404|Charged Condition]] ^d2dbb4
- Sacrifice: At the end of this action your current stamina is reduced by the size of your [[Health and Stamina|Recovery Die]]. Gain [[Meter]] equal to the amount lost. However you currently have the [[Conditions#^9d723e|Daemonized Condition]] you instead gain [[Meter]] equal to the amount of damage you deal, up to twice the size of your [[Health and Stamina|Recovery Die]]. ^195914
- Crossover: Any ally with a bond with you may expend their AP to use this action. If this action has the [[Traits#^8f40c8|Attack Trait]] it must target a Foe within line of sight of the ally. Any effects of the action happen as if you used it, but for the purposes of conditions for the ally's following actions it will count as if they had taken this action. When used this way, you may also take a move action for free before taking this action. ^0609c3
- Companion: This action may only be taken by your Companion(s). ^c2aac5
- Crushing: If this action exhausts its target's stamina, they automatically become impacted. ^7782f4
- Final: You can only use this action once per Scene. This Action cannot have the [[Traits#^0609c3|Crossover Trait]]. You can only Know one of this actions. ^ace9f7
- Piercing: If this action [[Health and Stamina|Exhausts the target's Stamina]] it also deal damage to the target's [[Health and Stamina|Health]] as if they had no Stamina ^cb440a
- Brutal: This action deals an extra point of damage if it deals damage to health. ^21477e
## Magic Traits 
List:
- Ancestral : Someone in your family line also possesses this Origin. You cannot pick other Ancestral Magics
- Zodiac : You obtained this Magic because of events that took place during your birth
- Power : You obtained this magic because you learned it, or something happened to you that made you gain it.
- Soul Bound : This magic is bound to your soul


## Environment Traits
- The Floor Is Lava(N): Characters that end their turn adjacent a specified surface take N damage
- Slippery: when character's [[Health and Stamina#Gates|Gate]] is triggered they become [[Conditions#^471f1e|Impacted]]
- Crumbling: at the end of the round all characters in this area take 2 damage. They can attempt a [[Saves|Reflex Save]] to avoid the damage if they succeed or take 3 damage if they fail.
- Royale(N): At the end of every turn all characters who aren't in this area take N damage
- Trudging(N): All characters in this area have a N movement tax
- Showdown:  At the beginning of the first round all Characters gain [[Conditions#^685a66|Adrenaline]]
- Mosh Pit: All characters in this area take 1 stamina damage once per turn in which they take an action without the [[Traits#^8f40c8|Attack Trait]] #PH
- Library: All characters in this area take 1 stamina damage once per turn in which they take an action with the [[Traits#^8f40c8|Attack Trait]] #PH

## Deprecated Traits

- Swap(Weapon/Armor): After this action is resolved you may exchange a piece of gear you have equipped for a different piece of gear, without exceeding your Load. ^803dca
#### Targeting Traits
These traits determine the who or what this action targets, they are mutually exclusive per aspect
- Weapon Range(N): This Action targets N characters in the range of the equipped weapon ^be4c14
- Cone(N): This Action targets an area determined by a cone of N
- Radius(N): This Action targets an area determined by a radius of N
- Line(N): This Action targets an area determined by a line long N ^cdf11b
- Melee: This action targets N characters within the reach of your melee weapon ^ff0aa3
- Ranged(N): This action targets N characters within line of sight   ^cbb2c4
- Self: This Action targets the user ^d885e1
- Allies(N): This Action targets N allies at any range ^412513
- Foes(N): This Action targets N foes at any range ^5d64a2
- Any(N): This Action targets N characters at any range
if an aspect does not have a targeting trait it means it inherits the target from the previous aspect. Example
[[Traits#^8f40c8|Attack]](W+1d6), [[Traits#^ff0aa3|Melee(1)]] | [[Conditions#^9ed920|Stressing(2)]] 
The second aspect targets the same foe you targeted with the previous aspect
[[Traits#^8f40c8|Attack]](W+1d6), [[Traits#^ff0aa3|Melee(1)]] |  [[Traits#^ff0aa3|Melee(1)]], [[Conditions#^9ed920|Stressing(2)]] |
The second aspect targets the any foe in melee of your choice

#### Roll Traits
These Traits revolve around invoking rolls for an action or modifying their results
- Reinforce(ROLL): This action grants the listed [[Health and Stamina|Stamina]] to the target ^4cf018
- Unbalanced(N): This action leaves the target, reducing their stamina by N at the end of the turn ^b7f6b3
- Guarded(N): This action grants the target N stamina ^e2d480
#### Gear Traits
- Summoned: this piece of gear was summoned through magic, if broken it will not turn into scrap but instead it will vanish into nothingness ^d1c690
#### Role Traits

^0c5bc6
- BIG: This [[Actions|Action]] costs one less [[Actions|AP]] if your [[Health and Stamina|Health]] is below half #PH ^0c3ae0
- TCT: After seeing the results of any roll invoked by this [[Actions|Action]] you may choose to undo this [[Actions|Action]] and choose a [[Terminology|Party Memeber]] to take an [[Actions|Action]] that must have their respective Role Trait. This is still your action phase. #PH ^167655
- HRT: This [[Actions|Action]] gains +1 to any one result for every [[Terminology|Party Member]] who is below their maximum [[Health and Stamina|Health]] ^effdd1
- ACE: Add your meter to any one result or roll of this action