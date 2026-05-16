---
title: "MatrixTransformation Classe"
type: docs
weight: 670
url: /it/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | Inizializza una nuova istanza della classe MatrixTransformation |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| rotazione | double | r |  |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Crea un nuovo oggetto che è una copia dell'istanza corrente. |
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

Inizializza una nuova istanza della classe MatrixTransformation

### Method: clone() {#clone__1}


```
 clone() 
```

Crea un nuovo oggetto che è una copia dell'istanza corrente.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


