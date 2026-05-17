---
title: "WayLayerGenerator Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Bir [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) örneği oluştur |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Bloğu hücreye ekle |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Yolu hücreye ekle |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Başlangıç noktasından hedefe yolu bul |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Bir [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) örneği oluştur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | oluşturucunun seçenekleri. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Bloğu hücreye ekle

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | bloğun x'i |
| y | int | bloğun y'si |
| size_x | int | bloğun sizeX'i |
| size_y | int | bloğun sizeY'si |
| hız | double | bloğun hızı |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Yolu hücreye ekle

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | başlangıç noktası. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | bitiş noktası. |
| hız | double | hız. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Başlangıç noktasından hedefe yolu bul

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | başlangıç Noktası |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | hedef Noktası |
| yarıçap | double | aramak için yarıçap |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Bulunan Yol. |


