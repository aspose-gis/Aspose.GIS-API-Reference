---
title: "Klassen MapLayersGenerator"
type: docs
weight: 20
url: /sv/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Initierar en ny instans av klassen MapLayersGenerator |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Hämta lista över lager: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Skapa karta. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Initierar en ny instans av klassen MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Hämta lista över lager: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Alternativ för kartgeneratorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Listan över lager med genererad geometri. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Skapa karta.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Alternativ för kartgeneratorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Den färdiga kartan. |


