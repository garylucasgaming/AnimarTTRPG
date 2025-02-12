---
Name: Durin BronzeBeard
Race: "[[Dwarf]]"
Class: "[[Mage]]"
Title: "[[Defender]]"
SecondaryTitle: "[[Marksman]]"
HP: 0
Strength: 20
Dexterity: 20
Fortitude: 40
Intellect: 20
Education: 20
Charm: 20
Level: 1
---


## Character Sheet


###### Name `INPUT[text:Name]` Race `INPUT[inlineSelect(option([[Dwarf]]), option([[Elf]]), option([[Human]])):Race]`  Class `INPUT[inlineSelect(option([[Fighter]]), option([[Mage]]), option([[Rogue]])):Class]`

###### Class Title `INPUT[inlineSelect(option([[Defender]]), option([[Marksman]]), option([[Veteran Soldier]])):Title]`Secondary Title  `INPUT[inlineSelect(option([[Defender]]), option([[Marksman]]), option([[Veteran Soldier]]), option(none)):SecondaryTitle]` 


>###### Stats
   Level  `INPUT[number:Level]` 
> Class  `=this.Class` 
> Class Title  `=this.Title`
> Secondary Title  `=this.SecondaryTitle`
> HP `= round(this.Fortitude / this.Class.HPMOD) +  (this.Class.HPMOD * this.Level) + this.Race.HPMod - (this.Class.HPMOD)`
> Current HP `INPUT[number]` 
> Speed `= this.Dexterity + this.Race.SpeedMod`

> ###### Characteristics
>[[Strength]]  `INPUT[number:Strength]`
>[[Dexterity]] `INPUT[number:Dexterity]`
> [[Fortitude]] `INPUT[number:Fortitude]`
>[[Intellect]] `INPUT[number:Intellect]`
>[[Education]] `INPUT[number:Education]`
>[[Charm]]  `INPUT[number:Charm]`

| Skill                               | Stat                | UseUntrained | Advancement                                                                                 | Value             | Modifier |
| ----------------------------------- | ------------------- | ------------ | ------------------------------------------------------------------------------------------- | ----------------- | -------- |
| [[Appraise]]                        | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Arcane Arts]]                     | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Climb]]                           | Strength            | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Strength`  | 0        |
| [[Craft]]()                         | Intellect           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Intellect` | 0        |
| [[Deceive]]                         | Charm               | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Charm`     | 0        |
| [[Evasion Skill]]                   | Dexterity           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[First Aid]]                       | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Handle Animal]]                   | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Hide]]                            | Dexterity           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[Insight]]                         | Education           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Intimidate]]                      | Strength            | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Strength`  | 0        |
| [[Investigate]]                     | Charm               | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Charm`     | 0        |
| [[Knowledge]]()                     | Intellect           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Intellect` | 0        |
| [[Language]]()                      | Intellect           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Intellect` | 0        |
| [[Listen]]                          | Intellect           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Intellect` | 0        |
| [[Locks]]                           | Dexterity           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[Medicine]]                        | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[move silently]]                   | Dexterity           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[Navigate]]                        | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Perception]]                      | Education           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Persuade]]                        | Education, Charm    | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | -                 | 0        |
| [[Religion]]                        | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Ride]]()                          | Education           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Search]]                          | Intellect           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Intellect` | 0        |
| [[Sleight of Hand]]                 | Dexterity           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[Survival]]                        | Education           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Use Rope]]                        | Dexterity           | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Dexterity` | 0        |
| [[Swim]]                            | Education           | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Education` | 0        |
| [[Performance()]]                   | Charm               | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Charm`     | 0        |
| [[Weapon Skill(unarmed)]]           | Strength            | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Strength`  | 0        |
| [[Weapon Skill(improvised weapon)]] | Strength            | true         | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | `=this.Strength`  | 0        |
| [[Weapon Skill]]                    | Strength, Dexterity | false        | `INPUT[inlineSelect(option(Untrained), option(Trained), option(Advanced), option(Expert))]` | -                 | 0        |

