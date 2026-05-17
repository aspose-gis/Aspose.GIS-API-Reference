---
title: "Clase WayLayerGenerator"
type: docs
weight: 10
url: /es/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Crear una instancia de [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Agregar bloque a la celda |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Agregar carretera a la celda |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Encontrar el camino desde el punto de inicio hasta el objetivo |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Crear una instancia de [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | las opciones del generador. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Agregar bloque a la celda

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | la x del bloque |
| y | int | la y del bloque |
| size_x | int | el sizeX del bloque |
| size_y | int | el sizeY del bloque |
| velocidad | double | la velocidad del bloque |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Agregar carretera a la celda

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | el punto de inicio. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | el punto final. |
| velocidad | double | la velocidad. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Encontrar el camino desde el punto de inicio hasta el objetivo

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | el Punto de inicio |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | el Punto de objetivo |
| radio | double | el radio a buscar |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | El Camino Encontrado. |


