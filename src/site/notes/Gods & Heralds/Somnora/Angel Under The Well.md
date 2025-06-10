---
dg-publish: true
race: Herald
icon: god
---
#INFORMATION_MISSING_OR_OUT-OF-DATE 

Angel under the well in [[Newhall]]

### History & Mentions
```dataview
TABLE WITHOUT ID
	file.link AS "§", 
	x AS "Interactions" FROM "Session Notes"
FLATTEN x WHERE contains(x,this.file.name) 
SORT file.name DESC
```