---
title: "RasterLayer.GetSpatialPoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RasterLayer. تحول العمود والصف المحددين إلى الإحداثية المكانية"
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
| cellX | Int32 | القيمة للعمود (إحداثي س). يبدأ العد من 0. |
| cellY | Int32 | القيمة للصف (إحداثي ص). يبدأ العد من 0. |

### قيمة الإرجاع

تُرجع إحداثي x للزاوية العلوية اليسرى بناءً على العمود والصف.

## ملاحظات

إذا تم تمرير أي من المعاملين خارج نطاق البُعد المقابل للراستر، فستُعيد إحداثيات خارج الراستر بافتراض أن شبكة الراستر قابلة للتطبيق خارج حدود الراستر.

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


