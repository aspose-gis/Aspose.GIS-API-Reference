---
title: "GeoConvert.ParsePointText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoConvert. تُحوِّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint"
type: docs
weight: 20
url: /ar/net/aspose.gis/geoconvert/parsepointtext/
---
## GeoConvert.ParsePointText method

يحول السلسلة التي تحتوي على إحداثيات إلى كائن IPoint.

```csharp
public static IPoint ParsePointText(string text)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | String | سلسلة نصية تحتوي على إحداثيات للتحويل. يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول. يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة، أو بفاصلة منقوطة. |

### قيمة الإرجاع

كائن IPoint بالإحداثيات المكافئة للسلسلة المدخلة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [GisException](../../gisexception/) |  |

## ملاحظات

أمثلة: "80° 151°", "74°50.82', 172°08.21'", "80°;151°", "2CMB", "2CMB6682893142", "2C MB 66828 93142", "WMAQ12405535".

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [GeoConvert](../)
* namespace [Aspose.Gis](../../geoconvert/)
* assembly [Aspose.GIS](../../../)


