---
title: "WayLayerGenerator Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Instanz von [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) erstellen |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Block zur Zelle hinzufügen |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Straße zur Zelle hinzufügen |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Finde den Weg vom Startpunkt zum Ziel |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Instanz von [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) erstellen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | die Optionen des Generators. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Block zur Zelle hinzufügen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | das x des Blocks |
| y | int | das y des Blocks |
| size_x | int | die sizeX des Blocks |
| size_y | int | die sizeY des Blocks |
| Geschwindigkeit | double | die Geschwindigkeit des Blocks |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Straße zur Zelle hinzufügen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | der Startpunkt. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | der Endpunkt. |
| Geschwindigkeit | double | die Geschwindigkeit. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Finde den Weg vom Startpunkt zum Ziel

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | der Startpunkt |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | der Zielpunkt |
| Radius | double | der zu suchende Radius |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Der gefundene Weg. |


