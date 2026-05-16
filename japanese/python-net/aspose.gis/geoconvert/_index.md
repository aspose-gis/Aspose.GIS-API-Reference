---
title: "GeoConvert クラス"
type: docs
weight: 1140
url: /ja/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | 指定された形式で計算された位置を文字列として返します。 |
| [as_point_text(point, format)](#as_point_text_point_format_2) | 指定された形式で計算された位置を文字列として返します。 |
| [parse_point_text(text)](#parse_point_text_text_3) | 座標を含む文字列を IPoint オブジェクトに変換します。 |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | 座標を含む文字列を IPoint オブジェクトに変換します。戻り値は変換が成功したか失敗したかを示します。 |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

指定された形式で計算された位置を文字列として返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 緯度 | double | 位置の緯度。 |
| 経度 | double | 位置の経度。 |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 結果の形式。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | 文字列としての位置。 |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

指定された形式で計算された位置を文字列として返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint オブジェクト。 |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | 結果の形式。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | 文字列としての位置。 |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

座標を含む文字列を IPoint オブジェクトに変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | string | 変換する座標を含む文字列。<br/>            文字列は緯度と経度の両方の座標を含んでいる必要があります。<br/>            座標は空白、カンマ、またはセミコロンで区切られるべきです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 入力文字列と同等の座標を持つ IPoint オブジェクト。 |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

座標を含む文字列を IPoint オブジェクトに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| text | string | 変換する座標を含む文字列。<br/>            文字列は緯度と経度の両方の座標を含んでいる必要があります。<br/>            座標は空白、カンマ、またはセミコロンで区切られるべきです。 |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | このメソッドが戻ると、変換が成功した場合は解析された座標を持つ IPoint オブジェクトが含まれ、失敗した場合は null が含まれます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | テキストが正常に解析された場合は True、そうでない場合は False。 |


