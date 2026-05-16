---
title: "WayLayerGenerator 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)의 인스턴스를 생성합니다 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | 셀에 블록을 추가합니다 |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | 셀에 도로를 추가합니다 |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | 시작 지점에서 목표까지의 경로를 찾습니다 |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

[WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)의 인스턴스를 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | 생성기의 옵션. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

셀에 블록을 추가합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | int | 블록의 x |
| y | int | 블록의 y |
| size_x | int | 블록의 sizeX |
| size_y | int | 블록의 sizeY |
| 속도 | double | 블록의 속도 |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

셀에 도로를 추가합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 시작 지점. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 끝 지점. |
| 속도 | double | 속도. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

시작 지점에서 목표까지의 경로를 찾습니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 시작 지점 |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | 목표 지점 |
| 반경 | double | 검색할 반경 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | 찾은 경로. |


