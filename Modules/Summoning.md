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
  - [Attacker](#summon-configuration-physical-attacker)
  - [Defender](#summon-configuration-defender)
  - [Spellcaster](#summon-configuration-spellcaster)
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
  - [Spellcaster Options](#spellcaster-options)
  - [Attacker Options](#physical-attacker-options)
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
When you use this Ability, choose one version of Summon Configuration benefits to add to the summoned creature.  
You may spend MP up to a maximum of your level when you first use this Ability. The being summoned has HP, Offense, and Defense, based on the MP used and which Summon Configuration you choose, explained in each individual [Summon Configuration](#summon-configuration] entry.  
Summoned creatures may move during the summoner's turn once for free. The summoner may use a Minor action to move the ally a second square.  
You may only summon one creature at a time. If a summoned creature runs out of HP, you cannot use Summon with the the same Summon Configuration for one hour. If you have multiple Summon Configuration options, you may choose to summon a different one by using this Ability again.  
Description: This Ability allows you to draw a second creature to your aid in combat. This could be the result of necromancy, alchemy, robotics, conjuration, imbuing a familiar with combat ability, ritual summoning, or any other effect that would result in an additional creature involved in the combat. As long as you pay the MP cost and the ally is not killed, the creature remains on hand to help in combat.  
It is up to the player and Arbiter how to handle summons running out of HP. The summoned creature can be forced back to wherever it was summoned from, limp away from battle to return after spending some time resting, fall apart and need to be repaired, run out of ammo/power, die and be discarded for a cheap replacement, or whatever sort of justification is needed for your particular spin on summoning.  
Summoned creatures do not have MP of their own. Any of their Abilities that cost MP take from their original Summoner's MP.

> The high MP cost and Upkeep of this Ability makes it a poor choice for low level characters. No one can stop you from taking this as one of your first three Abilities, but this would typically be a poor tactical decision as you should probably get a couple levels of Capacity to support the MP costs.

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
These are the stats of the base summoned creatures. These describe a Summon with 1 MP spent

### Basic Summon  
Strength: 1  
Finesse: 1  
Toughness: 1  
Mind: 1  
Soul: 1  
Heart: 1  
Physical Offense: +2  
Mental Offense: +2  
Physical Defense: 12  
Mental Defense: 12  

## Summon Configurations  
There are four broad categories a summoned creature can fall into. Attacker, Defender, Attacker, Spellcaster, and Support. You gain access to these configurations through the following Lesson:  

### Summoning Attunement
When you gain this Lesson, pick one of the following: Attacker, Defender, Spellcaster, or Support. Whenever you use a [Summoning] Ability, you can summon an Ally of the corresponding type.

#### Summon Configuration: Attacker  
This configuration is a hyper mobile ally that gets into melee with foes and deals physical damage.  
//TODO Consider making higher DPS focuses in Lessons  
For every MP used to summon it, the Attacker gains +1 to its Physical Offense and +5 Max HP. Every odd point of MP used to summon it (1, 3, 5, ...) gives is +1 Physical Defense, and every even point (2, 4, 6, ...) gives it +1 Mental Defense.  

| MP Spent to summon | Physical Offense | Physical Defense | Mental Defense | Max HP |
|--------------------|------------------|------------------|----------------|--------|
| 1                  | +3               | 13               | 12             | 5      |
| 2                  | +4               | 13               | 13             | 10     |
| 3                  | +5               | 14               | 13             | 15     |
| 4                  | +6               | 14               | 14             | 20     |
| 5                  | +7               | 15               | 14             | 25     |
...  

##### Strike  
Attack  
Action: None  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Spellcaster ally makes a physical attack with a x1 multiplier. This can be done for free once per turn.  

##### Empowered Strike  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 3 MP  
The Spellcaster ally makes a physical attack with a x2 multiplier. This cannot be done on the same turn where Strike has already been used.  

#### Summon Configuration: Defender  
This configuration serves as a source of cover. Though slower than the other types and not great at offense, it is much tougher and able to draw enemy attention to itself. 
//TODO rework  

#### Summon Configuration: Spellcaster  
This configuration is an ally with unremarkable mobility but high range.
//TODO Consider adding utility/ailment options in Lessons  
For every MP used to summon it, the Spellcaster gains +1 to its Mental Offense and +5 Max HP. Every odd point of MP used to summon it (1, 3, 5, ...) gives is +1 Mental Defense, and every even point (2, 4, 6, ...) gives it +1 Physical Defense.  

| MP Spent to summon | Mental Offense | Physical Defense | Mental Defense | Max HP |
|--------------------|----------------|------------------|----------------|--------|
| 1                  | +3             | 12               | 13             | 5      |
| 2                  | +4             | 13               | 13             | 10     |
| 3                  | +5             | 13               | 14             | 15     |
| 4                  | +6             | 14               | 14             | 20     |
| 5                  | +7             | 14               | 15             | 25     |

##### Zap  
Spell   
Action: None  
Range: Medium  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Spellcaster ally makes a mental attack with a x1 multiplier. This can be done for free once per turn.

##### Empowered Zap  
Spell  
Action: Minor  
Range: Long  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
The Spellcaster ally makes a mental attack with a x2 multiplier. This cannot be done on the same turn where Zap has already been used.

#### Summon Configuration: Support  
The Support configuration is not very good at dealing damage, but is able to keep summoners and their allies on their feet by sharing their HP.  
For every MP used to summon it, the Support gains +6 Max HP. In addition, every odd MP used (1, 3, 5, ...) gives it +1 Mental Defense, and every even MP used (2, 4, 6, ...) gives it +1 Mental Offense and Physical Defense.  
Support Summons have a value called their Healing Efficacy (generally shortened to just Efficacy). This number is used in its healing Abilities. It starts at 4, and every level divisible by 3 (3, 6, 9, ...) it increases by 1.  
//TODO Consider giving status ailment relief, other utilities in Lessons. Maybe efficiency Lesson that reduces the self drain on using Soothe  

| MP Spent to summon | Mental Offense | Physical Defense | Mental Defense | Max HP | Efficacy |
|--------------------|----------------|------------------|----------------|--------|----------|
| 1                  | +2             | 12               | 13             | 6      | 4        |
| 2                  | +3             | 13               | 13             | 12     | 4        |
| 3                  | +3             | 13               | 14             | 18     | 5        |
| 4                  | +4             | 14               | 14             | 24     | 5        |
| 5                  | +4             | 14               | 15             | 30     | 5        |
| 6                  | +5             | 15               | 15             | 36     | 6        |
...  

##### Jolt  
Spell  
Action: None  
Range: Short  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Support ally makes a Mental Attack with a x1 multiplier. This can be done for free once per turn, but cannot be used on the same turn as they use Soothe.  

##### Soothe  
Auxiliary  
Action: None  
Range: Short  
Targets: 1 ally  
Summoner MP Cost: 0  
The Support ally heals the target an amount equal to its Efficacy and loses that much HP. This can be done for free once per turn, but cannot be used on the same turn as they use Jolt.  

##### Empowered Soothe  
Auxiliary  
Action: Minor  
Range: Medium  
Targets: 1 ally  
Summoner MP Cost: 2 MP  
The Support ally heals the target an amount equal to twice its Efficacy and loses that much HP. This cannot be done on the same turn where Jolt or Soothe has already been used.  

***

## Summoning Lessons
//TODO: revise  

#### Assisting Summon  
Prerequisites: [Summon Configuration: Support](#summon-configuration-support)  
Your summons gain an additional +1 to Physical and Mental Defense. In addition, when your Support Configuration uses Soothe or Empowered Soothe, the target is immediately healed for the same amount as it gain in Regen. (So 1 HP for Soothe, 2 HP for Empowered Soothe, when looking at the default Support Configuration summon.)

#### Basher Summon  
Prerequisites: [Summon Configuration: Attacker](#summon-configuration-physical-attacker)  
Your summons gain an additional +1 to Physical and Mental Attack. Your Physical Attack Configuration ally against the following option:

##### Bash  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
Special: This attack has a x1 multiplier and moves the target one square.  

#### Blaster Summon  
Prerequisites: [Summon Configuration: Spellcaster](#summon-configuration-spellcaster)  
Your summons gain an additional +1 to Physical and Mental Attack. Your Spellcaster Configuration ally gains the following option:

##### Blast  
Spell  
Action: Minor  
Range: Medium  
Targets: 1 square  
Summoner MP Cost: 2 MP  
Special: The Spellcaster ally makes a mental attack on all creatures in the square with a x1 multiplier. This cannot be done on the same turn where Zap has already been used.

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
//TODO: revise  
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

### Spellcaster Options  
These options are available only to [Spellcaster Configuration](#summon-configuration-spellcaster) summons.

#### Summoned Flight  
Your summoned ally has Flight.

#### Hindering Zap  
Increase your ally's damage multipliers by 1. In addition, when hitting with your ally's Empowered Zap ability you also cause the target to be unable to move with its minor action for 1 round.

### Attacker Options  
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
You may have two summon allies active at the same time. When you gain this Talent, you also gain another [Summoning Attunement](#summoning-attunement) Lesson. If you already had all configurations before taking this Talent, you may instread refund the XP spent on one of those lessons.  
