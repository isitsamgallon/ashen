---
tags:
  - NPC
Nation: The Dawn Empire
town: Dawnhaven
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction:
  - Ivory Crest
---

### Overview
The guard [[The Party]] met in [[Dawnhaven]], is a part of the [[Ivory Crest]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```