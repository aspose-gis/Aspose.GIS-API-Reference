---
title: "الفئة GmlOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Formats.Gml.GmlOptions. خيارات خاصة بالسائق لتنسيق GML"
type: docs
weight: 1960
url: /ar/net/aspose.gis.formats.gml/gmloptions/
---
## GmlOptions class

خيارات خاصة ببرنامج التشغيل لتنسيق GML.

```csharp
public class GmlOptions : DriverOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GmlOptions](gmloptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان سيتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | هامش لاستخدامه في تحويل الأشكال الهندسية المنحنية إلى خطية. |
| [LoadSchemasFromInternet](../../aspose.gis.formats.gml/gmloptions/loadschemasfrominternet/) { get; set; } | يحدد ما إذا كان يُسمح لـ Aspose.GIS بتحميل مخطط XML من الإنترنت. إذا تم تعيينه إلى `false`، فإن المخططات ذات عناوين URI المطلقة التي لا تبدأ بـ 'file://' لن يتم تحميلها. القيمة الافتراضية هي `false`. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [NestedPropertiesSeparator](../../aspose.gis.formats.gml/gmloptions/nestedpropertiesseparator/) { get; set; } | يحصل أو يعيّن سلسلة تُستخدم لفصل مكونات السمات المتداخلة. القيمة الافتراضية هي "_". |
| [RestoreSchema](../../aspose.gis.formats.gml/gmloptions/restoreschema/) { get; set; } | يحدد ما إذا كان يُسمح لـ Aspose.GIS بتحليل السمات في ملف Gml لا يحتوي على مخطط XML أو لا يمكن تحميله. إذا تم تعيينه إلى `true`، فإن قارئ Aspose.GIS لا يتطلب وجود مخطط XML. القيمة الافتراضية هي `false`. |
| [SchemaLocation](../../aspose.gis.formats.gml/gmloptions/schemalocation/) { get; set; } | قائمة مفصولة بمسافات من أزواج URI. الـ URI الأول في كل زوج هو URI للمساحة الاسمية، والـ URI الثاني هو مسار إلى مخطط XML للمساحة الاسمية. إذا تم تعيينه إلى `null`، فإن [`GmlDriver`](../gmldriver/) سيحاول قراءة schemaLocation من العنصر الجذر للمستند. القيمة الافتراضية هي `null`. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XmlResolver](../../aspose.gis.formats.gml/gmloptions/xmlresolver/) { get; set; } | كائن [`XmlResolver`](./xmlresolver/) يُستخدم لحل الموارد الخارجية. القيمة الافتراضية هي XmlUrlResolver. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Gml](../../aspose.gis.formats.gml/)
* assembly [Aspose.GIS](../../)


