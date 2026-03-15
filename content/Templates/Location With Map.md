---
publish: true
created: 2026-03-15T01:10:08.874+01:00
modified: 2026-03-15T01:08:44.111+01:00
cssclasses: ""
---

## Map
```zoommap
imageBases:
  - path: Campaigns/Under The Ash/Locations/img/<%tp.file.title%> Map.png
    name: <%tp.file.title%>
markers: Campaigns/Under The Ash/Locations/markers/<%tp.file.title%>.markers.json
markerLayers:
  - Default
minZoom: 0.66
maxZoom: 8
wrap: false
responsive: false
width: 100%
height: 532px
resizable: false
resizeHandle: native
render: canvas
id: <%tp.file.title%>-map
```
## Description
<% tp.file.cursor(1) %>
<%await tp.file.move(`Campaigns/Under The Ash/Locations/${tp.file.title}`)%>