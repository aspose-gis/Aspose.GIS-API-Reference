---
title: "فئة GeoConvert"
type: docs
weight: 1140
url: /ar/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | يعيد الموضع المحسوب كسلسلة في الصيغة المحددة. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | يعيد الموضع المحسوب كسلسلة في الصيغة المحددة. |
| [parse_point_text(text)](#parse_point_text_text_3) | يقوم بتحويل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | يقوم بتحويل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

يعيد الموضع المحسوب كسلسلة في الصيغة المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| خط العرض | double | خط عرض الموضع. |
| خط الطول | double | خط طول الموضع. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | صيغة النتيجة. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | الموضع كسلسلة. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

يعيد الموضع المحسوب كسلسلة في الصيغة المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | كائن IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | صيغة النتيجة. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | الموضع كسلسلة. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

يقوم بتحويل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| text | string | سلسلة تحتوي على إحداثيات للتحويل.<br/>            يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول.<br/>            يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة أو بفاصلة منقوطة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | كائن IPoint مع إحداثيات مكافئة للسلسلة المدخلة. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

يقوم بتحويل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| text | string | سلسلة تحتوي على إحداثيات للتحويل.<br/>            يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول.<br/>            يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة أو بفاصلة منقوطة. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | عند عودة هذه الطريقة، يحتوي على كائن IPoint مع الإحداثيات التي تم تحليلها إذا نجح التحويل، أو null إذا فشل التحويل. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | True إذا تم تحليل النص بنجاح، وإلا False. |


