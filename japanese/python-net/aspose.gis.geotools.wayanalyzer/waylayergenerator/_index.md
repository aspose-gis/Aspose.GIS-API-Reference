---
title: "WayLayerGenerator クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) のインスタンスを作成します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | セルにブロックを追加します |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | セルに道路を追加します |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | 開始点から目標までの道を見つけます |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

[WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) のインスタンスを作成します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | ジェネレータのオプションです。 |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

セルにブロックを追加します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | int | ブロックの x |
| y | int | ブロックの y |
| size_x | int | ブロックの sizeX |
| size_y | int | ブロックの sizeY |
| 速度 | double | ブロックの速度 |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

セルに道路を追加します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 開始点。 |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 終了点。 |
| 速度 | double | 速度。 |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

開始点から目標までの道を見つけます

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 開始点 |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | ゴールポイント |
| 半径 | double | 検索する半径 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | 見つかった経路。 |


