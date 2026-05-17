---
title: "Klassen WayLayerGenerator"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Skapa en instans av [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Lägg till block i cellen |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Lägg till väg i cellen |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Hitta vägen från startpunkt till mål |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Skapa en instans av [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | alternativen för generatorn. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Lägg till block i cellen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | x för blocket |
| y | int | y för blocket |
| size_x | int | sizeX för blocket |
| size_y | int | sizeY för blocket |
| hastighet | double | hastigheten för blocket |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Lägg till väg i cellen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | startpunkten. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | slutpunkten. |
| hastighet | double | hastigheten. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Hitta vägen från startpunkt till mål

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | startpunkten |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | mål Point |
| radie | double | radien att leta efter |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Den hittade vägen. |


