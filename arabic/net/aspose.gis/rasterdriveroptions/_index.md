---
title: "الفئة RasterDriverOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.RasterDriverOptions. خيارات لبرنامج تشغيل RasterDriver"
type: docs
weight: 3910
url: /ar/net/aspose.gis/rasterdriveroptions/
---
## RasterDriverOptions class

خيارات لبرنامج [`RasterDriver`](../rasterdriver/).

```csharp
public abstract class RasterDriverOptions : DriverOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان يتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان يتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | قيمة تحمل تُستخدم لتقويم الأشكال المنحنية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../precisionmodel/) سيتم تطبيقه على إحداثي M عندما تُضاف الأشكال إلى [`VectorLayer`](../vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../vectorlayer/). القيمة الافتراضية هي [`Exact`](../precisionmodel/exact/). |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../precisionmodel/) سيتم تطبيقه على إحداثيات X و Y عندما تُضاف الأشكال إلى [`VectorLayer`](../vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../vectorlayer/). القيمة الافتراضية هي [`Exact`](../precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../precisionmodel/) سيتم تطبيقه على إحداثي Z عندما تُضاف الأشكال إلى [`VectorLayer`](../vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../vectorlayer/). القيمة الافتراضية هي [`Exact`](../precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../driveroptions/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


