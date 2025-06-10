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
One of the guards that went missing investigated the occurrence in [[Newhall]]. He went missing alongside [[Deputy Bridges]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```