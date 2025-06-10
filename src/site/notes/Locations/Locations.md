---
tags: 
Nation: 
town: 
dg-publish: true
dg-hide-in-graph: true
---
```dataview
TABLE WITHOUT ID
Nation, rows.file.link as "Towns & Cities"
from "Locations" and !#Display and !"Locations/Locations"
group by Nation 
SORT file.name
```
