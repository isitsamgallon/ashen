---
dg-publish: true
city type: 
Nation:
  - The Dawn Empire
icon: place
aliases:
  - The Shattered Dawn
tags:
  - Discovered
---
> [!infobox]
> 
> # `=this.file.name`
> ![[The_Dawn_Empire_Map.jpg]]
> ###### Basic Information
> 
>  Type | Info |
> :----: | --- |
>  Primary Race | [[Human]] |
>  Founder | [[Redmund Verix †]] |
>  Current Leader | [[Galen Verix ‡]] |
>  ##### Notable NPCs
>  ```dataview
>  list 
>  from #Important
>  where Nation = "The Dawn Empire" 
>  ```
>  
>  ##### Cities & Towns 
>  ```dataview
>  table tags as "Discovery Status"
>  From "Locations"
>  WHERE contains( Nation, this.file.name)
>  ```

### Overview
The home nation of the Humans in [[The Amber Realms]] and led by The Emperor, [[Galen Verix ‡]]. Galen is from a long line of Verixs who have ruled the nation for over 500 years after liberating it from the Dwarves in what came to be known as [[The Cleansing]] led by his ancestor [[Redmund Verix †]]. The Dawn was one of the magic factions that made up [[The Coalition]] during [[The Sundering]]. During this period The Dawn had a very good relationship with [[Ehobel]] after many wars. However, sometime after the Sundering, the nations began to despise each other again, causing [[4th Dawn vs Ehobel War]] which sprouted the offshoot nation called The [[Organisation of Free Cities (OFC)]].



### NPCs From The Dawn
```dataview
TABLE town as "Home Town", Status as "Status"
FROM #NPC
WHERE Nation = "The Dawn Empire" 

```

### Static Map
![[The_Dawn_Empire_Map.jpg]]

### Interactive Map (Unavailable Online)
```leaflet  
id: TheDawnEmpire_iMap ### Must be unique with no spaces  
image: [[The_Dawn_Empire_Map.jpg]] ### Link to the map image file  
bounds: [[0,0], [3008, 4096]] ### Size of the map in px Width_x, Height_y  
height: 450px ### Size of the leaflet embed in px on your screen  
width: 90% ### Size of the leaflet embed in your note  
lat: 1504 ### To center the map, make this half of the map width.  
long: 2048 ### To center the map, make this half of the map height.  
minZoom: -5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -2.7 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.1 ### Adjust how much the zoom changes when you zoom in or out.
```
