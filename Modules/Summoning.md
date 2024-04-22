# Summoning
**Table of Contents**  
- [Abilities](#abilities)  
  - [Summon](#summon)  
- [The Base Summons](#the-base-summons)  
  - [Basic Summon](#basic-summon)  
- [Summon Configuration](#summon-configuration)
  - [Summoning Attunement](#summoning-attunement)
  - [Attacker](#summon-configuration-physical-attacker)
  - [Defender](#summon-configuration-defender)
  - [Spellcaster](#summon-configuration-spellcaster)
  - [Support](#summon-configuration-support)
- [Summoning Lessons](#summoning-lessons)  
  - [Basher Summon](#basher-summon)
  - [Blaster Summon](#blaster-summon)
  - [Bodyguard Summon](#bodyguard-summon)
  - [Channeling Summon](#channeling-summon)
  - [Extra Options](#extra-options)
  - [Elemental Allies](#elemental-allies)
  - [Sturdy Allies](#sturdy-allies)
- [Advanced Options](#advanced-options)
  - [Universal Options](#universal-options)
  - [Defender Options](#defender-options)  
  - [Spellcaster Options](#spellcaster-options)
  - [Attacker Options](#physical-attacker-options)
  - [Support Options](#support-options)
- [Talent](#talent)  
  - [Double Summon](#double-summon)
 
# Abilities

## Summon    
Auxiliary [Summoning]  
Action: Minor  
Prerequisites: None  
Range: Short  
Targets: None  
Cost: Variable (See Special) (Upkeep: 2 MP)  
Special: You summon a friendly Summon Ally (henceforth shortened to Ally) to assist you in combat. The creature summoned is described below.  
When you gain this Ability, you automatically gain the [Summoning Attunement](#summoning-attunement) Lesson once.  
When you use this Ability, choose one version of Summon Configuration benefits to add to your Ally.  
You may spend MP up to a maximum of your twice your Level when you first use this Ability. The Ally has HP, Offense, and Defense based on the amount of MP used and which Summon Configuration you choose, explained in each individual [Summon Configuration](#summon-configuration) entry.  
Allies may move during the summoner's turn once for free. The summoner may use a Minor action to move the Ally a second square.  
Summoned creatures do not have MP of their own. Any of their Abilities that cost MP take from their Summoner's MP.  
You may only summon one Ally at a time. If an Ally runs out of HP, you cannot use Summon with the the same Summon Configuration for one hour. If you have multiple Summon Configuration options, you may choose to summon a different one by using this Ability again.  
If you spend 12 or more MP to cast this Ability, the Summoned Ally gains one [Advanced Option](#advanced-options) which allows the summoned creature to be further customized.  
Description: This Ability allows you to create or summon a second creature to your aid in combat. This could be the result of necromancy, alchemy, robotics, conjuration, imbuing a familiar with combat ability, calling a sidekick, or any other effect that would result in an additional creature involved in the combat. As long as you pay the Upkeep cost and the Ally is not killed, the creature remains on hand to help in combat.  
It is up to the player and Arbiter how to handle summons running out of HP. The summoned creature can be forced back to wherever it was summoned from, limp away from battle to return after spending some time resting, fall apart and need to be repaired, run out of ammo/power, die and be discarded for a cheap replacement, or whatever sort of justification is needed for your particular spin on summoning.  

> The high MP cost and Upkeep of this Ability makes it a poor choice for low level characters. No one can stop you from taking this as one of your first three Abilities, but this would typically be a poor tactical decision as you should probably get a couple levels of Capacity to support the Upkeep cost.  
***

# The Base Summon
Here are the stats of the base Ally. These describe an Ally with 1 MP spent and before the bonuses of its Configuration are applied.  

## Base Summon  
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

# Summon Configurations  
There are four broad categories a summoned creature can fall into. Attacker, Defender, Attacker, Spellcaster, and Support. You gain access to these configurations through the following Lesson:  

## Summoning Attunement  
**Lesson**  
When you gain this Lesson, pick one of the following: Attacker, Defender, Spellcaster, or Support. Whenever you use a [Summoning] Ability, you can summon an Ally of the corresponding type.

### Summon Configuration: Attacker  
This configuration is a hyper mobile Ally that gets into melee with foes and deals physical damage.  
//TODO Consider making higher DPS focuses in Lessons  
The Attacker's statistics scale based on the MP used to summon it.

| MP Spent to summon | Physical Offense | Physical/Mental Defense | Max HP |
|--------------------|------------------|-------------------------|--------|
| 2                  | +5               | 13                      | 10     |
| 4                  | +6               | 13                      | 15     |
| 6                  | +7               | 14                      | 20     |
| 8                  | +8               | 14                      | 26     |
| 10                 | +9               | 15                      | 32     |
| 12                 | +10              | 16                      | 38     |
...  //TODO further scaling

#### Mobile  
Passive  
Attacker Allies can move two Squares for free each turn, one Square more than other summons can move freely.  

#### Strike  
Attack  
Action: None  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Attacker Ally makes a Physical Attack with a x1 multiplier. This can be done for free once per turn.  

#### Empowered Strike  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 3 MP  
The Attacker Ally makes a physical attack with a x2 multiplier. This cannot be done on the same turn where Strike has already been used.  

### Summon Configuration: Defender  
// TODO REBALANCE
This configuration serves as a source of cover. Though slower than the other types and not great at offense, it is much tougher and able to draw enemy attention to itself. 
//TODO more tanking options in lessons  
For every MP used to summon it, the Defender gains +1 to its Physical and Mental Defense and +7 Max HP. Every even point (2, 4, 6, ...) gives it +1 Physical Offense.  

| MP Spent to summon | Physical Offense | Physical Defense | Mental Defense | Max HP |
|--------------------|------------------|------------------|----------------|--------|
| 1                  | +2               | 13               | 13             | 7      |
| 2                  | +3               | 14               | 14             | 14     |
| 3                  | +3               | 15               | 15             | 21     |
| 4                  | +4               | 16               | 16             | 28     |
| 5                  | +4               | 17               | 17             | 35     |  

#### Immobile  
Passive  
Defender Allies cannot move for free once per turn, unlike other summoned Allies.  

#### Taunt  
Passive  
The Defender Ally must be targeted first, before other Allies in its square. For details, see the [handbook entry for Taunt](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#taunt).  

#### Slam  
Attack  
Action: None  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Defender Ally makes a Physical Attack with a x1 multiplier. This can be done for free once per turn.  

#### Demanding Slam  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2  
The Defender Ally makes a Physical Attack with a x1 multiplier using its Physical [Defense Bonus](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#defense-bonus). If this Attack hits, the Defender ally [Provokes](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#provoke) its target. This Ability cannot be used on the same Round as Slam.  


### Summon Configuration: Spellcaster  
// TODO REBALANCE
This configuration is an ally with unremarkable mobility but high range and damage output.
//TODO Consider adding utility/ailment options in Lessons  
For every MP used to summon it, the Spellcaster gains +1 to its Mental Offense and +5 Max HP. Every odd point of MP used to summon it (1, 3, 5, ...) gives is +1 Mental Defense, and every even point (2, 4, 6, ...) gives it +1 Physical Defense.  

| MP Spent to summon | Mental Offense | Physical Defense | Mental Defense | Max HP |
|--------------------|----------------|------------------|----------------|--------|
| 1                  | +3             | 12               | 13             | 5      |
| 2                  | +4             | 13               | 13             | 10     |
| 3                  | +5             | 13               | 14             | 15     |
| 4                  | +6             | 14               | 14             | 20     |
| 5                  | +7             | 14               | 15             | 25     |

#### Zap  
Spell   
Action: None  
Range: Medium  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Spellcaster Ally makes a Mental Attack with a x1 multiplier. This can be done for free once per turn.

#### Empowered Zap  
Spell  
Action: Minor  
Range: Long  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
The Spellcaster Ally makes a Mental Attack with a x2 multiplier. This cannot be done on the same turn where Zap has already been used.

### Summon Configuration: Support  
The Support configuration is not very good at dealing damage, but is able to keep summoners and their friends on their feet by sharing their HP.  
The Support's statistics scale based on the MP used to summon it. Support Allies have a value called their Healing Efficacy (generally shortened to just Efficacy). This number is used in its healing Abilities.  
//TODO Consider giving status ailment relief, other utilities in Lessons. Maybe efficiency Lesson that reduces the self drain on using Soothe  


| MP Spent to summon | Mental Offense | Physical/Mental Defense | Max HP | Efficacy |
|--------------------|----------------|-------------------------|--------|----------|
| 2                  | +4             | 14                      | 12     | 4        |
| 4                  | +5             | 14                      | 18     | 4        |
| 6                  | +5             | 15                      | 24     | 5        |
| 8                  | +6             | 16                      | 32     | 5        |
| 10                 | +7             | 17                      | 40     | 6        |
| 12                 | +7             | 18                      | 48     | 6        |
...  //TODO further scaling  

#### Resilient
Passive  
If a Support Ally runs out of HP, it can be re-summoned after one Round (as opposed to one hour).  

#### Jolt  
Spell  
Action: None  
Range: Short  
Targets: 1 enemy  
Summoner MP Cost: 0  
The Support Ally makes a Mental Attack with a x1 multiplier. This can be done for free once per turn, but cannot be used on the same turn as Soothe.  

#### Soothe  
Auxiliary  
Action: None  
Range: Short  
Targets: 1 ally  
Summoner MP Cost: 0  
The Support Ally heals the target an amount equal to its Efficacy and loses that much HP. This can be done for free once per turn, but cannot be used on the same turn as Jolt.  

#### Empowered Soothe  
Auxiliary  
Action: Minor  
Range: Medium  
Targets: 1 ally  
Summoner MP Cost: 2 MP  
The Support Ally heals the target an amount equal to twice its Efficacy and loses that much HP. This cannot be done on a turn where Jolt or Soothe has already been used.  

***

# Summoning Lessons
//TODO: revise  

## Basher Summon  
Prerequisites: [Summon Configuration: Attacker](#summon-configuration-physical-attacker)  
Your Allies gain an additional +1 to Physical and Mental Attack. Your Physical Attack Configuration Ally against the following option:

### Bash  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
Special: This attack has a x1 multiplier and moves the target one square.  

## Blaster Summon  
Prerequisites: [Summon Configuration: Spellcaster](#summon-configuration-spellcaster)  
Your Allies gain an additional +1 to Physical and Mental Attack. Your Spellcaster Configuration Ally gains the following option:

### Blast  
Spell  
Action: Minor  
Range: Medium  
Targets: 1 square  
Summoner MP Cost: 2 MP  
Special: The Spellcaster Ally makes a mental attack on all creatures in the square with a x1 multiplier. This cannot be done on the same turn where Zap has already been used.

## Bodyguard Summon  
Prerequisites: [Summon Configuration: Defender](#summon-configuration-defender)  
Your summoned Allies gain an additional +1 to Physical and Mental Defense. In addition, your Defender Configuration Ally gains the following option:  

### Summon's Guard  
Auxiliary  
Action: Minor  
Range: Melee  
Targets: 1 ally  
Summoner MP Cost: 1 MP  
Special: As long as your Ally is in the same Square as the target and conscious, the Ally provides that target with [Protection](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#protection) and gains [Shield](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#shield-x) equal to twice your [Hero Tier](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#hero-tier).

## Channeling Summon  
You may use Spell and Auxiliary Abilities from your summoned Ally's position. When utilizing this option, the Ability functions in all ways as though used by yourself, but if your Ally is not in the same square as you, you may treat the origin of your Ability as your Ally's square, effectively extending your range.

## Elemental Allies  
Prerequisites: [Elemental Attunement](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#elemental-attunement)  
When you use Summon, you may select an element you have Elemental Attunement to. Your Ally is resistant to damage of that element, and all damage it deals is of that element.

## Sturdy Allies  
Your Allies gain an additional +1 to Physical and Mental Defense. In addition, they gain one more HP per MP spent to summon them.
***
``` 
This section of the document (everything in this font) is currently deprecated while I make sure things are balanced up to this point.  
# Advanced Options  
//TODO: revise  
When using the [Summon](#summon) Ability and paying at least 6 MP to use it, the summoned creature gains an Advanced Option. These are additional options that empower your Summon Ally.

## Universal Options  
These options are available to all summon configurations.

### Attack Up  
Increase your summoned Ally's Mental and Physical Attack by your Hero Tier.

### Defense Up  
Increase your summoned Ally's Mental and Physical Defense by your Hero Tier.

## Defender Options  
These options are available only to [Defender Configuration](#summon-configuration-defender) Allies.

### Summoned Armor Crush  
When using its Overwhelm ability, your Defender Configuration Ally may use its Physical Defense - 10 in place of Physical Attack. Its damage multiplier also increases by 1.

### Summoned Thorns X  
When struck by a melee range attack, your Defender Configuration Ally deals X damage to the attacker, where X equals half the MP used to initially summon it.

## Spellcaster Options  
These options are available only to [Spellcaster Configuration](#summon-configuration-spellcaster) Allies.

### Summoned Flight  
Your summoned Ally has Flight.

### Hindering Zap  
Increase your Ally's damage multipliers by 1. In addition, when hitting with your Ally's Empowered Zap ability you also cause the target to be unable to move with its minor action for 1 round.

## Attacker Options  
These options are available only to [Physical Attack Configuration](#summon-configuration-physical-attacker) Allies.

### Summoned Draining Strike  
Increase your Ally's damage multipliers by 1. In addition, when hitting with your Ally's Empowered Strike ability you also reduce the target's Degen by your Hero Tier.

### Summoned Flight  
Your summoned Ally has Flight.

## Support Options  
These options are available only to [Support Configuration](#summon-configuration-support) Allies.

### Summoned Shield X  
When your Ally uses Soothe or Empowered Soothe, the targeted Ally also gains [Shield](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#shield-x) equal to X, where X is half the MP used to initially summon it.

### Summoned Soother  
Increase the effect of Soothe by 1, and Empowered Soothe by your Hero Tier.
***  
```

# Talent

## Double Summon
You may have two summon Allies active at the same time. When you gain this Talent, you also gain another [Summoning Attunement](#summoning-attunement) Lesson. If you already had all configurations before taking this Talent, you may instead refund the XP spent on one of those lessons.  
Whenever you use your Minor Action for your Ally, you may affect both Allies if you have multiple summoned. This allows you to move and/or Empower both of your Allies with one Minor Action.  
