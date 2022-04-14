# Adversaries and Monsters
/* TODO For now this is going to be where I list and describe monsters written. Eventually I need to write a more concrete introduction about how to use monsters, notes about how the entries are kept generic with a few details left unwritten so one entry can potentially represent many different types of monsters, how to read these entries, and the like. For now I want to skip to actually sharing monster entries to give an idea of how I would want these entries to be read by Shapers and used in games.  
Figure out how to explain adversary archetypes at some point. Add notes about figuring out skill mods when they’re not listed.
*/

# Table of Contents
- [Bystander](#bystander)
- [Creeps](#creeps)
- [Defenders](#defenders)
- [Grapplers](#grapplers)
- [Healers](#healers)
- [Magi](#magi)
- [Nuisances](#nuisances)
- [Rogues](#rogues)
- [Snipers](#snipers)  
- [Thugs](#thugs)  
- [Slimes](#slimes)
- [Warriors](#warriors)

## Bystander
A bystander represents a person who has no combat training and nothing about them that would be suitable to fighting. They are more likely to try to run, hide, or seek assistance from someone actually ready to fight during combat. The person they represent may have different Attributes, but with no combat ability or experience they are unlikely to be able to effectively use them when a fight breaks out.  
Strength 0  
Finesse 0  
Toughness 0  
Mind 0  
Soul 0  
Heart 0  
HP Max: 10  
Physical Attack: 0  
Mental Attack: 0  
Physical Defense: 10  
Mental Defense: 10   

*Desperate Strike* (Major action attack), x1 multiplier, physical, melee, made with Bane -3.

## Creeps
Creeps represent enemies who rely on cheap tricks and numbers. Individually they usually aren’t that dangerous, but adventurers will never actually encounter creatures like these alone. They fight by trying to pile onto individual targets and overwhelm them with sheer numbers. In generally they should be small or scrawny creatures. These can be creatures like goblins, kobolds, imps, small and disposable aliens in part of a hive mind, and the like.  
Their elemental properties should generally be unimpressive: at best they resist as many elements as they are weak to. Perhaps they even have more weaknesses than resistances. For example, the modern image of a kobold is a creature that spends its life in caves. This could mean they resist earth but are weak to sky and fire. Goblins are sometimes depicted having an affinity for gunpowder, so perhaps they resist fire and are weak to ice and earth.

### Lesser Creep  
Strength 1  
Finesse 1  
Toughness 0  
Mind -1  
Soul -1  
Heart -1  
HP Max: 8  
Physical Attack: 2  
Mental Attack: -2  
Physical Defense: 11  
Mental Defense: 8  

*Melee strike* (Major action attack), x1 multiplier, physical, melee.  
*Hoard Tactics* (Passive): If in a square with two other allied Creeps, Melee Strike has Boon 4 on Offense rolls. 

## Defenders
Defenders represent enemies whose main goal is to ensure the safety of their allies. They block attacks and focus on being difficult to take down, giving their allies cover during combat. They are often especially concerned with the safety of healers. This could be a town guard with a shield, a mercenary, a bodyguard, or something similar.

#### Lesser Defender  
Strength 0  
Finesse 0  
Toughness 2  
Mind 0  
Soul 0  
Heart 1  
HP Max: 60  
Physical Attack: 0  
Mental Attack: 0  
Physical Defense: 14  
Mental Defense: 13  
Initiative: 0  

*Taunt* (Passive)  
*Defend* (Minor Aux), melee, target ally gains Cover, gain 2 Shield  
*Challenge* (Minor Attack/Spell), medium, target is Provoked, +4/+3 to hit  

#### Competent Defender  
Strength 0  
Finesse 0  
Toughness 2  
Mind 0  
Soul 0  
Heart 2  
HP Max: 60  
Physical Attack: 0  
Mental Attack: 0  
Physical Defense: 15  
Mental Defense: 15  
Initiative: 0  

*Taunt* (<Passive>)  
*Defend* (Minor Aux), melee, target ally gains Cover, gain 2 Shield  
*Challenge* (Minor Attack/Spell), medium, target is Provoked, +5 to hit  
*Shield Bash* (Major Attack), x1 damage, melee, physical, +5 to hit (PDef)
*Counter* (Counter Attack), x1 damage, melee, physical, +5 to hit (PDef)

## Grapplers
Grapplers are foes that focus on Grabbing their opponents, simultaneously holding them in place and crushing the life out of them. They are also fairly strong defensively to physical attacks, though they suffer in mental defense. This could be a wrestler, a ground fighter, a constrictor snake, or something similar.

#### Lesser Grappler
Strength 2  
Finesse 0  
Toughness 2  
Mind 0  
Soul -1  
Heart 0  
HP Max: 30  
Physical Attack: 3  
Mental Attack: -1  
Physical Defense: 14  
Mental Defense: 9  
Initiative: -1

*Grapple* (Major Attack), melee, 0 damage, Grab target on success
*Strike* (Major Attack), melee, x1 damage
*Suples* (Major Attack), melee, x2 damage, can only be used on Grabbed targets.

## Healers
Healers represent enemies whose primary action in combat is going to be repairing damage to their allies. They are also defensively solid, though generally not as much so as an equally powered [Defender](#defenders). They will generally try to keep distance from foes or hide behind someone with Taunt. This could be a spellcaster, a medic, a helpful creature such as a unicorn, or similar creatures who support other fighters.

#### Lesser Healer  
Strength -1  
Finesse 0  
Toughness 1  
Mind 0  
Soul 1  
Heart 3  
HP Max: 20  
MP Max: 3  
Physical Attack: 0  
Mental Attack: 2  
Physical Defense: 12  
Mental Defense: 13  
Initiative: 1  

*Heal* (Major Aux), medium, heal target 1d10  
*Big heal* (Major Aux), medium, heal target 2d10, 1 MP  
*Cleanse* (Minor Aux)  
Choose one:  
* Increase the target along one buff/debuff track of your choice by two. You can only increase the value up to 0.  
* Increase the target along all buff/debuff tracks by one. You can only increase the value up to 0.  
* *Dart* (Major Spell), x1 damage, one element, medium

#### Competent Healer  
Strength 0  
Finesse 0  
Toughness 1  
Mind 0  
Soul 1  
Heart 3  
HP Max: 35  
MP Max: 5  
Physical Attack: 0  
Mental Attack: 4  
Physical Defense: 14  
Mental Defense: 15  
Initiative: 1  

*Heal* (Major Aux), medium, heal target 1d10  
*Big heal* (Major Aux), medium, heal target 2d10, 1 MP  
Choose one:  
* Increase the target along one buff/debuff track of your choice by two. You can only increase the value up to 0.  
* Increase the target along all buff/debuff tracks by one. You can only increase the value up to 0.  
* *Dart* (Major Spell), x1 damage, one element, medium

## Hexer
Hexers are opponents who focus on limiting their enemies options using curses and other hindering effects. They are also defensively strong against magic, but vulnerable to physical attacks. This could be a cultist, a warlock, a curse-focused mage, or something similar.

#### Lesser Hexer
Strength -1  
Finesse 0  
Toughness 1  
Mind 0  
Soul 3  
Heart 0  
HP Max: 35  
Physical Attack: -1  
Mental Attack: 5  
Physical Defense: 11  
Mental Defense: 14  
Initiative: 3

*Offense Hex* (Major Spell), target loses one rank on the Offense Track  
*Defense Hex* (Major Spell), target loses one rank on the Defense Track  
*Zap* (Major Spell), x1 damage, choose one element for type, medium

#### Competent Hexer
Strength 0  
Finesse 0  
Toughness 1  
Mind 0  
Soul 3  
Heart 0  
HP Max: 35  
Physical Attack: -1  
Mental Attack: 7  
Physical Defense: 11  
Mental Defense: 15  
Initiative: 3

*Offense Hex* (Major Spell), target loses one rank on the Offense Track  
*Defense Hex* (Major Spell), target loses one rank on the Defense Track  
*Purge* (Major Aux), target loses two ranks on Offense/Defense Track, minimum 0  
*Zap* (Major Spell), x1 damage, choose one element for type, medium

## Magi
Magi tend to focus on doing damage from a medium distance. They often do elemental damage. They tend to hide behind Defenders or cover where they have the chance, as they are very fragile.

#### Lesser Mage
Strength -1  
Finesse 0  
Toughness 0  
Mind 3  
Soul 1  
Heart 0  
HP Max: 20  
MP Max: 4
Physical Attack: -1  
Mental Attack: 5  
Physical Defense: 10  
Mental Defense: 12  
Initiative: 1

*Zap* (Major Spell), x1 damage, choose one of two elemental types, medium  
*Quick Zap* (Minor Spell), x1 damage, physical, short, cannot be used on the same target as Zap in a round, 1 MP

#### Competent Mage  
Strength -1  
Finesse 0  
Toughness 0  
Mind 3  
Soul 2  
Heart 0  
HP Max: 25  
MP Max: 6  
Physical Attack: -1  
Mental Attack: 7  
Physical Defense: 11  
Mental Defense: 13  
Initiative: 2  

*Zap* (Major Spell), x2 damage, choose one of two elemental types, medium.  
*Quick Zap* (Minor Spell), x1 damage, physical, short, cannot be used on the same target as Zap in a round, 1 MP  
*Purge* (Minor Aux), Medium  
Choose one:  
* Reduce the target's Buff/Debuff track by 1, to a minimum of 0.  
* Remove the target's current Ward.  
* Reduce the target's regeneration/degeneration track by 2, to a minimum of 0.

## Nuisances
The Nuisance archetype represents small, elusive adversaries that utilize mental attacks against the heroes. These may appear in groups with other nuisances, or assist a more impressive threat as minor support. They generally shouldn’t appear alone, as their low hit points means individuals will typically be dealt with quickly. Example nuisances include pixies, will o’ wisps, imps, elemental motes, and the like.  
Elementally, Nuisances should have one resistance (which also determines the damage type of their attacks) and one weakness. A pixie might utilize Sky attacks while being weak to Fire. Imps that serve greater demonic masters may use bolts of Dark while being expelled by Light. These combinations should typically be straightforward.
   
#### Lesser Nuisance  
Strength -1  
Finesse 2  
Toughness -1  
Mind 2  
Soul 0  
Heart 1  
HP Max: 5   
Physical Attack: 1  
Mental Attack: 3  
Physical Defense: 12  
Mental Defense: 13  

*Elusive* (Passive): Physical damage against this target is halved.  
*Zap* (Major action spell): x1 multiplier, medium range. Damage type is the same as this creature’s elemental resistance.
*Fuddle* (Major action auxiliary): Curse, medium range, duration 2 rounds, must succeed on mental attack or it fails. Imposes Bane -2. 
Hover (Minor action auxiliary): Move one square and ignore a single Terrain effect for one round. 2 MP  

## Rogues

#### Competent Rogue  
Strength 0  
Finesse 3  
Toughness 0  
Mind 1  
Soul 0  
Heart 0  
HP Max: 30  
MP Max: 3  
Physical Attack: 6  
Mental Attack: 3  
Physical Defense: 14  
Mental Defense: 12  
Initiative: 3  

*Shoot* (Major Attack), x2 damage, physical, long  
*Dash* (Minor Aux), move 2  
*Hide* (Minor Aux), gain Stealth, Cooldown 1, 1 MP    
*Dodge* (Counter Aux), increase Defense by 2 against an incoming Ability  

## Slimes
Slimes come in many sizes and shapes. These could be a pool of magically animated gel, a huge amoeba, the result of an alchemical accident, or just blobs with faces on them. Slimes tend to be associated with a specific <Element> and generally deals damage of that type.

#### Medium Elemental Slime
Strength 3  
Finesse -1  
Toughness 4  
Mind -3  
Soul 0  
Heart 0  
HP Max: 25  
Physical Attack: +6  
Mental Attack: -  
Physical Defense: 13  
Mental Defense: 10  
 
*Favored Element*, each instance of this monster deals damage of a chosen element. Damage can be fire, ice, sky, earth, light, or dark.
*Absorb* (Major action Attack), x1 damage, Elemental, melee. On first success, the target is rooted. On a third success, target is grappled and this Attack's damage becomes x2
*Splash* (Major action Attack), x1 damage, Elemental, short.  
*Thorns* (Passive), anyone who attacks a Slime in melee range takes 4 Elemental damage. 

## Snipers
Archers, rifle-wielders, markspeople, assassins who rely on distance and steady aim. Their general tactic is going to be to find a safe place where they're away from the fighting or in an otherwise difficult to reach perch, and take their time aiming and firing consistent shots.

#### Minor Sniper
Strength -1  
Finesse 3  
Toughness 0  
Mind 0  
Soul 0  
Heart 0  
HP Max: 25  
MP Max: 0  
Physical Attack: +5  
Mental Attack: +0  
Physical Defense: 12
Mental Defense: 10

*Shoot* (Major action Attack), x1 damage, long.  
*Aim* (Minor action Auxiliary), gain Boon +2 on Shoot this turn.

#### Moderate Sniper
Strength -1  
Finesse 3  
Toughness 1  
Mind 0  
Soul 0  
Heart 0  
HP Max: 35  
MP Max: 0  
Physical Attack: +8  
Mental Attack: +0  
Physical Defense: 14
Mental Defense: 12

*Shoot* (Major action Attack), x1 damage, long.  
*Aim* (Minor action Auxiliary), gain Boon +2 on Shoot this turn.

#### Major Sniper
Strength -1  
Finesse 4  
Toughness 2  
Mind 0  
Soul 0  
Heart 0  
HP Max: 50  
MP Max: 0  
Physical Attack: +13  
Mental Attack: +0  
Physical Defense: 17
Mental Defense: 14

*Shoot* (Major action Attack), x1 damage, long.  
*Aim* (Minor action Auxiliary), gain Boon +2 on Shoot this turn.

## Thugs
Heavy fighters who rely on brute strength to fight. A drunk brawler, a burly brute, or bulky animals can be represented with Thugs. They take a very straightforward approach to combat; get close and hit as hard as they can. Their reliance on brute strength often leaves them open to attacks, but they have the sturdiness needed to take a few hits anyway.

#### Lesser Thug  
Strength 3  
Finesse 0  
Toughness 2  
Mind -1  
Soul -1  
Heart 0  
HP Max: 30  
Physical Attack: 6  
Mental Attack: -2  
Physical Defense: 12  
Mental Defense: 9  

*Strike* (Major action attack): x1 melee range, physical damage  
*Careless Strike* (Major action attack): x2 melee range, physical damage, incoming attack on the Thug gain Boon +2.

## Warriors
The Warrior archetype represents creatures trained in combat that utilize physical attacks against the players. They generally will prefer to get into melee range to deal high damage. They may appear in groups with Archers or other similar types who can benefit from their strengths and/or cover their weaknesses. They fight intelligently and will prioritize casters and archers where possible.

#### Lesser Warrior  
Strength 2  
Finesse 1  
Toughness 2  
Mind 0  
Soul -1  
Heart -1  
HP Max: 24  
Physical Attack: 5  
Mental Attack: -1  
Physical Defense: 14  
Mental Defense: 9  

*Jab* (Major action attack): x1 melee range, physical damage  
*Bash* (Major action attack): x1 melee range, physical damage, if Result is 5 or greater then the target and the Lesser Warrior move to an adjacent square, cooldown 3

#### Competent Warrior 
Strength 1  
Finesse 1  
Toughness 2  
Mind 0  
Soul 0  
Heart 0  
HP Max: 40  
Physical Attack: 5  
Mental Attack: 0  
Physical Defense: 15  
Mental Defense: 11  
Initiative: +1  

*Strike* (Major Attack), x2 damage, physical, melee  
*Shoot* (Major Attack), x1 damage, physical, medium  
*Restrain* (Major Attack), x1 damage, physical, melee, on success Grab   
*Bash* (Major action attack): x1 melee range, physical damage, if Result is 5 or greater then the target and the Lesser Warrior move to an adjacent square  
*Protect* (Minor Aux), target ally gains Cover  

#### Excellent Warrior 
Strength 2  
Finesse 1  
Toughness 2  
Mind 0  
Soul 0  
Heart 0  
HP Max: 70   
Physical Attack: 8  
Mental Attack: 0  
Physical Defense: 16  
Mental Defense: 13  
Initiative: +1  

*Strike* (Major Attack), x2 damage, physical, melee  
*Shoot* (Major Attack), x2 damage, physical, medium  
*Restrain* (Major Attack), x1 damage, physical, melee, on success Grab the target  
*Bash* (Major Attack), x1 damage, physical, melee, on success move target 1 square  
*Protect* (Minor Aux), target ally gains Cover  
