---
tags: 
Nation: 
town: 
dg-publish: true
dg-hide-in-graph: true
---

### Important Characters 
```dataview
TABLE WITHOUT ID
  file.link AS "Character", Nation as "Home Nation", town as "Home Town"
FROM #Important and !"Admin"
SORT file.name
```

### All Characters 
```dataview
TABLE WITHOUT ID
  file.link AS "Character", Status as "Status", age + " " + race + " " + gender AS "Description", Nation as "Home Nation", town as "Home Town"
FROM "Named Characters & Beasts" and !#Important and !"Named Characters & Beasts/Named Characters & Beasts"
SORT file.name
```



