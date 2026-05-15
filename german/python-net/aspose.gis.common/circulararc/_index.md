---
title: "CircularArc Klasse"
type: docs
weight: 140
url: /de/python-net/aspose.gis.common/circulararc/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.CircularArc

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CircularArc()](#CircularArc__1) | Initialisiert eine neue Instanz der CircularArc Klasse |
| [CircularArc(start, mid, end)](#CircularArc_start_mid_end_2) | Initialisiert eine neue Instanz der CircularArc Klasse |
| [CircularArc(x0, y0, x1, y1, x2, y2)](#CircularArc_x0_y0_x1_y1_x2_y2_3) | Initialisiert eine neue Instanz der CircularArc Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| circle_center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| is_circle | bool | r |  |
| is_clockwise | bool | r |  |
| is_line | bool | r |  |
| is_minor | bool | r |  |
| is_point | bool | r |  |
| Länge | double | r |  |
| mid | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| Radius | double | r |  |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [equal(other)](#equal_other_1) |    |
| [from_center(center, radius, start_angle_rad, end_angle_rad, clockwise)](#from_center_center_radius_start_angle_rad_end_angle_rad_clockwise_2) |    |
| [from_center(center, start, end, clockwise)](#from_center_center_start_end_clockwise_3) |    |
| [get_coordinate(angle)](#get_coordinate_angle_4) |    |
| get_normalized_angles(start_angle, mid_angle, end_angle) |  |
| grow_bounding_rectangle(brect) |  |
| linearize(result, tolerance, add_endpoints) |  |
| linearize(result, tolerance, add_endpoints, index_of_mid) |  |


### Constructor: CircularArc() {#CircularArc__1}


```
 CircularArc() 
```

Initialisiert eine neue Instanz der CircularArc Klasse

### Constructor: CircularArc(start, mid, end) {#CircularArc_start_mid_end_2}


```
 CircularArc(start, mid, end) 
```

Initialisiert eine neue Instanz der CircularArc Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| mid | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

### Constructor: CircularArc(x0, y0, x1, y1, x2, y2) {#CircularArc_x0_y0_x1_y1_x2_y2_3}


```
 CircularArc(x0, y0, x1, y1, x2, y2) 
```

Initialisiert eine neue Instanz der CircularArc Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x0 | double |  |
| y0 | double |  |
| x1 | double |  |
| y1 | double |  |
| x2 | double |  |
| y2 | double |  |

### Method: equal(other) {#equal_other_1}


```
 equal(other) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: from_center(center, radius, start_angle_rad, end_angle_rad, clockwise)  [static] {#from_center_center_radius_start_angle_rad_end_angle_rad_clockwise_2}


```
 from_center(center, radius, start_angle_rad, end_angle_rad, clockwise) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| Radius | double |  |
| start_angle_rad | double |  |
| end_angle_rad | double |  |
| im Uhrzeigersinn | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |


### Method: from_center(center, start, end, clockwise)  [static] {#from_center_center_start_end_clockwise_3}


```
 from_center(center, start, end, clockwise) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| im Uhrzeigersinn | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |


### Method: get_coordinate(angle) {#get_coordinate_angle_4}


```
 get_coordinate(angle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Winkel | double |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


