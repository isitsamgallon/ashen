---
tags:
  - NPC
type:
  - important
  - The Auditors
Status: Unknown
dg-publish: true
icon: npc
age: Adult
race: Human
gender: Male
faction:
---
> [!infobox]
> 
> # `=this.file.name`
>![[Screenshot 2025-06-09 181640.png]]
> ###### Basic Information
> 
> | Type | Stat |
> | :----: | --- |
> | Race | Unknown |
> | Status | Unknown |
> | Nationality | Unknown |
> | Age | Unknown |
> | Alignment | Unknown |
> | Pronouns | He/ Him |
> | Faction | Unknown |
### Overview
Nehzahr of the [[Ebon Quill]], Keeper of Forgotten Lore. He is the writer of [[A Chronicle of Akin Netch - The Man of Many Faces]]. He is also known for a verity of other works, including collating [[Archivist Thalen]] research about [[Gods & Heralds]] into [[Ashen Gods]].

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```