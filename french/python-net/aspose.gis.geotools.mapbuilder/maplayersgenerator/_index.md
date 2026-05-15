---
title: "Classe MapLayersGenerator"
type: docs
weight: 20
url: /fr/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Initialise une nouvelle instance de la classe MapLayersGenerator |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Obtenir la liste des calques: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Produire la carte. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Initialise une nouvelle instance de la classe MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Obtenir la liste des calques: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Options du générateur de carte. |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | La liste des calques avec la géométrie générée. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Produire la carte.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Options du générateur de carte. |

**Returns**

| Type | Description |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | La carte terminée. |


