---
title: "MatrixTransformation Klasse"
type: docs
weight: 670
url: /de/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | Initialisiert eine neue Instanz der MatrixTransformation Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| Drehung | double | r |  |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
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

Initialisiert eine neue Instanz der MatrixTransformation Klasse

### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


