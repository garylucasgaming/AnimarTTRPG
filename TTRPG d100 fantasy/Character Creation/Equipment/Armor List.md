
## Armor List

```dataview 
table Covers, Item_Weight
fROM "Rules/Equipment/Armor"
SORT choice(Item_Weight = "Light", "1", choice(Item_Weight = "Medium", "2", choice(Item_Weight = "Heavy", "3", "other")))
SORT Covers
```
