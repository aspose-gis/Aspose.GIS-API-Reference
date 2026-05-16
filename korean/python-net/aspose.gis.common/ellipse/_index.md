---
title: "Ellipse 클래스"
type: docs
weight: 260
url: /ko/python-net/aspose.gis.common/ellipse/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.Ellipse

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipse(center, x_radius, y_radius, rotation)](#Ellipse_center_x_radius_y_radius_rotation_1) | Ellipse 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| 회전 | double | r |  |
| x_radius | double | r |  |
| y_radius | double | r |  |
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

Ellipse 클래스의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| x_radius | double |  |
| y_radius | double |  |
| 회전 | double |  |

### Method: get_angle(coordinate) {#get_angle_coordinate_1}


```
 get_angle(coordinate) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double |  |


### Method: get_arc(start, end, clockwise) {#get_arc_start_end_clockwise_2}


```
 get_arc(start, end, clockwise) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| 시계 방향 | bool |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [EllipticArc](/psd/python-net/aspose.gis.common/ellipticarc) |  |


### Method: get_coordinate(parametric_angle) {#get_coordinate_parametric_angle_3}


```
 get_coordinate(parametric_angle) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parametric_angle | double |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


