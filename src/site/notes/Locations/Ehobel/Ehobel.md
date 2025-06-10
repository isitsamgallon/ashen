---
dg-publish: true
Nation: Ehobel
icon: place
---
> [!infobox]
> 
> # `=this.file.name`
> ![[Ehobel_Map.jpg]]
> ###### Basic Information
> 
>  Type | Info |
> :----: | --- |
>  Primary Race | [[Elves]]|
>  Founder | Unknown |
>  Current Leader | [[Obeus Yelris]] |
>  ##### Cities & Towns 
>  ```dataview
>  table tags as "Discovery Status"
>  From "Locations"
>  WHERE contains( Nation, this.file.name)
>  ```


The home nation of the [[Elves]] in [[The Amber Realms]] and led by The Empress, [[Obeus Yelris]]. Obeus took over the role of Empress from her mother [[Ashira Yelris †]] some years ago. He is described in books as a very kind and understanding ruler and has "grand military plans". In reality, She doesn't leave the palace enough to understand the situation of her lands, let alone what was happening with her people. Ehobel was one of the main factions that made up [[The Coalition]] during [[The Sundering]]. During this period Ehobel had a very good relationship with [[The Dawn Empire]] after many wars. However, sometime after the Sundering, the nations began to despise each other again, causing [[4th Dawn vs Ehobel War]] which sprouted the offshoot nation called The [[Organisation of Free Cities (OFC)]].


### NPCs From Ehobel
```dataview
TABLE town as "Home Town", Status as "Status"
FROM #NPC
WHERE Nation = "Ehobel" 

```
### Static Map
![[Ehobel_Map.jpg]]

### Interactive Map (Unavailable Online)
```leaflet  
id: Ehobel_iMap ### Must be unique with no spaces  
image: [[Ehobel_Map.jpg]] ### Link to the map image file  
bounds: [[0,0], [4096, 3232]] ### Size of the map in px Width_x, Height_y  
height: 620px ### Size of the leaflet embed in px on your screen  
width: 70% ### Size of the leaflet embed in your note  
lat: 2048 ### To center the map, make this half of the map width.  
long: 1616 ### To center the map, make this half of the map height.  
minZoom: -5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -2.7 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.1 ### Adjust how much the zoom changes when you zoom in or out.
```
