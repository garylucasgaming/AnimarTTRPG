## Skills

Skills are the backbone of this system. Every action taken uses a skill roll. you can use whatever skill roll you like to complete an action, but must make a case to the Game master for why your character could use that skill to solve the problem at hand.    

Skills have a base value determined by their corresponding characteristic. for instance, weapon skill(Great sword) is strength based since a great sword is strength based melee weapon. so this skill would start at the character modifier for strength x 10. 

basic skills can be used untrained, however do so at less effectiveness. 

Skills advance with levels. Skills start as untrained, and on character creation based on class and race, you gain some skills that become trained. Through advancement and character level you can upgrade skills into higher tiers. 

the skill tiers are as follows:  **untrained**, **trained**, **Intermediate**, **Expert**

A skill can only be advanced if it meets the level requirement:

| Skill Level  | Character Level                        | Effect               |
| ------------ | -------------------------------------- | -------------------- |
| untrained    | any level                              | characteristic - 10  |
| trained      | 2+(outside of starting trained skills) | characteristic       |
| intermediate | 6+                                     | characteristic + 10  |
| expert       | 13+                                    | characteristic  + 30 |



![[Skill Test#Skill test]] 


#### test Difficulty 

| Difficulty  | Modifier |
| ----------- | -------- |
| easy        | +30      |
| routine     | +20      |
| ordinary    | +10      |
| challenging | 0        |
| difficult   | -10      |
| hard        | -20      |
| very hard   | -30      |
opposition tests do not get a difficulty modifier applied to them unless a tool or device is used to aid the individual in such things. 

##### Assistance
another player can help a player making a test. to do so, both players must have the skill being tested. The player with the higher skill must be the one making the test. No more than 1 character can assist with a test.  The effect of assisting, is the difficulty of the test is reduced by 1. 

> [!Tip]+ Example of Skill roll. 
> Johnny wants to attack with his Great Sword. Great swords are strength based so Weapon Skill(Great sword) will be based off the strength characteristic. Johnny has 47 in strength, which means he has a strength modifier of 4. his weapon skill(Great sword) will then have a base value of 40. (strength modifier of 4 X 10 when trained in this skill). 
> to attack with his great sword, johnny rolls a d100, and he gets a 25. 25 is lower than his value of 40, so he succeeds his roll. Johnny also rolled 15 points lower than his value, which would give him 1 degree of success. 
> Johnny's opponent then rolls an evasion skill test, to try and dodge the attack. They roll a 60, and their skill value is 30. they fail their roll and johnny successfully hits his opponent. 

### Skill List

```dataview 
table Stat, UseUntrained
FROM "mechanics glossary"
WHERE contains(tags, "Skill")
SORT Name
```