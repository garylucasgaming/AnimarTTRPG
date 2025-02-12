---
Class: Fighter
HPMOD: 3
---
# Fighter

![[Pasted image 20250101025846.png| 300]]

## Class description

The fighter is a martial class that is adept at many fighting styles. having trained for years to master these skills, they are a fierce combatant on the battlefield. 

Hit point modifier: Fortitude/`=this.HPMOD`(increases each level by fortitude modifier)

#### Trained Class Skills: 
2x [[Weapon skill]](), [[Climb]], [[Intimidate]], [[Swim]], [[First Aid]]

| Level | Progression                                                                                                             |
| ----- | ----------------------------------------------------------------------------------------------------------------------- |
| 1     | [[#Characteristics boost]], [[#Proficiencies]], [[#Class Titles]], racial talent, [[Shield Block]], [[#Fighting Style]] |
| 2     | [[Retaliation strike]], [[#Battle Tactics]], Skill advance,  Title Talent                                               |
| 3     | class Talent, General Talent                                                                                            |
| 4     | Title Talent, Skill Advance                                                                                             |
| 5     | class Talent, racial talent, General Talent, New Title                                                                  |
| 6     | Title Talent, Skill Advance                                                                                             |
| 7     | class Talent, General Talent                                                                                            |
| 8     | [[#Advanced Battle Tactics]], Skill Advance,  Title Talent                                                              |
| 9     | class Talent, racial talent , General Talent                                                                            |
| 10    | Title Talent, Skill Advance                                                                                             |
| 11    | class Talent, General Talent                                                                                            |
| 12    | Title Talent, Skill Advance                                                                                             |
| 13    | class Talent, racial talent, General Talent                                                                             |
| 14    | [[#Master Battle Tactics]], Skill Advance,  Title Talent                                                                |
| 15    | class Talent, General Talent                                                                                            |
| 16    | Title Talent, Skill Advance                                                                                             |
| 17    | class Talent, racial talent, General Talent                                                                             |
| 18    | Title Talent, Skill Advance                                                                                             |
| 19    | class Talent, General Talent                                                                                            |
| 20    | Skill Advance,  Title Talent                                                                                            |

### Fighting Style
choose between one of the options and gain the relevant bonus. 

###### Dual Wielder
You no longer suffer a penalty for attacking with a weapon in your offhand. 

###### Great Weapon Fighter
Devastating hits with heavy weapons you make deal 3x damage. 

###### Archery
on a turn where you do not use your movement action, you can use your movement action to reload. 

###### Sword and Board
You may use an action to Shield Bash.  this is an attack that uses [[Weapon Skill]](improvised weapon).  if you successfully [[Shield Block]] the same target in your previous turn, you get a +10 bonus. 


### Class Titles:

Titles let you focus your build in certain directions, letting you become an expert in a specific area for your build.  These are the class titles available to Fighter. Unlike regular titles, taking this as a class title gives you an extra benefit as listed below. 

#### [[Defender]]
when you take this Title, increase physical damage reduction([[Slashing]], [[Bludgeoning]], [[Piercing]]) on shields you use by 1. 

#### [[Marksman]]
 When taking the aim action/bonus action, gain an additional +5 when using ranged Weapons. 

#### [[Veteran Soldier]]
######  Inspiring Command 
once per encounter, as an action, you may call to an ally. they gain +10 on their next action. 


### Proficiencies
medium and heavy armor, 

### Class Abilities:

#### Characteristics boost
at level 1, the fighter gets to add 1d10 to a [[Weapon Skill]]() of their choice and [[Fortitude]]. 

#### Battle Tactics 
Fighters are proficient in the art of combat. not only are they able to make quick decisions to outmaneuver their opponents, they are skilled in commanding others. 

Gain tactics points. your total tactics points is always equal to your fighter level. your tactics points reset after a long rest. 

you can spend tactics points to complete complex maneuvers in battle. 

| Tactics             | effect                                                                                                                                                                                                        | point cost |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Disorienting Strike | on a successful attack roll, after damage, you disorient your target such that they are unable to see the next attack coming. The next attack against that target, not by you, gets +20 to [[Weapon Skill]]() | 1          |
| Superior Blow       | after making a successful hit, you may expend tactics points to increase the severity of the blow. to go from weak to firm is 1 point, firm to strong is 3 points, strong to devastating 5                    | varies     |
| Lightning Strike    | after making a successful hit, after damage, you make attempt to make another attack at -20 [[Weapon Skill]]()                                                                                                | 1          |
| Commanding Strike   | after making a successful attack, you can make a call to a comrade who can hear or see you, they can use their reaction to make a movement at half their speed.                                               | 2          |
| Brace for Impact    | after an opponent has made a successful hit against you, but before damage, you can add the points spent to your physical damage reduction. (cannot exceed half your level. minimum 1)                        | varies     |
| Preparedness        | as an encounter begins, after initiatives have been rolled. you may have two comrades swap initiatives.                                                                                                       | 1          |

#### Advanced Battle Tactics 
add these new battle tactics to your battle tactics repertoire

| Tactics             | effect                                                                                                                                                                                                        | point cost |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Disorienting Strike | on a successful attack roll, after damage, you disorient your target such that they are unable to see the next attack coming. The next attack against that target, not by you, gets +20 to [[Weapon Skill]]() | 1          |
| Superior Blow       | after making a successful hit, you may expend tactics points to increase the severity of the blow. to go from weak to firm is 1 point, firm to strong is 3 points, strong to devastating 5                    | varies     |
| Lightning Strike    | after making a successful hit, after damage, you make attempt to make another attack at -20 [[Weapon Skill]]()                                                                                                | 1          |
| Commanding Strike   | after making a successful attack, you can make a call to a comrade who can hear or see you, they can use their reaction to make a movement at half their speed.                                               | 2          |


#### Master Battle Tactics 
add these new battle tactics to your battle tactics repertoire

| Tactics             | effect                                                                                                                                                                                                        | point cost |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| Disorienting Strike | on a successful attack roll, after damage, you disorient your target such that they are unable to see the next attack coming. The next attack against that target, not by you, gets +20 to [[Weapon Skill]]() | 1          |
| Superior Blow       | after making a successful hit, you may expend tactics points to increase the severity of the blow. to go from weak to firm is 1 point, firm to strong is 3 points, strong to devastating 5                    | varies     |
| Lightning Strike    | after making a successful hit, after damage, you make attempt to make another attack at -20 [[Weapon Skill]]()                                                                                                | 1          |
| Commanding Strike   | after making a successful attack, you can make a call to a comrade who can hear or see you, they can use their reaction to make a movement at half their speed.                                               | 2          |



### Class Talents

```dataview 
table requisite, Class, Level
fROM "Rules/Talents/Class talents"
WHERE contains(Class, this.Class)
SORT Level
```