---
title: "Класс BoundingRectangle"
type: docs
weight: 100
url: /ru/python-net/aspose.gis.common/boundingrectangle/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.BoundingRectangle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [BoundingRectangle()](#BoundingRectangle__1) | Создаёт новый экземпляр класса BoundingRectangle |
| [BoundingRectangle(x_min, y_min, x_max, y_max)](#BoundingRectangle_x_min_y_min_x_max_y_max_2) | Создаёт новый экземпляр класса BoundingRectangle |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| площадь | double | r |  |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| has_values | bool | r |  |
| высота | double | r |  |
| max_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| min_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| width | double | r |  |
| x_max | double | r/w |  |
| x_min | double | r/w |  |
| y_max | double | r/w |  |
| y_min | double | r/w |  |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создает новый объект, являющийся копией текущего экземпляра. |
| [contains(c)](#contains_c_2) |    |
| [contains(other)](#contains_other_3) |    |
| [contains(x, y)](#contains_x_y_4) |    |
| [contains_x(x)](#contains_x_x_5) |    |
| [contains_y(y)](#contains_y_y_6) |    |
| [distance(coordinate)](#distance_coordinate_7) |    |
| [distance(other)](#distance_other_8) |    |
| [distance(x, y)](#distance_x_y_9) |    |
| grow(c) |  |
| grow(other) |  |
| grow(x, y) |  |
| grow_x(x) |  |
| grow_y(y) |  |
| [intersection(other)](#intersection_other_10) |    |
| [intersects(other)](#intersects_other_11) |    |
| [squared_distance(c)](#squared_distance_c_12) |    |
| [squared_distance(other)](#squared_distance_other_13) |    |
| [squared_distance(x, y)](#squared_distance_x_y_14) |    |


### Constructor: BoundingRectangle() {#BoundingRectangle__1}


```
 BoundingRectangle() 
```

Создаёт новый экземпляр класса BoundingRectangle

### Constructor: BoundingRectangle(x_min, y_min, x_max, y_max) {#BoundingRectangle_x_min_y_min_x_max_y_max_2}


```
 BoundingRectangle(x_min, y_min, x_max, y_max) 
```

Создаёт новый экземпляр класса BoundingRectangle

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x_min | double |  |
| y_min | double |  |
| x_max | double |  |
| y_max | double |  |

### Method: clone() {#clone__1}


```
 clone() 
```

Создает новый объект, являющийся копией текущего экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: contains(c) {#contains_c_2}


```
 contains(c) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: contains(other) {#contains_other_3}


```
 contains(other) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: contains_x(x) {#contains_x_x_5}


```
 contains_x(x) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: contains_y(y) {#contains_y_y_6}


```
 contains_y(y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| y | double |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: distance(coordinate) {#distance_coordinate_7}


```
 distance(coordinate) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: distance(other) {#distance_other_8}


```
 distance(other) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: distance(x, y) {#distance_x_y_9}


```
 distance(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: intersection(other) {#intersection_other_10}


```
 intersection(other) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: intersects(other) {#intersects_other_11}


```
 intersects(other) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: squared_distance(c) {#squared_distance_c_12}


```
 squared_distance(c) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: squared_distance(other) {#squared_distance_other_13}


```
 squared_distance(other) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: squared_distance(x, y) {#squared_distance_x_y_14}


```
 squared_distance(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


