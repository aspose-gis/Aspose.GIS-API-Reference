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
| **Name** | **الوصف** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | يعيد الموضع المحسوب كسلسلة نصية بالتنسيق المحدد. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | يعيد الموضع المحسوب كسلسلة نصية بالتنسيق المحدد. |
| [parse_point_text(text)](#parse_point_text_text_3) | يحوّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | يحوّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحاً أم فاشلاً. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

يعيد الموضع المحسوب كسلسلة نصية بالتنسيق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| خط العرض | double | خط عرض الموضع. |
| خط الطول | double | خط طول الموضع. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | تنسيق النتيجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | الموضع كسلسلة نصية. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

يعيد الموضع المحسوب كسلسلة نصية بالتنسيق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | كائن IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | تنسيق النتيجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | الموضع كسلسلة نصية. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

يحوّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | string | سلسلة نصية تحتوي على إحداثيات للتحويل.<br/>            يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول.<br/>            يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة، أو بفاصلة منقوطة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | كائن IPoint يحتوي على إحداثيات مكافئة للسلسلة المدخلة. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

يحوّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحاً أم فاشلاً.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | string | سلسلة نصية تحتوي على إحداثيات للتحويل.<br/>            يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول.<br/>            يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة، أو بفاصلة منقوطة. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | عند عودة هذه الطريقة، يحتوي على كائن IPoint بالإحداثيات التي تم تحليلها إذا نجح التحويل، أو null إذا فشل التحويل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | True إذا تم تحليل النص بنجاح، وإلا False. |


