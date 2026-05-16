---
title: "Kelas Ellipse"
type: docs
weight: 260
url: /id/python-net/aspose.gis.common/ellipse/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.Ellipse

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Ellipse(center, x_radius, y_radius, rotation)](#Ellipse_center_x_radius_y_radius_rotation_1) | Menginisialisasi instance baru dari kelas Ellipse |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| rotasi | double | r |  |
| x_radius | double | r |  |
| y_radius | double | r |  |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_angle(coordinate)](#get_angle_coordinate_1) |    |
| [get_arc(start, end, clockwise)](#get_arc_start_end_clockwise_2) |    |
| [get_coordinate(parametric_angle)](#get_coordinate_parametric_angle_3) |    |
| linearize(coordinates, step_size_in_degrees) |  |


### Constructor: Ellipse(center, x_radius, y_radius, rotation) {#Ellipse_center_x_radius_y_radius_rotation_1}


```
 Ellipse(center, x_radius, y_radius, rotation) 
```

Menginisialisasi instance baru dari kelas Ellipse

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| x_radius | double |  |
| y_radius | double |  |
| rotasi | double |  |

### Method: get_angle(coordinate) {#get_angle_coordinate_1}


```
 get_angle(coordinate) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double |  |


### Method: get_arc(start, end, clockwise) {#get_arc_start_end_clockwise_2}


```
 get_arc(start, end, clockwise) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| searah jarum jam | bool |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [EllipticArc](/psd/python-net/aspose.gis.common/ellipticarc) |  |


### Method: get_coordinate(parametric_angle) {#get_coordinate_parametric_angle_3}


```
 get_coordinate(parametric_angle) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parametric_angle | double |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


