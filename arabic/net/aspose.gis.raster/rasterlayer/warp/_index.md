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
| الخيارات | WarpOptions | خيارات لإجراء إعادة الإسقاط. |

### قيمة الإرجاع

طبقة الراستر المشوهة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعامل لا يمكن أن يكون فارغًا. اسم المعامل: options. |
| ArgumentException | نظام الإسناد المكاني للمصدر غير معروف. |
| InvalidOperationException | لا يمكن أن تكون الطبقة الأصلية WarpRasterLayer أخرى. |

### انظر أيضًا

* class [WarpOptions](../../warpoptions/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


