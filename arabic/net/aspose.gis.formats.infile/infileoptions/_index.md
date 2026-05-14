---
title: "الفئة InFileOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Formats.InFile.InFileOptions فئة. خيارات خاصة ببرنامج التشغيل لطبقة InFile"
type: docs
weight: 2000
url: /ar/net/aspose.gis.formats.infile/infileoptions/
---
## InFileOptions class

خيارات خاصة بالمحرك لطبقة InFile.

```csharp
public class InFileOptions : DriverOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [InFileOptions](infileoptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArrayAsString](../../aspose.gis.formats.infile/infileoptions/arrayasstring/) { get; set; } | ما إذا كان يجب كشف مصفوفات JSon من السلاسل أو الأعداد الصحيحة أو العشرية كسلسلة. |
| [AttributesSkip](../../aspose.gis.formats.infile/infileoptions/attributesskip/) { get; set; } | يتحكم في ترجمة السمات: نعم - تخطي جميع السمات |
| [AutoId](../../aspose.gis.formats.infile/infileoptions/autoid/) { get; set; } | إنشاء معرفات تلقائيًا |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان يتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CountOfFeatureInPart](../../aspose.gis.formats.infile/infileoptions/countoffeatureinpart/) { get; set; } | الحد الأقصى لعدد الميزات في كل جزء من الملف |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان يتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DateAsString](../../aspose.gis.formats.infile/infileoptions/dateasstring/) { get; set; } | ما إذا كان يجب كشف تاريخ/وقت/تاريخ‑وقت JSon كسلسلة. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [GeometryAsCollection](../../aspose.gis.formats.infile/infileoptions/geometryascollection/) { get; set; } | التحكم في ترجمة الأشكال: نعم - غلف الأشكال بنوع GeometryCollection |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | قيمة تحمل تُستخدم لتقويم الأشكال المنحنية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [NestedPropertiesSeparator](../../aspose.gis.formats.infile/infileoptions/nestedpropertiesseparator/) { get; set; } | يحصل أو يعيّن سلسلة تُستخدم لفصل مكونات السمات المتداخلة. القيمة الافتراضية هي "_". |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [WriteUnsetAttribute](../../aspose.gis.formats.infile/infileoptions/writeunsetattribute/) { get; set; } | ما إذا كان يجب كتابة السمات غير المحددة بإضافة القيمة 'null' |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.InFile](../../aspose.gis.formats.infile/)
* assembly [Aspose.GIS](../../)


