---
{"dg-publish":true,"permalink":"/homepage/home/","tags":["gardenEntry"]}
---


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`

[[Xaode Hexmap.png]]

```leaflet  
id: Xaode ### Must be unique with no spaces  
image: [[Xaode Hexmap.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [3000, 4000]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 700px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 600 ### To center the map, make this half of the map height.  
long: 950 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -0.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```


</div></div>

# Menu
[[Heroes/- Lista de Heroes -\|- Lista de Heroes -]]
[[NPCs/- Lista de NPCs -\|- Lista de NPCs -]]
[[Stash/- Inventario de Gremio -\|- Inventario de Gremio -]]
[[Kit Equiment/- Lista de Kit Categories -\|- Lista de Kit Categories -]]


