---
title: "Tetragon Κλάση"
type: docs
weight: 190
url: /el/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| γωνία | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| γωνία | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Tetragon

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| ύψος | double |  |
| γωνία | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


