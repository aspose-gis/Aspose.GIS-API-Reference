---
title: "GeoConvert 类"
type: docs
weight: 1140
url: /zh/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | 返回按指定格式计算的位置字符串。 |
| [as_point_text(point, format)](#as_point_text_point_format_2) | 返回按指定格式计算的位置字符串。 |
| [parse_point_text(text)](#parse_point_text_text_3) | 将包含坐标的字符串转换为 IPoint 对象。 |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | 将包含坐标的字符串转换为 IPoint 对象。返回值指示转换是成功还是失败。 |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

返回按指定格式计算的位置字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 纬度 | double | 位置纬度。 |
| 经度 | double | 位置经度。 |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 结果的格式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 位置的字符串表示。 |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

返回按指定格式计算的位置字符串。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint 对象。 |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 结果的格式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 位置的字符串表示。 |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

将包含坐标的字符串转换为 IPoint 对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | string | 一个包含待转换坐标的字符串。<br/>            该字符串应同时包含纬度和经度坐标。<br/>            坐标应以空格、逗号或分号分隔。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint 对象，其坐标等价于输入字符串。 |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

将包含坐标的字符串转换为 IPoint 对象。返回值指示转换是成功还是失败。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | string | 一个包含待转换坐标的字符串。<br/>            该字符串应同时包含纬度和经度坐标。<br/>            坐标应以空格、逗号或分号分隔。 |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | 当此方法返回时，包含已解析坐标的 IPoint 对象（如果转换成功），否则为 null（如果转换失败）。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果文本解析成功则为 True，否则为 False。 |


