---
title: "Класс Tetragon"
type: docs
weight: 190
url: /ru/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | Инициализирует новый экземпляр класса Tetragon |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | Инициализирует новый экземпляр класса Tetragon |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | Инициализирует новый экземпляр класса Tetragon |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| угол | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

Инициализирует новый экземпляр класса Tetragon

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

Инициализирует новый экземпляр класса Tetragon

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| угол | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

Инициализирует новый экземпляр класса Tetragon

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| высота | double |  |
| угол | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


