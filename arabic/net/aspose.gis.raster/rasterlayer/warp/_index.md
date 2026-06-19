---
title: "RasterLayer.Warp"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RasterLayer. تشوه طبقة الراستر إلى أخرى"
type: docs
weight: 210
url: /ar/net/aspose.gis.raster/rasterlayer/warp/
---
## RasterLayer.Warp method

يشوه طبقة الراستر إلى أخرى.

```csharp
public RasterLayer Warp(WarpOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| options | WarpOptions | خيارات لإجراء إعادة الإسقاط. |

### قيمة الإرجاع

طبقة الراستر المشوهة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون الوسيط null. اسم المعامل: options. |
| ArgumentException | نظام الإحداثيات المكانية للمصدر غير معروف. |
| InvalidOperationException | لا يمكن أن تكون الطبقة الأصلية WarpRasterLayer أخرى. |

### انظر أيضًا

* class [WarpOptions](../../warpoptions/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


