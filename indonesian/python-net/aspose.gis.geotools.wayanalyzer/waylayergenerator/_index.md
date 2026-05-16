---
title: "Kelas WayLayerGenerator"
type: docs
weight: 10
url: /id/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Buat instance dari [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Tambahkan blok ke sel |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Tambahkan jalan ke sel |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Temukan jalur dari titik awal ke tujuan |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Buat instance dari [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | opsi generator. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Tambahkan blok ke sel

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | x blok |
| y | int | y blok |
| size_x | int | sizeX blok |
| size_y | int | ukuran sizeY dari blok |
| kecepatan | double | kecepatan blok |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Tambahkan jalan ke sel

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | titik awal. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | titik akhir. |
| kecepatan | double | kecepatan. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Temukan jalur dari titik awal ke tujuan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | titik awal |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | titik tujuan |
| jari-jari | double | jari-jari yang dicari |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Jalur Ditemukan. |


