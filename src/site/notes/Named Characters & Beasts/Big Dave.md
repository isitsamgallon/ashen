---
tags:
  - NPC
Nation: OFC
town: Inchling Village
dg-publish: true
icon: npc
Status: Alive
---

### Overview
Big Dave is a human who currently lives and works in [[The Inchling Kingdom]]. He isn't very smart and talks in simple words and phrases. He does the vast majority of the work in the kingdom by gathering food and cleaning messes when needed. 

### Notable Information 
- He is the raining fishing champion.

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```