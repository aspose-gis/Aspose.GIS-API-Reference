---
title: "MapLayersGenerator Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Инициализирует новый экземпляр класса MapLayersGenerator |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Получить список слоёв: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Создать карту. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Инициализирует новый экземпляр класса MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Получить список слоёв: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Параметры генератора карты. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Список слоёв с сгенерированной геометрией. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Создать карту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Параметры генератора карты. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Готовая карта. |


