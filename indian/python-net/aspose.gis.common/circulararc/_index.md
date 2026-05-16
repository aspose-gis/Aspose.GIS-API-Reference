---
title: "CircularArc क्लास"
type: docs
weight: 140
url: /hi/python-net/aspose.gis.common/circulararc/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.CircularArc

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [CircularArc()](#CircularArc__1) | CircularArc क्लास का नया उदाहरण प्रारंभ करता है |
| [CircularArc(start, mid, end)](#CircularArc_start_mid_end_2) | CircularArc क्लास का नया उदाहरण प्रारंभ करता है |
| [CircularArc(x0, y0, x1, y1, x2, y2)](#CircularArc_x0_y0_x1_y1_x2_y2_3) | CircularArc क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| circle_center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| is_circle | bool | r |  |
| is_clockwise | bool | r |  |
| is_line | bool | r |  |
| is_minor | bool | r |  |
| is_point | bool | r |  |
| लंबाई | double | r |  |
| mid | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| त्रिज्या | double | r |  |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
## **Methods**
| **नाम** | **विवरण** |
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

CircularArc क्लास का नया उदाहरण प्रारंभ करता है

### Constructor: CircularArc(start, mid, end) {#CircularArc_start_mid_end_2}


```
 CircularArc(start, mid, end) 
```

CircularArc क्लास का नया उदाहरण प्रारंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| mid | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

### Constructor: CircularArc(x0, y0, x1, y1, x2, y2) {#CircularArc_x0_y0_x1_y1_x2_y2_3}


```
 CircularArc(x0, y0, x1, y1, x2, y2) 
```

CircularArc क्लास का नया उदाहरण प्रारंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
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

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: from_center(center, radius, start_angle_rad, end_angle_rad, clockwise)  [static] {#from_center_center_radius_start_angle_rad_end_angle_rad_clockwise_2}


```
 from_center(center, radius, start_angle_rad, end_angle_rad, clockwise) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| त्रिज्या | double |  |
| start_angle_rad | double |  |
| end_angle_rad | double |  |
| घड़ी की दिशा में | bool |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |


### Method: from_center(center, start, end, clockwise)  [static] {#from_center_center_start_end_clockwise_3}


```
 from_center(center, start, end, clockwise) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| घड़ी की दिशा में | bool |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CircularArc](/psd/python-net/aspose.gis.common/circulararc) |  |


### Method: get_coordinate(angle) {#get_coordinate_angle_4}


```
 get_coordinate(angle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | double |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


