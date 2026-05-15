---
title: "فئة MapLayersGenerator"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | يُنشئ مثلاً جديدًا لفئة MapLayersGenerator |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | احصل على قائمة الطبقات: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | إنشاء الخريطة. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

يُنشئ مثلاً جديدًا لفئة MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

احصل على قائمة الطبقات: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | خيارات مولد الخريطة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | قائمة الطبقات مع الهندسة المولدة. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

إنشاء الخريطة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | خيارات مولد الخريطة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | الخريطة المكتملة. |


