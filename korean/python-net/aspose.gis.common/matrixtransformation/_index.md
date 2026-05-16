---
title: "MatrixTransformation 클래스"
type: docs
weight: 670
url: /ko/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | MatrixTransformation 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| 회전 | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 현재 인스턴스의 복사본인 새 객체를 생성합니다. |
| lock_from_editing() |  |
| rotate(cos, sin) |  |
| rotate(degrees) |  |
| scale(zoom_x, zoom_y) |  |
| [transform(coordinate)](#transform_coordinate_2) |    |
| [transform(x, y)](#transform_x_y_3) |    |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: MatrixTransformation() {#MatrixTransformation__1}


```
 MatrixTransformation() 
```

MatrixTransformation 클래스의 새 인스턴스를 초기화합니다

### Method: clone() {#clone__1}


```
 clone() 
```

현재 인스턴스의 복사본인 새 객체를 생성합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


