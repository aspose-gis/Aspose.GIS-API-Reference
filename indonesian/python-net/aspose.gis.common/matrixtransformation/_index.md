---
title: "Kelas MatrixTransformation"
type: docs
weight: 670
url: /id/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | Menginisialisasi sebuah instansi baru dari kelas MatrixTransformation |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| rotasi | double | r |  |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Membuat objek baru yang merupakan salinan dari instance saat ini. |
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

Menginisialisasi sebuah instansi baru dari kelas MatrixTransformation

### Method: clone() {#clone__1}


```
 clone() 
```

Membuat objek baru yang merupakan salinan dari instance saat ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


