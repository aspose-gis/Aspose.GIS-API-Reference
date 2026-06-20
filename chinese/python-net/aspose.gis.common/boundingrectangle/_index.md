---
title: "BoundingRectangle 类"
type: docs
weight: 100
url: /zh/python-net/aspose.gis.common/boundingrectangle/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.BoundingRectangle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BoundingRectangle()](#BoundingRectangle__1) | 初始化 BoundingRectangle 类的新实例 |
| [BoundingRectangle(x_min, y_min, x_max, y_max)](#BoundingRectangle_x_min_y_min_x_max_y_max_2) | 初始化 BoundingRectangle 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 面积 | double | r |  |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| has_values | bool | r |  |
| 高度 | double | r |  |
| max_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| min_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| width | double | r |  |
| x_max | double | r/w |  |
| x_min | double | r/w |  |
| y_max | double | r/w |  |
| y_min | double | r/w |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 创建一个新对象，该对象是当前实例的副本。 |
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

初始化 BoundingRectangle 类的新实例

### Constructor: BoundingRectangle(x_min, y_min, x_max, y_max) {#BoundingRectangle_x_min_y_min_x_max_y_max_2}


```
 BoundingRectangle(x_min, y_min, x_max, y_max) 
```

初始化 BoundingRectangle 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x_min | double |  |
| y_min | double |  |
| x_max | double |  |
| y_max | double |  |

### Method: clone() {#clone__1}


```
 clone() 
```

创建一个新对象，该对象是当前实例的副本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: contains(c) {#contains_c_2}


```
 contains(c) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: contains(other) {#contains_other_3}


```
 contains(other) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: contains_x(x) {#contains_x_x_5}


```
 contains_x(x) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: contains_y(y) {#contains_y_y_6}


```
 contains_y(y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| y | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: distance(coordinate) {#distance_coordinate_7}


```
 distance(coordinate) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: distance(other) {#distance_other_8}


```
 distance(other) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: distance(x, y) {#distance_x_y_9}


```
 distance(x, y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: intersection(other) {#intersection_other_10}


```
 intersection(other) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: intersects(other) {#intersects_other_11}


```
 intersects(other) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: squared_distance(c) {#squared_distance_c_12}


```
 squared_distance(c) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: squared_distance(other) {#squared_distance_other_13}


```
 squared_distance(other) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: squared_distance(x, y) {#squared_distance_x_y_14}


```
 squared_distance(x, y) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


