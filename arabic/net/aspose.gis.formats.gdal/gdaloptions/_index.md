---
title: Class GdalOptions
second_title: Aspose.GIS لمرجع .NET API
description: Aspose.Gis.Formats.GDAL.GdalOptions فصل. خيارات خاصة ببرنامج التشغيل لتنسيق GDAL .
type: docs
weight: 290
url: /ar/net/aspose.gis.formats.gdal/gdaloptions/
---
## GdalOptions class

خيارات خاصة ببرنامج التشغيل لتنسيق GDAL .

```csharp
public class GdalOptions : DriverOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GdalOptions](gdaloptions/)(string) | إنشاء مثيل جديد . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | تحديد ما إذا كان يتم إغلاق ملفLinearRing في كل هندسة. افتراضات إلى`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | لتحديد ما إذا كان سيتم إضافة نقطة جديدة في المنتصف لكل مقطع هندسي. افتراضات إلى`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | تحديد ما إذا كان يتم حذف النقاط القريبة في كل شكل هندسي. افتراضات إلى`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) . افتراضات إلى`0` . |
| [FileName](../../aspose.gis.formats.gdal/gdaloptions/filename/) { get; set; } | اسم التطبيق المراد بدء تشغيله |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | تفاوت لاستخدامه في تحديد الأشكال الهندسية للمنحنى الخطي. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | أ[`PrecisionModel`](../../aspose.gis/precisionmodel/) التي سيتم تطبيقها على M إحداثيات عند إضافة الأشكال الهندسية إلى[`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما يتم قراءتها من[`VectorLayer`](../../aspose.gis/vectorlayer/) . القيمة الافتراضية هي[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [PathToTempFile](../../aspose.gis.formats.gdal/gdaloptions/pathtotempfile/) { get; } | مسار الملفات المؤقتة . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | لتحديد ما إذا كان سيتم حذف النقاط الموجودة على نفس المقطع في كل شكل هندسي. افتراضات إلى`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) . افتراضات إلى`0` . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة. إذا تم التعيين على`true` و[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) يتم استدعاؤها لكل هندسة _ عند إضافتها إلى الطبقة ، وإذا فشل التحقق من الصحة ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) يكون`false` ) ،[`GisException`](../../aspose.gis/gisexception/) تم القيت . |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | لتحديد ما إذا كان مسموحًا بتحويل المضلع أو متعدد الأضلاع إلى خط مستقيم. افتراضات إلى`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | أ[`PrecisionModel`](../../aspose.gis/precisionmodel/) التي سيتم تطبيقها على إحداثيات X و Y عند إضافة الأشكال الهندسية إلى[`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما يتم قراءتها من[`VectorLayer`](../../aspose.gis/vectorlayer/) . القيمة الافتراضية هي[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | أ[`PrecisionModel`](../../aspose.gis/precisionmodel/) التي سيتم تطبيقها على Z إحداثيات عند إضافة الأشكال الهندسية إلى[`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما يتم قراءتها من[`VectorLayer`](../../aspose.gis/vectorlayer/) . القيمة الافتراضية هي[`Exact`](../../aspose.gis/precisionmodel/exact/) . |

### أنظر أيضا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* مساحة الاسم [Aspose.Gis.Formats.GDAL](../../aspose.gis.formats.gdal/)
* المجسم [Aspose.GIS](../../)

