---
Class: Mage
HPMOD: 6
---
# Mage

![[Pasted image 20250210192647.webp|348]]



### Class description

here is the class description

Hit point modifier: Fortitude/`=this.HPMOD`(increases each level by fortitude modifier)

#### Trained Class Skills: 
[[Knowledge]](Arcane arts), [[Arcane Arts]], 2x [[Knowledge]](), 

| Level | Progression                                                                                        |
| ----- | -------------------------------------------------------------------------------------------------- |
| 1     | [[#Characteristics boost]], [[#Proficiencies]], [[#Class Titles]], racial talent, [[#Mana Charge]] |
| 2     | [[Retaliation strike]], [[#Battle Tactics]], Skill advance, Class Title Talent                     |
| 3     | class Talent, General Talent                                                                       |
| 4     | Title Talent, Skill Advance, [[#Counter spell]]                                                    |
| 5     | class Talent, racial talent, General Talent, New Title                                             |
| 6     | Title Talent, Skill Advance, [[#Mana Siphon]]                                                      |
| 7     | class Talent, General Talent                                                                       |
| 8     | [[#Advanced Battle Tactics]], Skill Advance,  Title Talent                                         |
| 9     | class Talent, racial talent , General Talent                                                       |
| 10    | Title Talent, Skill Advance                                                                        |
| 11    | class Talent, General Talent                                                                       |
| 12    | Title Talent, Skill Advance                                                                        |
| 13    | class Talent, racial talent, General Talent                                                        |
| 14    | [[#Master Battle Tactics]], Skill Advance,  Title Talent                                           |
| 15    | class Talent, General Talent                                                                       |
| 16    | Title Talent, Skill Advance                                                                        |
| 17    | class Talent, racial talent, General Talent                                                        |
| 18    | Title Talent, Skill Advance                                                                        |
| 19    | class Talent, General Talent                                                                       |
| 20    | Skill Advance,  Title Talent                                                                       |
### Proficiencies

### Known Spells

Mages learn spells through study and practice. Starting at level 1, a mage knows as many spells as their [[Intellect]] modifier + 2. Each time a mage levels up, they gain a number of new spells equal to their intellect modifier.

A mages level determines what level of spells they can cast. Every two levels starting from level 1,  a mage can learn a new level of spell. For example, level 1 mage can learn level 1 spells. a level 3 mage can learn level 2 spells. 5=3, 7=4, 9=5, 11=6, 13=7, 15=8, 17=9.

### Class Titles


Titles let you focus your build in certain directions, letting you become an expert in a specific area for your build.  These are the class titles available to Fighter. Unlike regular titles, taking this as a class title gives you an extra benefit as listed below. 

####  [[Blood Mage]]

 Whenever you are casting an evoked spell(this does not include using magic items like rune stones) gain a +5 bonus to your [[Arcane Arts]] roll. 


#### [[Rune Mage]]

 Whenever you are casting a Channeled spell(this does not include using magic items like rune stones) gain a +5 bonus to your [[Arcane Arts]] roll. 

#### [[Witch]]

 Whenever you are casting a Ritual spell(this does not include using magic items like rune stones) gain a +5 bonus to your [[Arcane Arts]] roll. 



### Class Abilities:

#### Characteristics boost
at level 1, the mage gets to add 1d10 to [[Arcane Arts]]. 

#### Mana Charge
all mages have the ability to charge mana. while this might not be the most efficient way to generate mana, it is a way to get access to mana one might not be able to generate normally.  As a standard action, the mage taps into the well force of magic that permeates all living things. they are able to focus and harness a small amount of that mana to be used. Without storage, the mana will disappear after 1 turn. Generate 1 mana of a type of your choice

#### Mana Siphon
Mages can eventually learn the ability to siphon mana directly from objects or people. As a standard action, the mage can focus in on mana that is floating or stored inside an object. they can then siphon that mana and add it to their own.  For example, if a blood mage holds a powerful runic talisman, they can mana siphon 1 stored mana from within the talisman to use for themselves. Conversely, if two mages are combating one another, and a mage generates mana using mana charge, another mage could attempt to mana siphon that mana for themselves.    Mana siphon is an [[Arcane Arts]] test, and is an opposed one when trying to siphon mana from an unwilling creature. 



#### Counter spell
 discover a deeper understanding for interacting with other mages in combat.  As a reaction, when an opposing mage casts a spell, the player may spend mana of any type to attempt to counter spell. after the opposing mage has rolled for the success of their spell, the player may make an opposing [[Arcane Arts]] test to attempt to counter the spell. if they succeed the spell fizzles out. The Counter Spells effective level is equal to the mana spent. The maximum mana that can be spent to counter spell is equal to the highest level of spell you can cast. 

for each spell level below the counter spell level, receive a +10 modifier to your counter spell roll. 

for each level the spell is above the counter spell level receive a -10 to the roll. 



### Class Talents
```dataview 
table requisite, Class, Level
fROM "Rules/Talents/Class talents"
WHERE contains(Class, this.Class)
SORT Level
```