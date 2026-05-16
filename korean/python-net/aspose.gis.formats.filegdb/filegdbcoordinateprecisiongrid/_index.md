---
title: "FileGdbCoordinatePrecisionGrid 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | FileGdbCoordinatePrecisionGrid 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | M 좌표의 원점을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| m_scale | Nullable<double> | r/w | M 좌표의 스케일을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| x_origin | Nullable<double> | r/w | X 좌표의 원점을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| xy_scale | Nullable<double> | r/w | X 및 Y 좌표의 스케일을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| y_origin | Nullable<double> | r/w | Y 좌표의 원점을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| z_origin | Nullable<double> | r/w | Z 좌표의 원점을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
| z_scale | Nullable<double> | r/w | Z 좌표의 스케일을 가져오거나 설정합니다. <see langword="null" /> 로 설정하면 기본값이 사용됩니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | <c>FileGdbCoordinatePrecisionGrid</c>를 새로 생성하여 사각형 내부의 모든 값이 표현 가능하도록 합니다. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

FileGdbCoordinatePrecisionGrid 클래스의 새 인스턴스를 초기화합니다

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

<c>FileGdbCoordinatePrecisionGrid</c>를 새로 생성하여 사각형 내부의 모든 값이 표현 가능하도록 합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 사각형의 한 모서리. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 사각형의 반대 모서리. <paramref name="p1" />와 동일한 차원을 가져야 합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | <c>FileGdbCoordinatePrecisionGrid</c>는 사각형 내부의 모든 값이 표현 가능하도록 합니다.<br/>            사각형 외부의 값은 표현할 수 없으므로 FileGDB 레이어에 기록될 모든 좌표는 사각형 내부에 있어야 합니다. |


