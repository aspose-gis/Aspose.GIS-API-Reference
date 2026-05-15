---
title: "MatrixTransformation Κλάση"
type: docs
weight: 670
url: /el/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης MatrixTransformation |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| περιστροφή | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Δημιουργεί ένα νέο αντικείμενο που είναι αντίγραφο της τρέχουσας εμφάνισης. |
| lock_from_editing() |  |
| rotate(cos, sin) |  |
| rotate(degrees) |  |
| scale(zoom_x, zoom_y) |  |
| [transform(coordinate)](#transform_coordinate_2) |    |
| [transform(x, y)](#transform_x_y_3) |    |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: MatrixTransformation() {#MatrixTransformation__1}


```
 MatrixTransformation() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης MatrixTransformation

### Method: clone() {#clone__1}


```
 clone() 
```

Δημιουργεί ένα νέο αντικείμενο που είναι αντίγραφο της τρέχουσας εμφάνισης.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


