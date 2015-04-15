# OpenStreetMap - ArcGIS

### Introduction

Provides a means to style OpenStreetMap data imported into ArcGIS using the [OpenStreetMap Editor for ArcGIS](http://www.esri.com/software/arcgis/extensions/openstreetmap).

The styles are based on the humanitarian theme from http://openstreetmap.org/. The original style information is from [HDM-CartoCSS](https://github.com/hotosm/HDM-CartoCSS) and is based on [CartoCSS](https://github.com/mapbox/carto).

In addition to the styles a work flow will be generated that will walk through a complete process of:
1. Load
2. Extract additional tags
3. Build network dataset
4. Update template mxd with loaded data
5. Publish to ArcGIS server
6. Generate tile cache

In addition address locators will be built and published along with publishing the network dataset. The entire process will be semi automated using geoprocessing scripts.


### Description

The style file contains symbols for 4 distinct scale levels. Each level groups 1 or more of the zoom levels from OpenStreetMap. The following images are examples of how the layers look.
###### Level 1
![Image of Level 1](https://github.com/daveb1034/OpenStreetMap-ArcGIS/blob/master/images/Zoom1.PNG)

###### Level 2
![Image of Level 2](https://github.com/daveb1034/OpenStreetMap-ArcGIS/blob/master/images/Zoom2.PNG)

###### Level 3
![Image of Level 3](https://github.com/daveb1034/OpenStreetMap-ArcGIS/blob/master/images/Zoom3.PNG)

###### Level 4
![Image of Level 4](https://github.com/daveb1034/OpenStreetMap-ArcGIS/blob/master/images/Zoom4.PNG)

These styles are a work in progress and layer files will produced for each zoom level in the ArcGIS online tiling scheme. Each level will show the required features based on the HDM-CartoCSS style and additional features not included.


### License

- stylesheet is licenced under CCO
- Nori icons are licenced under CCO
- Maki icons are © [MapBox](https://www.mapbox.com/maki/)

