---
title: "MapLayersGenerator Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Initialiseert een nieuw exemplaar van de MapLayersGenerator klasse |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Haal lijst met lagen op: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Genereer kaart. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Initialiseert een nieuw exemplaar van de MapLayersGenerator klasse

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Haal lijst met lagen op: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Kaartgeneratoropties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | De lijst met lagen met gegenereerde geometrie. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Genereer kaart.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Kaartgeneratoropties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | De voltooide kaart. |


