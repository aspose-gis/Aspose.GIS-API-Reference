---
title: "Ellipse Κλάση"
type: docs
weight: 260
url: /el/python-net/aspose.gis.common/ellipse/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.Ellipse

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipse(center, x_radius, y_radius, rotation)](#Ellipse_center_x_radius_y_radius_rotation_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης Ellipse |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| περιστροφή | double | r |  |
| x_ακτίνα | double | r |  |
| y_ακτίνα | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_angle(coordinate)](#get_angle_coordinate_1) |    |
| [get_arc(start, end, clockwise)](#get_arc_start_end_clockwise_2) |    |
| [get_coordinate(parametric_angle)](#get_coordinate_parametric_angle_3) |    |
| linearize(coordinates, step_size_in_degrees) |  |


### Constructor: Ellipse(center, x_radius, y_radius, rotation) {#Ellipse_center_x_radius_y_radius_rotation_1}


```
 Ellipse(center, x_radius, y_radius, rotation) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης Ellipse

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| x_ακτίνα | double |  |
| y_ακτίνα | double |  |
| περιστροφή | double |  |

### Method: get_angle(coordinate) {#get_angle_coordinate_1}


```
 get_angle(coordinate) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double |  |


### Method: get_arc(start, end, clockwise) {#get_arc_start_end_clockwise_2}


```
 get_arc(start, end, clockwise) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| clockwise | bool |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [EllipticArc](/psd/python-net/aspose.gis.common/ellipticarc) |  |


### Method: get_coordinate(parametric_angle) {#get_coordinate_parametric_angle_3}


```
 get_coordinate(parametric_angle) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parametric_angle | double |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


