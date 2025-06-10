---
tags:
  - NPC
Nation: The Dawn Empire
town: Newhall
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction: 
---

### Overview
A Farmer in [[Newhall]] lives outside the wall and, therefore, wasn't affected by the magic of [[Angel Under The Well]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```