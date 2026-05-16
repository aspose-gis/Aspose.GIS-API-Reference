---
title: "Classe WayLayerGenerator"
type: docs
weight: 10
url: /it/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Crea un'istanza di [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Aggiungi blocco alla cella |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Aggiungi strada alla cella |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Trova il percorso dal punto di partenza all'obiettivo |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Crea un'istanza di [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | le opzioni del generatore. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Aggiungi blocco alla cella

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | l'x del blocco |
| y | int | l'y del blocco |
| size_x | int | la sizeX del blocco |
| size_y | int | la sizeY del blocco |
| velocità | double | la velocità del blocco |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Aggiungi strada alla cella

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | il punto di partenza. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | il punto finale. |
| velocità | double | la velocità. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Trova il percorso dal punto di partenza all'obiettivo

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | il Punto di partenza |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | il Punto obiettivo |
| raggio | double | il raggio da cercare |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Il Percorso Trovato. |


