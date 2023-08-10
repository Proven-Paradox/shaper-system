# Summoning
**Table of Contents**  
- [Abilities](#abilities)  
  - [Basic Summon](#basic-summon)
  - [Advanced Summon](#advanced-summon)
- [The Base Summons](#the-base-summons)
  - [Basic Summon](#basic-summon)
  - [Advanced Summon](#advanced-summon)
- [Summon Configuration](#summon-configuration)
  - [Summoning Attunement](#summoning-attunement)
  - [Defender](#summon-configuration-defender)
  - [Mental Attacker](#summon-configuration-mental-attacker)
  - [Physical Attacker](#summon-configuration-physical-attacker)
  - [Support](#summon-configuration-support)
- [Summoning Lessons](#summoning-lessons)  
  - [Assisting Summon](#assisting-summon)
  - [Basher Summon](#basher-summon)
  - [Blaster Summon](#blaster-summon)
  - [Bodyguard Summon](#bodyguard-summon)
  - [Channeling Summon](#channeling-summon)
  - [Extra Options](#extra-options)
  - [Elemental Summons](#elemental-summons)
  - [Sturdy Summons](#sturdy-summons)
- [Advanced Options](#advanced-options)
  - [Universal Options](#universal-options)
  - [Defender Options](#defender-options)  
  - [Mental Attacker Options](#mental-attacker-options)
  - [Physical Attacker Options](#physical-attacker-options)
  - [Support Options](#support-options)
- [Talent](#talent)  
  - [Double Summon](#double-summon)
 
## Abilities

### Basic Summon    
Auxiliary [Summoning]  
Action: Minor  
Prerequisites: None  
Range: Short  
Targets: None  
Cost: Variable (See Special) (Upkeep: 2 MP)  
Special: You summon a friendly Basic Summon creature to assist you in combat. The creature summoned is described below.  
When you gain this Ability, you automatically gain the [Summoning Attunement](#summoning-attunement) Lesson once.  
You may spend MP up to a maximum of your level when you first use this Ability. The being summoned has max HP equal to five times the amount of MP spent.  
When you use this Ability, choose one version of Summon Configuration benefits to add to the summoned creature.  
Summoned creatures may move during the summoner's turn once for free. The summoner may commit a Minor action to move the ally a second square.  
You may only summon one creature at a time. If a summoned creature dies, you cannot use Summon with the the same Summon Configuration for one hour. If you have multiple Summon Configuration options, you may choose to summon a different one by using this Ability again.  
Description: This Ability allows you to draw a second creature to your aid. This could be the result of necromancy, alchemy, robotics, conjuration, imbuing a familiar with combat ability, ritual summoning, or any other effect that would result in an additional creature involved in the combat. As long as you pay the MP cost and the ally is not killed, the creature remains on hand to help in combat.

> The high MP cost and Upkeep of this Ability makes it a poor choice for low level characters. No one can stop you from taking this as one of your first three Abilities, but this would typically be a poor tactical decision as you should probably get a few levels of Capacity to support the MP costs.

### Advanced Summon
Tier: 2
Auxiliary [Summoning]  
Action: Minor  
Prerequisites: [Basic Summon](#basic-summon)  
Range: Short  
Targets: None  
Cost: Variable (See Special) (Upkeep: 2 MP)  
Special: You summon a friendly Advanced Summon creature to assist you in combat. The creature summoned is described below.
You may spend MP up to a maximum of your level and a minimum of 6. The being summoned has max HP equal to five times the amount of MP spent. In addition, you may select one Advanced Option.
***

## The Base Summons
These are the stats of the base summoned creatures.

### Basic Summon  
Strength: 1  
Finesse: 1  
Toughness: 1  
Mind: 1  
Soul: 1  
Heart: 1  
HP Per MP spent summoning: 5  
MP Max: - (Uses the summoner's MP)  
Physical Attack: 2  
Mental Attack: 2  
Physical Defense: 12  
Mental Defense: 12  

### Advanced Summon  
Strength: 2  
Finesse: 2  
Toughness: 2  
Mind: 2  
Soul: 2  
Heart: 2  
HP Per MP spent summoning: 5  
MP Max: - (Uses the summoner's MP)  
Physical Attack: 4  
Mental Attack: 4  
Physical Defense: 14  
Mental Defense: 14  
***

## Summon Configuration  
There are four broad categories a summoned creature can fall into. Defender, Physical Attacker, Mental Attacker, and Support. You gain access to these configurations through the following Lesson:  

### Summoning Attunement
When you gain this Lesson, pick one of the following: Defender, Mental Attacker, Physical Attacker, or Support. Whenever you use a [Summoning] Ability, you can summon an Ally of the corresponding type.

#### Summon Configuration: Defender  
Summons created with this Configuration have twice as much HP as other types, as well as a bonus to Physical and Mental Defense equal to twice your Hero Tier. This ally cannot move once per turn for free like other summons; it must take a minor action from the summoner to move. Summons created this way have Taunt, and the following option for the Summoner:
//TODO scaling

##### Overwhelm 
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
The Defender ally makes an Attack with a x1 damage multiplier. If this attack succeeds, the ally Provokes the target until the start of your next turn.

#### Summon Configuration: Mental Attacker  
Summons created with this Configuration have a bonus to Mental Attack equal to twice your Hero Tier. Summons created this way have two options.
//TODO scaling

##### Zap  
Spell   
Action: None  
Range: Medium  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Mental Attacker ally makes a mental attack with a x1 multiplier. This can be done for free once per turn.

##### Empowered Zap  
Spell  
Action: Minor  
Range: Medium  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
The Mental Attacker ally makes a mental attack with a x2 multiplier. This cannot be done on the same turn where Zap has already been used.

#### Summon Configuration: Physical Attacker  
Summons created with this Configuration have a bonus to Physical Attack equal to twice your Hero Tier. This ally may move two spaces per turn for free. This ally has two options.
//TODO scaling

##### Strike  
Attack  
Action: None  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Mental Attacker ally makes a physical attack with a x1 multiplier. This can be done for free once per turn.

##### Empowered Strike  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP 
The Mental Attacker ally makes a physical attack with a x2 multiplier. This cannot be done on the same turn where Strike has already been used.

#### Summon Configuration: Support  
Summons created with this Configuration have the following options.
//TODO rework

##### Soothe  
Auxiliary  
Action: None  
Range: Short  
Targets: 1 ally  
Summoner MP Cost: 0  
The Support ally increases the target's Regen by 1. This can be done for free once per turn.

##### Empowered Soothe  
Auxiliary  
Action: Minor  
Range: Short  
Targets: 1 ally  
Summoner MP Cost: 2  
The Support ally increases the target's Regen by 2. This cannot be done on the same turn where Soothe has already been used.
***

## Summoning Lessons

#### Assisting Summon  
Prerequisites: [Summon Configuration: Support](#summon-configuration-support)  
Your summons gain an additional +1 to Physical and Mental Defense. In addition, when your Support Configuration uses Soothe or Empowered Soothe, the target is immediately healed for the same amount as it gain in Regen. (So 1 HP for Soothe, 2 HP for Empowered Soothe, when looking at the default Support Configuration summon.)

#### Basher Summon  
Prerequisites: [Summon Configuration: Physical Attacker](#summon-configuration-physical-attacker)  
Your summons gain an additional +1 to Physical and Mental Attack. Your Physical Attack Configuration ally against the following option:

##### Bash  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
Special: This attack has a x1 multiplier and moves the target one square.  

#### Blaster Summon  
Prerequisites: [Summon Configuration: Mental Attacker](#summon-configuration-mental-attacker)  
Your summons gain an additional +1 to Physical and Mental Attack. Your Mental Attack Configuration ally gains the following option:

##### Blast  
Spell  
Action: Minor  
Range: Medium  
Targets: 1 square  
Summoner MP Cost: 2 MP  
Special: The Mental Attacker ally makes a mental attack on all creatures in the square with a x1 multiplier. This cannot be done on the same turn where Zap has already been used.

#### Bodyguard Summon  
Prerequisites: [Summon Configuration: Defender](#summon-configuration-defender)  
Your summoned allies gain an additional +1 to Physical and Mental Defense. In addition, your Defender Configuration ally may, as a minor action from the summoner, provide Cover to one creature in the same square as it. While doing this, the ally loses the Taunt property. This Cover lasts until the summoner chooses to withdraw it or if the creature provided Cover moves out of that your Defender Configuration's square, at which point the Defender immediately regains Taunt.

#### Channeling Summon  
You may use Spell and Auxiliary Abilities from your summoned ally's position. Utilizing this option increases the cost of the Ability by said Ability's tier. So a tier 1 Ability costs 1 additional MP, a tier 2 Ability costs 2 additional MP, and so on.  
When utilizing this option, the Ability functions in all ways as though used by yourself, but if your ally is not in the same square as you, you may treat the origin of your Ability as your ally's square, effectively extending your range.

#### Extra Options  
Prerequisites: [Advanced Summon](#advanced-summon)  
You may choose to increase the Upkeep of Advanced Summon by 1. If you do, you may choose an additional Advanced Option.

#### Elemental Summons  
Prerequisites: [Elemental Attunement](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#elemental-attunement)  
When you use Summon, you may select an element you have Elemental Attunement to. Your ally is resistant to damage of that element, and all damage it deals is of that element.

#### Sturdy Summons  
Your summons gain an additional +1 to Physical and Mental Defense. In addition, they gain one more HP per MP spent to summon them. ([Defender Configuration](#summon-configuration-defender) summons double this additional HP as well.)
***

## Advanced Options  
When using [Advanced Summon](#advanced-summon) or a stronger versions of Summon, the summoned creature gains an Advanced Option. These are additional options the summoned creature benefits from.

### Universal Options  
These options are available to all summon configurations.

#### Attack Up  
Increase your summoned ally's Mental and Physical Attack by your Hero Tier.

#### Defense Up  
Increase your summoned ally's Mental and Physical Defense by your Hero Tier.

### Defender Options  
These options are available only to [Defender Configuration](#summon-configuration-defender) summons.

#### Summoned Armor Crush  
When using its Overwhelm ability, your Defender Configuration ally may use its Physical Defense - 10 in place of Physical Attack. Its damage multiplier also increases by 1.

#### Summoned Thorns X  
When struck by a melee range attack, your Defender Configuration ally deals X damage to the attacker, where X equals half the MP used to initially summon it.

### Mental Attacker Options  
These options are available only to [Mental Attack Configuration](#summon-configuration-mental-attacker) summons.

#### Summoned Flight  
Your summoned ally has Flight.

#### Hindering Zap  
Increase your ally's damage multipliers by 1. In addition, when hitting with your ally's Empowered Zap ability you also cause the target to be unable to move with its minor action for 1 round.

### Physical Attacker Options  
These options are available only to [Physical Attack Configuration](#summon-configuration-physical-attacker) summons.

#### Summoned Draining Strike  
Increase your ally's damage multipliers by 1. In addition, when hitting with your ally's Empowered Strike ability you also reduce the target's Degen by your Hero Tier.

#### Summoned Flight  
Your summoned ally has Flight.

### Support Options  
These options are available only to [Support Configuration](#summon-configuration-support) summons.

#### Summoned Shield X  
When your ally uses Soothe or Empowered Soothe, the targeted ally also gains [Shield](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#shield-x) equal to X, where X is half the MP used to initially summon it.

#### Summoned Soother  
Increase the effect of Soothe by 1, and Empowered Soothe by your Hero Tier.
***  

## Talent

#### Double Summon
You may have two summon allies active at the same time.
