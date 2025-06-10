---
tags:
  - NPC
Nation: The Golden Fleet
town: Snowport
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction:
  - The Golden Fleet
---

### Overview
Captain of the [[The Golden Fleet]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```
