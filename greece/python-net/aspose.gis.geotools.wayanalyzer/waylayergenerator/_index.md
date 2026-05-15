---
title: "Κλάση WayLayerGenerator"
type: docs
weight: 10
url: /el/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Δημιουργήστε ένα στιγμιότυπο του [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Προσθέστε μπλοκ στο κελί |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Προσθέστε δρόμο στο κελί |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Βρείτε τη διαδρομή από το σημείο εκκίνησης μέχρι τον προορισμό |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Δημιουργήστε ένα στιγμιότυπο του [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | οι επιλογές του δημιουργού. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Προσθέστε μπλοκ στο κελί

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | το x του μπλοκ |
| y | int | το y του μπλοκ |
| size_x | int | το sizeX του μπλοκ |
| size_y | int | το sizeY του μπλοκ |
| velocity | double | η ταχύτητα του μπλοκ |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Προσθέστε δρόμο στο κελί

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | το αρχικό σημείο. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | το τελικό σημείο. |
| velocity | double | η ταχύτητα. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Βρείτε τη διαδρομή από το σημείο εκκίνησης μέχρι τον προορισμό

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | το αρχικό Σημείο |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | το σημείο στόχου |
| radius | double | η ακτίνα για αναζήτηση |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Η Βρεθείσα Διαδρομή. |


