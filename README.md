 # Geofence

MoveApps

Github repository: *https://github.com/nilanjanchatterjee/Geofence* 

## Description
The app segregates animal locations within or outside any specific polygon boundary. 

## Documentation
The app segregates animal locations within or outside any specific polygon boundary. A fall back file of protected area in the Y2Y region is provided in the app and users have the flexibility to upload their own. The shapefile uploaded must have a column/attribute table `NAME` which is used to distinguish between different areas. 

### Input data

MoveStack in Movebank format   
Polygon boundary file in shapefile format

### Output data

Move/MoveStack in Movebank format

### Artefacts

`PA_locations.jpeg`: plot showing animal tracks and locations within and outside the protected area    

### Settings 
The app requires a polygon boundary in shapefile format. A fall back file of protected area in the Y2Y area is provided and users can upload their own polygon shapefile.

### Null or error handling

If no point has overlap with the protected area an **logger** message is given in the app-log. Please check the app-log if you do not see an output artefact plot. 
