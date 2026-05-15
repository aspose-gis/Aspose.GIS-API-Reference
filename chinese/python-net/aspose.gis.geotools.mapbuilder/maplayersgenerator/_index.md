---
title: "MapLayersGenerator 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | 初始化 MapLayersGenerator 类的新实例 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | 获取图层列表：roadLayer、buildingLayer、parkLayer、parkRoadLayer、industrialLayer。 |
| [produce_map(options)](#produce_map_options_2) | 生成地图。 |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

初始化 MapLayersGenerator 类的新实例

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

获取图层列表：roadLayer、buildingLayer、parkLayer、parkRoadLayer、industrialLayer。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | 地图生成器选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | 包含生成几何的图层列表。 |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

生成地图。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | 地图生成器选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | 完成的地图。 |


