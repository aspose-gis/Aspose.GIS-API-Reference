---
title: "الفئة GpxOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Formats.Gpx.GpxOptions. خيارات خاصة بالسائق لتنسيق GPX"
type: docs
weight: 1980
url: /ar/net/aspose.gis.formats.gpx/gpxoptions/
---
## GpxOptions class

خيارات خاصة ببرنامج التشغيل لتنسيق GPX.

```csharp
public class GpxOptions : DriverOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GpxOptions](gpxoptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان سيتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | هامش لاستخدامه في تحويل الأشكال الهندسية المنحنية إلى خطية. |
| [MAttribute](../../aspose.gis.formats.gpx/gpxoptions/mattribute/) { get; set; } | يحدد أي سمة GPX سيتم تصديرها كإحداثي 'M' لنقاط الطريق، ونقاط المسار، ونقاط التتبع. السلوك هو نفسه مع [`ZAttribute`](./zattribute/)، الافتراضي هو `null`. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [NestedAttributeSeparator](../../aspose.gis.formats.gpx/gpxoptions/nestedattributeseparator/) { get; } | سلسلة لفصل اسم السمة المتداخلة ومؤشراتها. الافتراضي هو الشرطتين السفلية المزدوجتين "__". |
| [ReadNestedAttributes](../../aspose.gis.formats.gpx/gpxoptions/readnestedattributes/) { get; set; } | يحدد ما إذا كانت نقاط GPX، مثل 'trkpt' و 'rtept'، تحتوي على سمات داخلية وما إذا كان يجب قراءتها. الافتراضي هو `false`. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZAttribute](../../aspose.gis.formats.gpx/gpxoptions/zattribute/) { get; set; } | يحدد أي سمة GPX سيتم تصديرها كإحداثي 'Z' لنقاط الطريق، ونقاط المسار، ونقاط التتبع. إذا كان `null` - لن يتم تصدير أي سمة كإحداثي 'Z'. الافتراضي هو "ele". القيم الممكنة هي أسماء جميع سمات XML في GPX التي يمكن تمثيلها كقيمة مزدوجة (مثل "speed"، "magvar"، "geoidheight" وغيرها). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Gpx](../../aspose.gis.formats.gpx/)
* assembly [Aspose.GIS](../../)


