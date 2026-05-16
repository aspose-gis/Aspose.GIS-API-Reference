---
title: "MapLayersGenerator クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | MapLayersGenerator クラスの新しいインスタンスを初期化します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | レイヤーのリストを取得します: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | マップを生成します。 |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

MapLayersGenerator クラスの新しいインスタンスを初期化します

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

レイヤーのリストを取得します: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | マップジェネレータのオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | 生成されたジオメトリを持つレイヤーのリストです。 |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

マップを生成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | マップジェネレータのオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | 完成したマップです。 |


