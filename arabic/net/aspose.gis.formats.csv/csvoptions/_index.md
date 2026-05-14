---
title: "الفئة CsvOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Formats.Csv.CsvOptions. خيارات خاصة ببرنامج التشغيل لتنسيق CSV"
type: docs
weight: 1700
url: /ar/net/aspose.gis.formats.csv/csvoptions/
---
## CsvOptions class

خيارات خاصة بالمحرك لتنسيق CSV.

```csharp
public class CsvOptions : DriverOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [CsvOptions](csvoptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان يتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [ColumnM](../../aspose.gis.formats.csv/csvoptions/columnm/) { get; set; } | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي M. القيمة الافتراضية هي `null`. |
| [ColumnWkt](../../aspose.gis.formats.csv/csvoptions/columnwkt/) { get; set; } | يحصل أو يعيّن اسم العمود الذي يحتوي على نص معروف جيدًا (Well-Known Text) لتمثيل الهندسة. القيمة الافتراضية هي `null`. |
| [ColumnX](../../aspose.gis.formats.csv/csvoptions/columnx/) { get; set; } | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي X. القيمة الافتراضية هي `null`. |
| [ColumnY](../../aspose.gis.formats.csv/csvoptions/columny/) { get; set; } | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Y. القيمة الافتراضية هي `null`. |
| [ColumnZ](../../aspose.gis.formats.csv/csvoptions/columnz/) { get; set; } | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Z. القيمة الافتراضية هي `null`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان يتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [Delimiter](../../aspose.gis.formats.csv/csvoptions/delimiter/) { get; set; } | يحصل أو يعيّن حرفًا يُستخدم كفاصل لتقسيم القيم. القيمة الافتراضية هي ','. |
| [DoubleQuoteEscape](../../aspose.gis.formats.csv/csvoptions/doublequoteescape/) { get; set; } | يحصل أو يعيّن حرفًا يُستخدم كحرف هروب للاقتباسات المزدوجة. القيمة الافتراضية هي '\"'. |
| [HasAttributeNames](../../aspose.gis.formats.csv/csvoptions/hasattributenames/) { get; set; } | يحدد ما إذا كان هناك صف رأس يحتوي على أسماء السمات. القيمة الافتراضية هي `true`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | قيمة تحمل تُستخدم لتقويم الأشكال المنحنية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [StartLineNumber](../../aspose.gis.formats.csv/csvoptions/startlinenumber/) { get; set; } | يحصل أو يعيّن رقم السطر (بدءًا من الصفر) الذي سيكون الأول عند قراءة البيانات. القيمة الافتراضية هي 0. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Csv](../../aspose.gis.formats.csv/)
* assembly [Aspose.GIS](../../)


