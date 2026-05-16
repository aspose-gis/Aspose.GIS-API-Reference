---
title: "Classe MapLayersGenerator"
type: docs
weight: 20
url: /it/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Inizializza una nuova istanza della classe MapLayersGenerator |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Ottieni l'elenco dei layer: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Genera la mappa. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Inizializza una nuova istanza della classe MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Ottieni l'elenco dei layer: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opzioni del generatore di mappe. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | L'elenco dei layer con geometria generata. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Genera la mappa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opzioni del generatore di mappe. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | La mappa completata. |


