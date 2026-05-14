---
title: "RasterLayer.GetSpatialPoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RasterLayer. تقوم بتحويل العمود والصف المحددين إلى الإحداثيات المكانية"
type: docs
weight: 150
url: /ar/net/aspose.gis.raster/rasterlayer/getspatialpoint/
---
## RasterLayer.GetSpatialPoint method

يحوّل العمود والصف المحددين إلى الإحداثيات المكانية.

```csharp
public IPoint GetSpatialPoint(int cellX, int cellY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| cellX | Int32 | القيمة للعمود (إحداثي X). يبدأ الترقيم من 0. |
| cellY | Int32 | القيمة للصف (إحداثي Y). يبدأ الترقيم من 0. |

### قيمة الإرجاع

تُرجع إحداثي x للزاوية العليا اليسرى بناءً على العمود والصف.

## ملاحظات

إذا تم تمرير أي من المعاملين خارج نطاق البُعد المقابل للراستر، فستُرجع إحداثيات خارج الراستر بافتراض أن شبكة الراستر قابلة للتطبيق خارج حدود الراستر.

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


