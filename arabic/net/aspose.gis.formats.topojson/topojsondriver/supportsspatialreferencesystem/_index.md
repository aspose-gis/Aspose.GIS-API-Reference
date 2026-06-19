---
title: "TopoJsonDriver.SupportsSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة TopoJsonDriver. تحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل السائق"
type: docs
weight: 60
url: /ar/net/aspose.gis.formats.topojson/topojsondriver/supportsspatialreferencesystem/
---
## TopoJsonDriver.SupportsSpatialReferenceSystem method

يحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل البرنامج تشغيل.

```csharp
public override bool SupportsSpatialReferenceSystem(SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

قيمة منطقية، تشير إلى ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق.

## ملاحظات

بالنسبة إلى TopoJSON، نظام الإحداثيات المكانية الوحيد المدعوم هو 'null'، لأنه لا توجد طريقة لتخزين معلومات نظام الإحداثيات المكانية في ملف TopoJSON ولا تحدد مواصفة TopoJSON ما هو نظام الإحداثيات المكانية للأشكال الهندسية في ملف TopoJSON.

### انظر أيضًا

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [TopoJsonDriver](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsondriver/)
* assembly [Aspose.GIS](../../../)


