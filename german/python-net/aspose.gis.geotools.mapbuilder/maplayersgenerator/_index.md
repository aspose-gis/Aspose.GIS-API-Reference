---
title: "MapLayersGenerator Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Initialisiert eine neue Instanz der MapLayersGenerator Klasse |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Liste der Ebenen abrufen: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Karte erzeugen. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Initialisiert eine neue Instanz der MapLayersGenerator Klasse

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Liste der Ebenen abrufen: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Karten-Generator-Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Die Liste der Ebenen mit generierter Geometrie. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Karte erzeugen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Karten-Generator-Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Die fertige Karte. |


