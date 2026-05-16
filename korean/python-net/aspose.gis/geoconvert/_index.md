---
title: "GeoConvert 클래스"
type: docs
weight: 1140
url: /ko/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | 지정된 형식으로 계산된 위치를 문자열로 반환합니다. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | 지정된 형식으로 계산된 위치를 문자열로 반환합니다. |
| [parse_point_text(text)](#parse_point_text_text_3) | 좌표를 포함하는 문자열을 IPoint 객체로 변환합니다. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | 좌표를 포함하는 문자열을 IPoint 객체로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

지정된 형식으로 계산된 위치를 문자열로 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 위도 | double | 위도 위치. |
| 경도 | double | 경도 위치. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 결과 형식. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 문자열 형태의 위치. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

지정된 형식으로 계산된 위치를 문자열로 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint 객체. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 결과 형식. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 문자열 형태의 위치. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

좌표를 포함하는 문자열을 IPoint 객체로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | string | 변환할 좌표를 포함하는 문자열입니다.<br/>            문자열에는 위도와 경도 좌표가 모두 포함되어야 합니다.<br/>            좌표는 공백, 쉼표 또는 세미콜론으로 구분되어야 합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 입력 문자열과 동일한 좌표를 가진 IPoint 객체입니다. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

좌표를 포함하는 문자열을 IPoint 객체로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | string | 변환할 좌표를 포함하는 문자열입니다.<br/>            문자열에는 위도와 경도 좌표가 모두 포함되어야 합니다.<br/>            좌표는 공백, 쉼표 또는 세미콜론으로 구분되어야 합니다. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | 이 메서드가 반환될 때, 변환이 성공하면 파싱된 좌표를 가진 IPoint 객체를 포함하고, 변환이 실패하면 null을 포함합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 텍스트가 성공적으로 파싱되면 True, 그렇지 않으면 False. |


