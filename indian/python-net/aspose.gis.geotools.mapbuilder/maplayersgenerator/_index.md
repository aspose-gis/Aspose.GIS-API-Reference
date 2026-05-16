---
title: "MapLayersGenerator क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | MapLayersGenerator क्लास का नया इंस्टेंस आरंभ करता है |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | परतों की सूची प्राप्त करें: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | मानचित्र उत्पन्न करें। |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

MapLayersGenerator क्लास का नया इंस्टेंस आरंभ करता है

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

परतों की सूची प्राप्त करें: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | मानचित्र जनरेटर विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | उत्पन्न ज्यामिति वाली परतों की सूची। |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

मानचित्र उत्पन्न करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | मानचित्र जनरेटर विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | पूरा किया गया मानचित्र। |


