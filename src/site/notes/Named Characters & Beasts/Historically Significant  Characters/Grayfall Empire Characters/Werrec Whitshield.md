---
tags:
  - NPC
Nation: Dwarven Empire
town: Fort Molden
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Dwarf
gender: Male
faction: 
---

### Overview
The emperor of the remains of the [[Grayfall Empire]]. They are seen as a more measured and compassionate dwarf, who took up the mantle of leadership.

Under Werrec Whitshield's guidance, the [[Grayfall Empire]] underwent a transformation. He refocused efforts from revenge to survival and reconciliation. Abolishing the position of emperor, Werrec sought to rebuild and integrate his people into their new circumstances. His leadership marked a new chapter in the dwarven legacy, one characterised by peace and cooperation rather than conflict and conquest.

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```