---
title: "Clase MapLayersGenerator"
type: docs
weight: 20
url: /es/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Inicializa una nueva instancia de la clase MapLayersGenerator |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Obtener lista de capas: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Generar mapa. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Inicializa una nueva instancia de la clase MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Obtener lista de capas: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opciones del generador de mapas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | La lista de capas con geometría generada. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Generar mapa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opciones del generador de mapas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | El mapa completado. |


