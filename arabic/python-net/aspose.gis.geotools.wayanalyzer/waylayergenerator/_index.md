---
title: "فئة WayLayerGenerator"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | إنشاء مثيل من [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | إضافة كتلة إلى الخلية |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | إضافة طريق إلى الخلية |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | العثور على الطريق من نقطة البداية إلى الهدف |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

إنشاء مثيل من [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | خيارات المولد. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

إضافة كتلة إلى الخلية

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | int | قيمة x للكتلة |
| y | int | قيمة y للكتلة |
| size_x | int | حجم sizeX للكتلة |
| size_y | int | حجم sizeY للكتلة |
| السرعة | double | سرعة الكتلة |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

إضافة طريق إلى الخلية

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | نقطة البداية. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | نقطة النهاية. |
| السرعة | double | السرعة. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

العثور على الطريق من نقطة البداية إلى الهدف

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | نقطة البداية |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | نقطة الهدف |
| نصف القطر | double | نصف القطر للبحث عنه |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | الطريق المكتشف. |


