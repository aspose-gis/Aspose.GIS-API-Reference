---
title: "WayLayerGenerator Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Создать экземпляр [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Добавить блок в ячейку |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Добавить дорогу в ячейку |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Найти путь от начальной точки к цели |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Создать экземпляр [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | параметры генератора. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Добавить блок в ячейку

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | x блока |
| y | int | y блока |
| size_x | int | sizeX блока |
| size_y | int | размер sizeY блока |
| скорость | double | скорость блока |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Добавить дорогу в ячейку

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | начальная точка. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | конечная точка. |
| скорость | double | скорость. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Найти путь от начальной точки к цели

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | начальная точка |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | целевая точка |
| радиус | double | радиус для поиска |

**Returns**

| Тип | Описание |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Найденный путь. |


