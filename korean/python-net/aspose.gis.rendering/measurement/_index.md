---
title: "Measurement 클래스"
type: docs
weight: 150
url: /ko/python-net/aspose.gis.rendering/measurement/
---

**Summary:** A number that indicates a render measurement.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Measurement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Measurement()](#Measurement__1) | Measurement 클래스의 새 인스턴스를 초기화합니다 |
| [Measurement(value, unit)](#Measurement_value_unit_2) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 측정 단위입니다. |
| 값 | double | r | 측정 길이를 나타내는 숫자. |
| zero [static] | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r | 길이가 0인 측정값. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [inches(value)](#inches_value_1) | 인치 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |
| [map_units(value)](#map_units_value_2) | 지도 공간 기준 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |
| [meters_on_earth(value)](#meters_on_earth_value_3) | 지구상의 미터 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |
| [millimeters(value)](#millimeters_value_4) | 밀리미터 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |
| [pixels(value)](#pixels_value_5) | 픽셀 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |
| [points(value)](#points_value_6) | 포인트 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다. |


### Constructor: Measurement() {#Measurement__1}


```
 Measurement() 
```

Measurement 클래스의 새 인스턴스를 초기화합니다

### Constructor: Measurement(value, unit) {#Measurement_value_unit_2}


```
 Measurement(value, unit) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 측정 길이를 나타내는 숫자. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 측정 단위입니다. |

### Method: inches(value)  [static] {#inches_value_1}


```
 inches(value) 
```

인치 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 인치 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


### Method: map_units(value)  [static] {#map_units_value_2}


```
 map_units(value) 
```

지도 공간 기준 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 단위 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


### Method: meters_on_earth(value)  [static] {#meters_on_earth_value_3}


```
 meters_on_earth(value) 
```

지구상의 미터 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 미터 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


### Method: millimeters(value)  [static] {#millimeters_value_4}


```
 millimeters(value) 
```

밀리미터 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 밀리미터 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


### Method: pixels(value)  [static] {#pixels_value_5}


```
 pixels(value) 
```

픽셀 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 픽셀 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


### Method: points(value)  [static] {#points_value_6}


```
 points(value) 
```

포인트 단위 길이를 나타내는 <c>Measurement</c>의 새 인스턴스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 값 | double | 점의 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> 클래스의 새 인스턴스. |


