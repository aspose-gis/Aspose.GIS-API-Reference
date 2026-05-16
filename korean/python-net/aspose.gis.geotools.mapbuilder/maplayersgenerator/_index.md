---
title: "MapLayersGenerator 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | MapLayersGenerator 클래스의 새 인스턴스를 초기화합니다 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | 레이어 목록 가져오기: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | 지도를 생성합니다. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

MapLayersGenerator 클래스의 새 인스턴스를 초기화합니다

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

레이어 목록 가져오기: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | 지도 생성기 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | 생성된 기하학을 가진 레이어 목록. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

지도를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | 지도 생성기 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | 완성된 지도. |


