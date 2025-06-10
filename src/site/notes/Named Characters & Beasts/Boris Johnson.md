---
tags:
  - NPC
Nation: The Dawn Empire
town: Steelwick
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction: 
---

### Overview 
Owns the [[Adventurers Guild]] in [[Steelwick]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```