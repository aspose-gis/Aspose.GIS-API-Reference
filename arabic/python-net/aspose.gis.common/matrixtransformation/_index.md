---
title: "MatrixTransformation فئة"
type: docs
weight: 670
url: /ar/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | يُنشئ مثيلًا جديدًا من فئة MatrixTransformation |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| قابل_للتحرير | bool | r |  |
| خالي | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| دوران | double | r |  |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
| lock_from_editing() |  |
| rotate(cos, sin) |  |
| rotate(درجات) |  |
| scale(zoom_x, zoom_y) |  |
| [transform(coordinate)](#transform_coordinate_2) |    |
| [transform(x, y)](#transform_x_y_3) |    |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: MatrixTransformation() {#MatrixTransformation__1}


```
 MatrixTransformation() 
```

يُنشئ مثيلًا جديدًا من فئة MatrixTransformation

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


