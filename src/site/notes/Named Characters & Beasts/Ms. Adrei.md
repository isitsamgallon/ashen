---
tags:
  - NPC
Nation: Ehobel
Status: Alive
dg-publish: true
icon: npc
age: Adult
race: Elf
gender: Female
faction:
---

### Overview
The damsel in distress who fell for a bandit leader that robbed her in [[Ehobel]]

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```