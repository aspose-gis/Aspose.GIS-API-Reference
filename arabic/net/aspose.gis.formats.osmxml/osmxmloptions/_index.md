---
title: "الفئة OsmXmlOptions"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Formats.OsmXml.OsmXmlOptions. خيارات خاصة بالسائق لتنسيق OSM XML"
type: docs
weight: 2270
url: /ar/net/aspose.gis.formats.osmxml/osmxmloptions/
---
## OsmXmlOptions class

خيارات خاصة ببرنامج التشغيل لتنسيق OSM XML.

```csharp
public class OsmXmlOptions : DriverOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OsmXmlOptions](osmxmloptions/)() | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | يحدد ما إذا كان سيتم إغلاق LinearRing غير المغلقة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل الهندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | يحدد المسافة لـ [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/). القيمة الافتراضية هي `0`. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | هامش لاستخدامه في تحويل الأشكال الهندسية المنحنية إلى خطية. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي M عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ReportAllNodes](../../aspose.gis.formats.osmxml/osmxmloptions/reportallnodes/) { get; set; } | الإبلاغ عن جميع العقد كميزات، حتى إذا لم تكن لديها أي وسوم ذات أهمية. |
| [ReportAllWays](../../aspose.gis.formats.osmxml/osmxmloptions/reportallways/) { get; set; } | الإبلاغ عن جميع الطرق كميزات، حتى إذا لم تكن لديها أي وسوم ذات أهمية أو أي عقد. |
| [ReportCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/reportcommonattributes/) { get; set; } | الإبلاغ عن سمات OSM الشائعة: visible, version, changeset, timestamp, user و uid. سيتم الإبلاغ عن السمات الشائعة كسمات للميزات مع البادئة "osm_"، مثل osm_user، osm_timestamp، إلخ. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي `false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | يحدد المسافة لـ [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/). القيمة الافتراضية هي `0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة. إذا تم تعيينه إلى `true`، يتم استدعاء [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) لكل شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) هو `false`)، يتم رمي [`GisException`](../../aspose.gis/gisexception/). |
| [WriteCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/writecommonattributes/) { get; set; } | كتابة سمات OSM الشائعة: visible, version, changeset, timestamp, user و uid. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي `false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | نموذج [`PrecisionModel`](../../aspose.gis/precisionmodel/) سيُطبق على إحداثي Z عندما تُضاف الأشكال الهندسية إلى [`VectorLayer`](../../aspose.gis/vectorlayer/) أو عندما تُقرأ من [`VectorLayer`](../../aspose.gis/vectorlayer/). القيمة الافتراضية هي [`Exact`](../../aspose.gis/precisionmodel/exact/). |

### انظر أيضًا

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml/)
* assembly [Aspose.GIS](../../)


