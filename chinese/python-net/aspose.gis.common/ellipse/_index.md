---
title: "Ellipse 类"
type: docs
weight: 260
url: /zh/python-net/aspose.gis.common/ellipse/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.Ellipse

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipse(center, x_radius, y_radius, rotation)](#Ellipse_center_x_radius_y_radius_rotation_1) | 初始化 Ellipse 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| 旋转 | double | r |  |
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

初始化 Ellipse 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| x_radius | double |  |
| y_radius | double |  |
| 旋转 | double |  |

### Method: get_angle(coordinate) {#get_angle_coordinate_1}


```
 get_angle(coordinate) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double |  |


### Method: get_arc(start, end, clockwise) {#get_arc_start_end_clockwise_2}


```
 get_arc(start, end, clockwise) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| end | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |
| 顺时针 | bool |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [EllipticArc](/psd/python-net/aspose.gis.common/ellipticarc) |  |


### Method: get_coordinate(parametric_angle) {#get_coordinate_parametric_angle_3}


```
 get_coordinate(parametric_angle) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parametric_angle | double |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


