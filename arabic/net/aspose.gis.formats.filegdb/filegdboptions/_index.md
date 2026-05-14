---
title: "الفئة FileGdbOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Formats.FileGdb.FileGdbOptions فئة. خيارات خاصة بالسائق لتنسيق FileGDB"
type: docs
weight: 1860
url: /ar/net/aspose.gis.formats.filegdb/filegdboptions/
---
## FileGdbOptions class

خيارات خاصة بالسائق لتنسيق FileGDB.

```csharp
public sealed class FileGdbOptions : DriverOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [FileGdbOptions](filegdboptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان يتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CoordinatePrecisionGrid](../../aspose.gis.formats.filegdb/filegdboptions/coordinateprecisiongrid/) { get; set; } | شبكة دقة إحداثيات للاستخدام في طبقة جديدة. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان يتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [EnsureValidCoordinatesRange](../../aspose.gis.formats.filegdb/filegdboptions/ensurevalidcoordinatesrange/) { get; set; } | ما إذا كان يجب أن تكون الإحداثيات ضمن النطاق الصالح. |
| [ExpectedGeometryType](../../aspose.gis.formats.filegdb/filegdboptions/expectedgeometrytype/) { get; set; } | نوع الهندسة المتوقع للطبقة. إذا تم تعيين هذا الخيار فإننا نسمح بإضافة فقط الهندسات من هذا النوع |
| [GeometryFieldName](../../aspose.gis.formats.filegdb/filegdboptions/geometryfieldname/) { get; set; } | اسم حقل الهندسة. |
| [HasM](../../aspose.gis.formats.filegdb/filegdboptions/hasm/) { get; set; } | هل يمكن للهندسات في الطبقة أن تحتوي على إحداثي 'm'. بشكل افتراضي يكون صحيحًا |
| [HasZ](../../aspose.gis.formats.filegdb/filegdboptions/hasz/) { get; set; } | هل يمكن للهندسات في الطبقة أن تحتوي على إحداثي 'z'. بشكل افتراضي يكون صحيحًا |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | قيمة تحمل تُستخدم لتقويم الأشكال المنحنية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [MTolerance](../../aspose.gis.formats.filegdb/filegdboptions/mtolerance/) { get; set; } | تحمل الالتقاط للمحور M. |
| [ObjectIdFieldName](../../aspose.gis.formats.filegdb/filegdboptions/objectidfieldname/) { get; set; } | اسم حقل معرف الكائن. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [XYTolerance](../../aspose.gis.formats.filegdb/filegdboptions/xytolerance/) { get; set; } | تحمل الالتقاط للمحاور X و Y. |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZTolerance](../../aspose.gis.formats.filegdb/filegdboptions/ztolerance/) { get; set; } | تحمل الالتقاط للمحور Z. |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.FileGdb](../../aspose.gis.formats.filegdb/)
* assembly [Aspose.GIS](../../)


