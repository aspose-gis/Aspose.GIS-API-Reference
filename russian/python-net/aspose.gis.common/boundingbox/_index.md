---
title: "Класс BoundingBox"
type: docs
weight: 90
url: /ru/python-net/aspose.gis.common/boundingbox/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.BoundingBox

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [BoundingBox()](#BoundingBox__1) | Инициализирует новый экземпляр класса BoundingBox |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) | r |    |
| has_m | bool | r |  |
| has_z | bool | r |  |
| m_center | double | r |  |
| m_length | double | r |  |
| m_max | double | r/w |  |
| m_min | double | r/w |  |
| x_center | double | r |  |
| x_length | double | r |  |
| x_max | double | r/w |  |
| x_min | double | r/w |  |
| xy_center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| y_center | double | r |  |
| y_length | double | r |  |
| y_max | double | r/w |  |
| y_min | double | r/w |  |
| z_center | double | r |  |
| z_length | double | r |  |
| z_max | double | r/w |  |
| z_min | double | r/w |  |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| clear() |  |
| [clone()](#clone__1) | Создает новый объект, являющийся копией текущего экземпляра. |
| grow(other, has_z, has_m) |  |
| grow_m(m) |  |
| grow_x(x) |  |
| grow_y(y) |  |
| grow_z(z) |  |
| [has_values()](#has_values__2) |    |


### Constructor: BoundingBox() {#BoundingBox__1}


```
 BoundingBox() 
```

Инициализирует новый экземпляр класса BoundingBox

### Method: clone() {#clone__1}


```
 clone() 
```

Создает новый объект, являющийся копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [BoundingBox](/psd/python-net/aspose.gis.common/boundingbox) |  |


### Method: has_values() {#has_values__2}


```
 has_values() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


