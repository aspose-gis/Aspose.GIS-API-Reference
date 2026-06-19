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
| **Name** | **Description** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | يُنشئ مثيلاً جديدًا من فئة MatrixTransformation |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dx | double | قراءة/كتابة |  |
| dy | double | قراءة/كتابة |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | قراءة/كتابة |  |
| m12 | double | قراءة/كتابة |  |
| m21 | double | قراءة/كتابة |  |
| m22 | double | قراءة/كتابة |  |
| دوران | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
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

يُنشئ مثيلاً جديدًا من فئة MatrixTransformation

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns**

| نوع | وصف |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| نوع | وصف |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| نوع | وصف |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


