---
title: "Класс GeometryOperations"
type: docs
weight: 40
url: /ru/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Построить диаграмму центральной линии для полигона |
| [build_centerline(sites)](#build_centerline_sites_2) | Построить диаграмму центральной линии для набора точек (узлов) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Замыкает геометрические сегменты в кольцах при необходимости. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Создать средние точки, добавив новую точку посередине к каждому сегменту. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Удалить точки, которые находятся слишком близко друг к другу. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Извлечь коллекцию геометрий из слоя |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Получить длину центральной линии |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Получить длину центральной линии |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Построить диаграмму "Вороного" для набора точек (узлов) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Упорядочить коллекцию геометрий по типу в четыре коллекции (точка, линия, полигон и другие типы) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Удалить точки, лежащие на одном сегменте. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Построить диаграмму центральной линии для полигона

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Полигон для диаграммы центральной линии |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Коллекция ребер центральной линии |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Построить диаграмму центральной линии для набора точек (узлов)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| узлы | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Коллекция точек (узлов) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Коллекция ребер центральной линии |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Замыкает геометрические сегменты в кольцах при необходимости.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для замыкания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия после замыкания. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Создать средние точки, добавив новую точку посередине к каждому сегменту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для обработки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия после обработки. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Удалить точки, которые находятся слишком близко друг к другу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для удаления ближайших точек. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Параметры для удаления ближайших точек. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия после удаления ближайшей точки. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Извлечь коллекцию геометрий из слоя

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Входной слой |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Коллекция содержит все геометрии входного слоя |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Получить длину центральной линии

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Полигон для диаграммы центральной линии |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Длина ребер центральной линии |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Получить длину центральной линии

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| узлы | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Коллекция точек (узлов) |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Длина ребер центральной линии |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Построить диаграмму "Вороного" для набора точек (узлов)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| узлы | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Коллекция точек (узлов) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Коллекция ребер диаграммы Вороного |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Упорядочить коллекцию геометрий по типу в четыре коллекции (точка, линия, полигон и другие типы)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Коллекция геометрий для порядка |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Коллекция содержит четыре подколлекции (точка, линия, полигон и другой тип) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Удалить точки, лежащие на одном сегменте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для удаления лишней точки |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Параметры для удаления лишней точки |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия после удаления лишней точки |


