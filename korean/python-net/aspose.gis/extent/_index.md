---
title: "Extent 클래스"
type: docs
weight: 820
url: /ko/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Extent()](#Extent__1) | 새 인스턴스를 생성합니다. |
| [Extent(srs)](#Extent_srs_2) | 새 인스턴스를 생성합니다. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Extent의 중심. |
| 높이 | double | r | Extent의 높이. |
| is_valid | bool | r | 이 [Extent](/psd/python-net/aspose.gis/extent/)가 유효한지 여부를 결정합니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 이 Extent와 연결됩니다.<br/>            [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/)이 알 수 없는 경우 <see langword="null" /> 일 수 있습니다.<br/>            Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            서로 다른 공간 참조 시스템 간에 Extent를 변환하기 위해 사용합니다. |
| width | double | r | Extent의 너비. |
| x_max | double | r/w | X 좌표의 최대값. |
| x_min | double | r/w | X 좌표의 최소값. |
| y_max | double | r/w | Y 좌표의 최대값. |
| y_min | double | r/w | Y 좌표의 최소값. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |
| [contains(extent)](#contains_extent_2) | 이 범위가 인수를 포함하는지 여부를 결정합니다. |
| [contains(geometry)](#contains_geometry_3) | 이 범위가 인수를 포함하는지 여부를 결정합니다. |
| [contains(x, y)](#contains_x_y_4) | 이 범위가 인수로 정의된 좌표를 포함하는지 여부를 결정합니다. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | 이 범위를 포함하는 지정된 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)의 새 범위를 반환합니다. |
| [grow(extent)](#grow_extent_6) | 이 범위를 확장하여 인수를 포함하도록 합니다. |
| [grow(x, y)](#grow_x_y_7) | 이 범위를 확장하여 지정된 점을 포함하도록 합니다. |
| [grow_x(value)](#grow_x_value_8) | X 축을 따라 이 범위를 확장하여 지정된 값을 포함하도록 합니다. |
| [grow_y(value)](#grow_y_value_9) | Y 축을 따라 이 범위를 확장하여 지정된 값을 포함하도록 합니다. |
| [intersects(extent)](#intersects_extent_10) | 이 범위가 인수와 교차하는지 여부를 결정합니다. |
| [intersects(geometry)](#intersects_geometry_11) | 이 범위가 인수와 교차하는지 여부를 결정합니다. |
| normalize() | 만약 [Extent.width](/psd/python-net/aspose.gis/extent/)가 음수인 경우 [Extent.x_min](/psd/python-net/aspose.gis/extent/)와 [Extent.x_max](/psd/python-net/aspose.gis/extent/)를 교환하고<br/>            [Extent.height](/psd/python-net/aspose.gis/extent/)가 음수인 경우 [Extent.y_min](/psd/python-net/aspose.gis/extent/)와 [Extent.y_max](/psd/python-net/aspose.gis/extent/)를 교환합니다. |
| [to_polygon()](#to_polygon__12) | 이 범위를 이를 나타내는 직사각형 폴리곤으로 변환합니다. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

새 인스턴스를 생성합니다.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 이 범위와 연관된.<br/>            SRS가 알 수 없음을 나타내기 위해 <see langword="null" />일 수 있습니다. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x_min | double | X 최소값. |
| y_min | double | Y 최소값. |
| x_max | double | X 최대값. |
| y_max | double | Y 최대값. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 이 범위와 연관된.<br/>            SRS가 알 수 없음을 나타내기 위해 <see langword="null" />일 수 있습니다. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 인스턴스의 복제본. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

이 범위가 인수를 포함하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 다른 범위. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 값, 이 범위가 인수를 포함하는지 여부를 나타냅니다. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

이 범위가 인수를 포함하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 포함 여부를 테스트할 기하학 객체. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 값, 이 범위가 인수를 포함하는지 여부를 나타냅니다. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

이 범위가 인수로 정의된 좌표를 포함하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | 좌표의 X. |
| y | double | 좌표의 Y. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 값, 좌표가 경계 상자 내부에 있는지 여부를 나타냅니다. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

이 범위를 포함하는 지정된 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)의 새 범위를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 변환할 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 범위를 지정된 SRS로 변환한 결과. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

이 범위를 확장하여 인수를 포함하도록 합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 다른 범위. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

이 범위를 확장하여 지정된 점을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | 포함할 X 좌표. |
| y | double | 포함할 Y 좌표. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

X 축을 따라 이 범위를 확장하여 지정된 값을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 포함할 값. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Y 축을 따라 이 범위를 확장하여 지정된 값을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 포함할 값. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

이 범위가 인수와 교차하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 다른 범위. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 값, 이 범위가 인수와 교차하는지 여부를 나타냅니다. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

이 범위가 인수와 교차하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 교차를 테스트하기 위한 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 값, 이 범위가 인수와 교차하는지 여부를 나타냅니다. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

이 범위를 이를 나타내는 직사각형 폴리곤으로 변환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 이 범위를 나타내는 직사각형 [Polygon](/psd/python-net/aspose.gis.geometries/polygon/). 잘못된 범위의 경우<br/>            빈 폴리곤이 반환됩니다. |


