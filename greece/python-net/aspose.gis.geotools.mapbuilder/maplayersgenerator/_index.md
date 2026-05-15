---
title: "Κλάση MapLayersGenerator"
type: docs
weight: 20
url: /el/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MapLayersGenerator |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Λάβετε τη λίστα των στρωμάτων: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Δημιουργήστε χάρτη. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Λάβετε τη λίστα των στρωμάτων: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Επιλογές δημιουργού χάρτη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Η λίστα των στρωμάτων με τη δημιουργημένη γεωμετρία. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Δημιουργήστε χάρτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Επιλογές δημιουργού χάρτη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Ο ολοκληρωμένος χάρτης. |


