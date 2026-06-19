---
title: "الفئة GeoJsonSeqOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Formats.GeoJsonSeq.GeoJsonSeqOptions فئة. خيارات خاصة بالبرنامج التشغيل لـ GeoJsonSeq"
type: docs
weight: 1920
url: /ar/net/aspose.gis.formats.geojsonseq/geojsonseqoptions/
---
## GeoJsonSeqOptions class

خيارات خاصة ببرنامج التشغيل لتنسيق GeoJsonSeq.

```csharp
public class GeoJsonSeqOptions : DriverOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GeoJsonSeqOptions](geojsonseqoptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArrayAsString](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/arrayasstring/) { get; set; } | ما إذا كان يجب كشف مصفوفات JSon من السلاسل أو الأعداد الصحيحة أو العشرية كسلسلة. |
| [AttributesSkip](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/attributesskip/) { get; set; } | يتحكم في ترجمة السمات: نعم - تخطي جميع السمات |
| [AutoId](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/autoid/) { get; set; } | إنشاء معرفات تلقائيًا |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان سيتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DateAsString](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/dateasstring/) { get; set; } | ما إذا كان سيتم كشف تاريخ/وقت/تاريخ-وقت JSon كسلسلة. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [GeometryAsCollection](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/geometryascollection/) { get; set; } | التحكم في تحويل الأشكال الهندسية: نعم - تغليف الأشكال بـ نوع GeometryCollection |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | هامش لاستخدامه في تحويل الأشكال الهندسية المنحنية إلى خطية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [NestedPropertiesSeparator](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/nestedpropertiesseparator/) { get; set; } | يحصل أو يعيّن سلسلة تُستخدم لفصل مكونات السمات المتداخلة. القيمة الافتراضية هي "_". |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [WriteUnsetAttribute](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/writeunsetattribute/) { get; set; } | ما إذا كان سيتم كتابة السمات غير المحددة بإضافة قيمة 'null' |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.GeoJsonSeq](../../aspose.gis.formats.geojsonseq/)
* assembly [Aspose.GIS](../../)


