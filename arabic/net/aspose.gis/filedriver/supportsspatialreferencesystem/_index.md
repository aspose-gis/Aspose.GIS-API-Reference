---
title: "FileDriver.SupportsSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileDriver. تحدد ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق"
type: docs
weight: 100
url: /ar/net/aspose.gis/filedriver/supportsspatialreferencesystem/
---
## FileDriver.SupportsSpatialReferenceSystem method

يحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل برنامج التشغيل.

```csharp
public abstract bool SupportsSpatialReferenceSystem(SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

قيمة منطقية تشير إلى ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق. `null` يعتبر مدعومًا من أي سائق.

## ملاحظات

إذا لم يكن نظام الإسناد المكاني مدعومًا، وقمت بتمريره إلى طريقة [`CreateLayer`](../createlayer/)، سيتم رمي استثناء NotSupportedException.

### انظر أيضًا

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


