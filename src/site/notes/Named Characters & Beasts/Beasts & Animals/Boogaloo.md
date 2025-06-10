---
tags:
  - NPC
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction: 
---

### Overview
The name of the horse that [[The Korrigan]] befriends in [[Session 21]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```