---
title: "BoundingRectangle Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.gis.common/boundingrectangle/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.BoundingRectangle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BoundingRectangle()](#BoundingRectangle__1) | Initialisiert eine neue Instanz der BoundingRectangle-Klasse |
| [BoundingRectangle(x_min, y_min, x_max, y_max)](#BoundingRectangle_x_min_y_min_x_max_y_max_2) | Initialisiert eine neue Instanz der BoundingRectangle-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Fläche | double | r |  |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| has_values | bool | r |  |
| Höhe | double | r |  |
| max_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| min_coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| width | double | r |  |
| x_max | double | r/w |  |
| x_min | double | r/w |  |
| y_max | double | r/w |  |
| y_min | double | r/w |  |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
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

Initialisiert eine neue Instanz der BoundingRectangle-Klasse

### Constructor: BoundingRectangle(x_min, y_min, x_max, y_max) {#BoundingRectangle_x_min_y_min_x_max_y_max_2}


```
 BoundingRectangle(x_min, y_min, x_max, y_max) 
```

Initialisiert eine neue Instanz der BoundingRectangle-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x_min | double |  |
| y_min | double |  |
| x_max | double |  |
| y_max | double |  |

### Method: clone() {#clone__1}


```
 clone() 
```

Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: contains(c) {#contains_c_2}


```
 contains(c) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: contains(other) {#contains_other_3}


```
 contains(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: contains_x(x) {#contains_x_x_5}


```
 contains_x(x) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: contains_y(y) {#contains_y_y_6}


```
 contains_y(y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| y | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: distance(coordinate) {#distance_coordinate_7}


```
 distance(coordinate) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: distance(other) {#distance_other_8}


```
 distance(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: distance(x, y) {#distance_x_y_9}


```
 distance(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: intersection(other) {#intersection_other_10}


```
 intersection(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |


### Method: intersects(other) {#intersects_other_11}


```
 intersects(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: squared_distance(c) {#squared_distance_c_12}


```
 squared_distance(c) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| c | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: squared_distance(other) {#squared_distance_other_13}


```
 squared_distance(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: squared_distance(x, y) {#squared_distance_x_y_14}


```
 squared_distance(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


