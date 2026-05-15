---
title: "Tetragon 类"
type: docs
weight: 190
url: /zh/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | 初始化 Tetragon 类的新实例 |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | 初始化 Tetragon 类的新实例 |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | 初始化 Tetragon 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| 角度 | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

初始化 Tetragon 类的新实例

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

初始化 Tetragon 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| 角度 | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

初始化 Tetragon 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| height | double |  |
| 角度 | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


