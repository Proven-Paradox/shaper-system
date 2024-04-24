# Summoning
**Table of Contents**  
- [Abilities](#abilities)  
  - [Summon](#summon)  
- [Summon Configurations](#summon-configurations)  
  - [Summoning Attunement](#summoning-attunement)  
  - [Attacker](#summon-configuration-attacker)  
  - [Defender](#summon-configuration-defender)  
  - [Spellcaster](#summon-configuration-spellcaster)  
  - [Support](#summon-configuration-support)  
- [Summoning Lessons](#summoning-lessons)  
  - [Basher Summon](#basher-summon)  
  - [Blaster Summon](#blaster-summon)  
  - [Bodyguard Summon](#bodyguard-summon)  
  - [Channeling Summon](#channeling-summon)  
  - [Elemental Allies](#elemental-allies)  
  - [Sturdy Allies](#sturdy-allies)  
- [Advanced Options](#advanced-options)  
  - [Universal Advanced Options](#universal-advanced-options)  
  - [Advanced Attacker Options](#advanced-attacker-options)  
  - [Advanced Defender Options](#advanced-defender-options)  
  - [Advanced Spellcaster Options](#advanced-spellcaster-options)  
  - [Advanced Support Options](#advanced-support-options)  
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
Special: You summon a friendly creature or character (henceforth shortened to Ally) to assist you in combat.  
When you gain this Ability, you automatically gain the [Summoning Attunement](#summoning-attunement) Lesson once.  
You may spend MP up to a maximum of your twice your Level when you first use this Ability. The Ally has HP, Offense, and Defense based on the amount of MP used and which Summon Configuration you choose, as explained in each individual [Summon Configuration](#summon-configurations) entry.  
Allies may move during the summoner's turn once for free. The summoner may use a Minor action to move the Ally a second square. They do not have MP of their own. Any of their Abilities that cost MP take from their Summoner's MP. You may only summon one Ally at a time.  
If an Ally runs out of HP, you cannot use Summon with the same Summon Configuration for one hour. If you have multiple Summon Configuration options, you may choose to summon a different one after another has been knocked out by using this Ability again.  
If you spend 12 or more MP to cast this Ability, the Summoned Ally gains one [Advanced Option](#advanced-options) which allows the summoned creature to be further customized.  
Description: This Ability allows you to create or summon a second creature to your aid in combat. This could be the result of necromancy, alchemy, robotics, conjuration, imbuing a familiar with combat ability, calling a sidekick, or any other effect that would result in an additional creature involved in the combat. As long as you pay the Upkeep cost and the Ally is not killed, the creature remains on hand to help in combat.  
It is up to the player and Arbiter how to handle summons running out of HP. The summoned creature can be forced back to wherever it was summoned from, limp away from battle to return after spending some time resting, fall apart and need to be repaired, run out of ammo/power, die and be discarded for a cheap replacement, or whatever sort of justification is needed for your particular spin on summoning.  

***

# Summon Configurations  
There are four broad categories a summoned creature can fall into: Attacker, Defender, Attacker, Spellcaster, and Support. You gain access to these configurations through the following Lesson:  

## Summoning Attunement  
**Lesson**  
When you gain this Lesson, pick one of the following: Attacker, Defender, Spellcaster, or Support. Whenever you use a [Summoning] Ability, you can summon an Ally of the corresponding type.  

### Summon Configuration: Attacker  
This configuration is a hypermobile Ally that gets into melee with foes and deals physical damage.  
//TODO Consider making higher DPS focuses in Lessons  
The Attacker's statistics scale based on the MP used to summon it.

| MP Spent to summon | Physical Offense | Physical/Mental Defense | Max HP |
|--------------------|------------------|-------------------------|--------|
| 2                  | +5               | 13                      | 10     |
| 4                  | +6               | 13                      | 16     |
| 6                  | +7               | 14                      | 22     |
| 8                  | +8               | 14                      | 29     |
| 10                 | +9               | 15                      | 36     |
| 12                 | +10              | 16                      | 43     |
...  //TODO further scaling

#### Mobile  
Passive  
Attacker Allies can move two Squares for free each turn.  

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
The Attacker Ally makes a physical attack with a x2 multiplier. This Ability cannot be used in the same Round as Strike.  

### Summon Configuration: Defender  
This configuration serves as a source of cover. Though slower than the other types and not great at offense, it is much tougher and able to draw enemy attention to itself.  
//TODO more tanking options in lessons  

| MP Spent to summon | Physical Offense | Physical/Mental Defense | Max HP |
|--------------------|------------------|-------------------------|--------|
| 2                  | +4               | 15                      | 14     |
| 4                  | +5               | 15                      | 21     |
| 6                  | +5               | 16                      | 28     |
| 8                  | +6               | 17                      | 37     |
| 10                 | +6               | 18                      | 46     |  
| 12                 | +7               | 19                      | 55     |
//TODO further scaling

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
Attack [Guardian Strike]  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2  
The Defender Ally makes a Physical Attack with a x1 multiplier. If this Attack hits, the Defender ally [Provokes](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#provoke) its target. This Ability cannot be used in the same Round as Slam.  


### Summon Configuration: Spellcaster  
This configuration is an ally with unremarkable mobility but high range and damage output.  
//TODO Consider adding utility/ailment options in Lessons  

| MP Spent to summon | Mental Offense | Physical/Mental Defense | Max HP |
|--------------------|----------------|-------------------------|--------|
| 2                  | +5             | 14                      | 10     |
| 4                  | +6             | 14                      | 15     |
| 6                  | +7             | 15                      | 20     |
| 8                  | +8             | 15                      | 26     |
| 10                 | +9             | 16                      | 32     |
| 12                 | +10            | 17                      | 38     |

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
The Spellcaster Ally makes a Mental Attack with a x2 multiplier. This Ability cannot be used in the same Round as Zap.  

### Summon Configuration: Support  
The Support configuration is not very good at dealing damage, but is able to keep summoners and their friends on their feet by sharing their HP.  
The Support's statistics scale based on the MP used to summon it. Support Allies have a value called their Healing Efficacy (generally shortened to just Efficacy). This number is used for its healing Abilities.  
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
The Support Ally heals the target for an amount equal to its Efficacy and loses that much HP. This can be done for free once per turn, but cannot be used on the same turn as Jolt.  

#### Empowered Soothe  
Auxiliary  
Action: Minor  
Range: Medium  
Targets: 1 ally  
Summoner MP Cost: 2 MP  
The Support Ally heals the target an amount equal to twice its Efficacy and loses that much HP. This Ability cannot be used in the same Round as Jolt or Soothe.   

***

# Summoning Lessons

### Basher Summon  
Prerequisites: [Summon Configuration: Attacker](#summon-configuration-attacker)  
Your Allies gain an additional +1 to Physical and Mental Attack. Your Physical Attack Configuration Ally gains the following option:

#### Summon Bash  
Attack  
Action: Minor  
Range: Melee  
Targets: 1 enemy  
Summoner MP Cost: 2 MP  
Special: This attack has a x1 multiplier and moves the target one square. This cannot be done on the same turn as [Strike](#strike).   

### Blaster Summon  
Prerequisites: [Summon Configuration: Spellcaster](#summon-configuration-spellcaster)  
Your Allies gain an additional +1 to Physical and Mental Attack. Your Spellcaster Configuration Ally gains the following option:

#### Summon Blast  
Spell  
Action: Minor  
Range: Medium  
Targets: 1 square  
Summoner MP Cost: 2 MP  
Special: The Spellcaster Ally makes a mental attack on all creatures in the square with a x1 multiplier. This cannot be done on the same turn where [Zap](#zap) has already been used.

### Bodyguard Summon  
Prerequisites: [Summon Configuration: Defender](#summon-configuration-defender)  
Your summoned Allies gain an additional +1 to Physical and Mental Defense. In addition, your Defender Configuration Ally gains the following option:  

#### Summon Guard  
Auxiliary  
Action: Minor  
Range: Melee  
Targets: 1 ally  
Summoner MP Cost: 0 MP  
Special: As long as your Ally is in the same Square as the target and conscious, the Ally provides that target with [Protection](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#protection) and gains [Shield](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#shield-x) equal to twice your [Hero Tier](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#hero-tier).  

### Channeling Summon  
You may use Spell and Auxiliary Abilities from your summoned Ally's position. When utilizing this option, the Ability functions in all ways as though used by yourself, but if your Ally is not in the same square as you, you may treat the origin of your Ability as your Ally's square, effectively extending your range.  

### Elemental Allies  
Prerequisites: [Elemental Attunement](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#elemental-attunement)  
When you use Summon, you may select an element you have Elemental Attunement to. Your Ally is resistant to damage of that element, and all damage it deals is of that element.  

### Sturdy Allies  
Your Allies gain an additional +1 to Physical and Mental Defense. In addition, they gain one more HP per 2 MP spent to summon them.  

***  

# Advanced Options  
When using the [Summon](#summon) Ability and paying at least 12 MP to use it, the summoned creature gains one of the following Advanced Options.  

## Universal Advanced Options  
These options are available to all summon configurations.  
  
### Offense Up  
Increase your summoned Ally's Mental and Physical Offense by 1.  

### Defense Up  
Increase your summoned Ally's Mental and Physical Defense by 1.  

## Advanced Attacker Options  
These options are available only to [Attacker Configuration](#summon-configuration-attacker) Allies.  

### Dazing Strike  
When hitting with your Ally's [Empowered Strike](#empowered-strike) Ability you also [Daze](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#daze) the target for 1 round. On a [Solid Hit](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#solid-hit), the duration increases to 2 rounds.  

### Draining Strike  
When hitting with your Ally's [Empowered Strike](#empowered-strike) Ability you also inflict [Degeneration](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#degeneration) with a duration equal to twice your [Hero Tier](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#hero-tier).  

### Attacker Flight  
Your summoned Attacker Ally has [Flight](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#flight).  

## Advanced Defender Options  
These options are available only to [Defender Configuration](#summon-configuration-defender) Allies.  

### Extended Demand  
Your Defender Ally's [Demanding Slam](#demanding-slam) Ability's Range increase to Medium.  

### Mobile Defender  
Your Defender Ally loses the [Immobile](#immobile) passive.  

### Thorns X  
When struck by a melee range Ability, your Defender Ally deals X damage to the attacker, where X equals half the MP used to initially summon it.  

## Advanced Spellcaster Options  
These options are available only to [Spellcaster Configuration](#summon-configuration-spellcaster) Allies.  

### Hindering Zap  
When hitting with your Ally's [Empowered Zap](#empowered-zap) Ability you also [Slow](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#slow) the target for 1 round. On a [Solid Hit](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#solid-hit), the duration increases to 2 rounds.  

### Purging Zap  
When hitting with your Ally's [Empowered Zap](#empowered-zap) Ability you also reduce one of the target's [Buff Tracks](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#buff-tracks) by 1, to a minimum of 0.  

### Spellcaster Flight  
Your summoned Spellcaster Ally has [Flight](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#flight).  

## Advanced Support Options  
These options are available only to [Support Configuration](#summon-configuration-support) Allies.  

### Cleansing Soothe  
When your Ally uses [Empowered Soothe](#empowered-soothe), you may either reduce the duration of one [Status Ailment](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#status-ailments) by 2 rounds or increase one of the target's [Buff Tracks](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#buff-tracks) by 1, to a minimum of 0.  

### Potent Healer  
Increase your Support Ally's Efficacy by 1.  

### Protective Support  
When your Ally uses [Empowered Soothe](#empowered-soothe), the target also gains [Shield](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#shield-x) equal to X, where X twice your [Hero Tier](https://github.com/Proven-Paradox/shaper-system/blob/main/Handbook.md#hero-tier).  

***  

# Talent  

## Double Summon  
You may have two summon Allies active at the same time. When you gain this Talent, you also gain another [Summoning Attunement](#summoning-attunement) Lesson. If you already had all configurations before taking this Talent, you may instead refund the XP spent on one of those lessons.  
Whenever you use your Minor Action for your Ally, you may affect both Allies if you have multiple summoned. This allows you to move and/or Empower both of your Allies with one Minor Action.  
