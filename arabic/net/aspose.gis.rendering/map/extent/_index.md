---
title: "Map.Extent"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية Map. تحدد حدود الخريطة التي سيتم تصييرها. إذا تم تعيينها إلى null يتم حساب الحدود أثناء التصيير لتضمين جميع الأشكال في جميع الطبقات."
type: docs
weight: 40
url: /ar/net/aspose.gis.rendering/map/extent/
---
## Map.Extent property

يحدد حدود الخريطة لتصيرها. إذا تم تعيينه إلى `null`، يتم حساب الامتداد أثناء التصيير لتضمين جميع الأشكال في جميع الطبقات.

```csharp
public Extent Extent { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | [`IsValid`](../../../aspose.gis/extent/isvalid/) هو `false`.[`Width`](../../../aspose.gis/extent/width/) أقل من أو يساوي الصفر.[`Height`](../../../aspose.gis/extent/height/) أقل من أو يساوي الصفر.[`SpatialReferenceSystem`](../../../aspose.gis/extent/spatialreferencesystem/) هو `null`. |

## ملاحظات

إذا لم يكن نظام الإحداثيات المكاني للامتداد مساويًا لنظام الإحداثيات المكاني للخريطة، يتم تحويل الامتداد إلى نظام الإحداثيات المكاني الهدف أثناء العرض.

### انظر أيضًا

* class [Extent](../../../aspose.gis/extent/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


