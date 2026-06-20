---
title: "WayLayerGenerator 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | 创建一个实例 [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | 向单元格添加块 |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | 向单元格添加道路 |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | 寻找从起点到目标的路径 |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

创建一个实例 [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | 生成器的选项。 |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

向单元格添加块

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | 整数 | 块的 x 坐标 |
| y | 整数 | 块的 y 坐标 |
| size_x | 整数 | 块的 sizeX |
| size_y | 整数 | 块的 sizeY |
| 速度 | double | 块的速度 |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

向单元格添加道路

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 起始点。 |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 结束点。 |
| 速度 | double | 速度。 |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

寻找从起点到目标的路径

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 起始点 |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 目标点 |
| 半径 | double | 要查找的半径 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | 已找到路径。 |


