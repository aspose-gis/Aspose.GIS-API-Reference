---
title: "MapLayersGenerator Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | MapLayersGenerator sınıfının yeni bir örneğini başlatır |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Katmanların listesini al: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Haritayı üret. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

MapLayersGenerator sınıfının yeni bir örneğini başlatır

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Katmanların listesini al: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Harita oluşturucu seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Oluşturulan geometriye sahip katmanların listesi. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Haritayı üret.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Harita oluşturucu seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Tamamlanmış harita. |


