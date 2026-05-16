---
title: "WayLayerGenerator क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | एक इंस्टेंस बनाएं [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | सेल में ब्लॉक जोड़ें |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | सेल में सड़क जोड़ें |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | शुरुआती बिंदु से लक्ष्य तक का रास्ता खोजें |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

एक इंस्टेंस बनाएं [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | जनरेटर के विकल्प। |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

सेल में ब्लॉक जोड़ें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | इंट | ब्लॉक का x |
| y | इंट | ब्लॉक का y |
| size_x | इंट | ब्लॉक का sizeX |
| size_y | इंट | ब्लॉक का sizeY |
| वेग | double | ब्लॉक का वेग |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

सेल में सड़क जोड़ें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | शुरूआती बिंदु. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | अंत बिंदु. |
| वेग | double | वेग। |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

शुरुआती बिंदु से लक्ष्य तक का रास्ता खोजें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | शुरूआती बिंदु |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | लक्ष्य बिंदु |
| त्रिज्या | double | खोजने के लिए त्रिज्या |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | पाया गया मार्ग। |


