---
title: "Tetragon 클래스"
type: docs
weight: 190
url: /ko/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | Tetragon 클래스의 새 인스턴스를 초기화합니다 |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | Tetragon 클래스의 새 인스턴스를 초기화합니다 |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | Tetragon 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 각도 | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

Tetragon 클래스의 새 인스턴스를 초기화합니다

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

Tetragon 클래스의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| 각도 | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

Tetragon 클래스의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| 높이 | double |  |
| 각도 | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


