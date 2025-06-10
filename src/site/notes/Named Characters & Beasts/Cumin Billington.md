---
tags:
  - NPC
Nation: OFC
town: Inchling Village
dg-publish: true
icon: npc
Status: Alive
faction:
  - Inchlings
race: Inchling
---

### Overview
[[Dill Billington]] 's mother and a resident of [[The Inchling Kingdom]]

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```