---
title: "WayLayerGenerator Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Maak een exemplaar van [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Voeg blok toe aan de cel |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Voeg weg toe aan de cel |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Vind de weg van startpunt naar doel |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Maak een exemplaar van [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | de opties van de generator. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Voeg blok toe aan de cel

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | de x van blok |
| y | int | de y van blok |
| size_x | int | de sizeX van blok |
| size_y | int | de sizeY van block |
| velocity | double | de velocity van block |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Voeg weg toe aan de cel

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | het startpunt. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | het eindpunt. |
| velocity | double | de velocity. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Vind de weg van startpunt naar doel

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | het start Point |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | de goa lPoint |
| radius | double | de radius om te zoeken |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | De gevonden route. |


