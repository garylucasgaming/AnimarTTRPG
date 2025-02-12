
## Weapon List

```dataview 
table Weapon_Type, Item_Weight
fROM "Rules/Equipment/Weapons"
SORT choice(Item_Weight = "Light", "1", choice(Item_Weight = "Medium", "2", choice(Item_Weight = "Heavy", "3", "other")))
SORT Weapon_Type
```
