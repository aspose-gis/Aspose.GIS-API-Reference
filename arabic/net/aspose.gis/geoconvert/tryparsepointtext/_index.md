---
title: "GeoConvert.TryParsePointText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoConvert. تُحوِّل السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كانت عملية التحويل ناجحة أم فاشلة"
type: docs
weight: 30
url: /ar/net/aspose.gis/geoconvert/tryparsepointtext/
---
## GeoConvert.TryParsePointText method

يحول السلسلة التي تحتوي على إحداثيات إلى كائن IPoint. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```csharp
public static bool TryParsePointText(string text, out IPoint point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | String | سلسلة نصية تحتوي على إحداثيات للتحويل. يجب أن تحتوي السلسلة على كل من إحداثي خط العرض وخط الطول. يجب أن تكون الإحداثيات مفصولة بمسافة، أو بفاصلة، أو بفاصلة منقوطة. |
| نقطة | IPoint& | عند عودة هذه الطريقة، تحتوي على كائن IPoint بالإحداثيات التي تم تحليلها إذا نجح التحويل، أو null إذا فشل التحويل. |

### قيمة الإرجاع

صحيح إذا تم تحليل النص بنجاح، وإلا خطأ.

## ملاحظات

أمثلة: "80° 151°", "74°50.82', 172°08.21'", "80°;151°", "2CMB", "2CMB6682893142", "2C MB 66828 93142", "WMAQ12405535".

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [GeoConvert](../)
* namespace [Aspose.Gis](../../geoconvert/)
* assembly [Aspose.GIS](../../../)


