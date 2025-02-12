---
Title:
---
## `=this.Title`
placeholder image
![[Pasted image 20241231221402.png]]

### Description: 

this is where the description goes

Upon selecting this as a Title gain: 

ability description


### Talents



```dataview 
table requisite, Title, Level
fROM "Rules/Talents/Title Talents"
Where contains(Title, this.Title)
SORT Level
```


