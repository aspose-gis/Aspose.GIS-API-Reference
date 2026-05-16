---
title: "Kelas MapLayersGenerator"
type: docs
weight: 20
url: /id/python-net/aspose.gis.geotools.mapbuilder/maplayersgenerator/
---

**Summary:** Map layers generator

**Module:** [aspose.gis.geotools.mapbuilder](/psd/python-net/aspose.gis.geotools.mapbuilder/)

**Full Name:** aspose.gis.geotools.mapbuilder.MapLayersGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MapLayersGenerator()](#MapLayersGenerator__1) | Menginisialisasi instance baru dari kelas MapLayersGenerator |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_list_of_layers(options)](#get_list_of_layers_options_1) | Dapatkan daftar lapisan: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer. |
| [produce_map(options)](#produce_map_options_2) | Hasilkan peta. |


### Constructor: MapLayersGenerator() {#MapLayersGenerator__1}


```
 MapLayersGenerator() 
```

Menginisialisasi instance baru dari kelas MapLayersGenerator

### Method: get_list_of_layers(options)  [static] {#get_list_of_layers_options_1}


```
 get_list_of_layers(options) 
```

Dapatkan daftar lapisan: roadLayer, buildingLayer, parkLayer, parkRoadLayer, industrialLayer.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opsi generator peta. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.List<VectorLayer> | Daftar lapisan dengan geometri yang dihasilkan. |


### Method: produce_map(options)  [static] {#produce_map_options_2}


```
 produce_map(options) 
```

Hasilkan peta.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [MapGeneratorOptions](/psd/python-net/aspose.gis.geotools.mapbuilder/mapgeneratoroptions) | Opsi generator peta. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Map](/psd/python-net/aspose.gis.rendering/map/) | Peta yang selesai. |


