---
title: "MatrixTransformation klass"
type: docs
weight: 670
url: /sv/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | Initierar en ny instans av MatrixTransformation-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| dx | double | läs/skriv |  |
| dy | double | läs/skriv |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | läs/skriv |  |
| m12 | double | läs/skriv |  |
| m21 | double | läs/skriv |  |
| m22 | double | läs/skriv |  |
| rotation | double | r |  |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| lock_from_editing() |  |
| rotate(cos, sin) |  |
| rotate(grader) |  |
| scale(zoom_x, zoom_y) |  |
| [transform(coordinate)](#transform_coordinate_2) |    |
| [transform(x, y)](#transform_x_y_3) |    |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: MatrixTransformation() {#MatrixTransformation__1}


```
 MatrixTransformation() 
```

Initierar en ny instans av MatrixTransformation-klassen

### Method: clone() {#clone__1}


```
 clone() 
```

Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


