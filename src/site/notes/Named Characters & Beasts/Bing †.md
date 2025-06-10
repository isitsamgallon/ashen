---
tags:
  - NPC
Status: Dead
dg-publish: true
icon: npc
age: Adult
race: Goblin
gender: Male
faction: Goblin Mafia
---

### Overview
The goblin that was sent by the [[Goblin Mafia]] to assassinate [[The Party]]. They failed and when caught, took a cyanide pill. 

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```

#ConfirmedDead