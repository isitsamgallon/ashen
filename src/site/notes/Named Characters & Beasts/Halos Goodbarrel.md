---
tags:
  - NPC
dg-publish: true
icon: npc
age: Adult
race: Halfling
gender: Male
Status: Alive
faction:
---

### Overview
The creator and founder of [[Halos Emporium]].

### Notable Information 
- This was [[James Absolom]] 's original character from another campaign. 

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```