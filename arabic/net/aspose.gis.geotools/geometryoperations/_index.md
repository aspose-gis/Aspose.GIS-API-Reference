---
title: "فئة GeometryOperations"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.GeoTools.GeometryOperations. فئة عمليات الهندسة توفر خوارزميات معالجة جغرافية إضافية للأشكال الهندسية"
type: docs
weight: 2490
url: /ar/net/aspose.gis.geotools/geometryoperations/
---
## GeometryOperations class

فئة عمليات الشكل الهندسي توفر خوارزميات معالجة جغرافية إضافية للأشكال.

```csharp
public static class GeometryOperations
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [BuildCenterline](../../aspose.gis.geotools/geometryoperations/buildcenterline/#buildcenterline_1)(IEnumerable&lt;Point&gt;) | إنشاء مخطط الخط المركزي لمجموعة من النقاط (المواقع) |
| static [BuildCenterline](../../aspose.gis.geotools/geometryoperations/buildcenterline/#buildcenterline)(Polygon) | إنشاء مخطط الخط المركزي للمضلع |
| static [CloseLinearRing](../../aspose.gis.geotools/geometryoperations/closelinearring/)(IGeometry) | يغلق المقاطع الهندسية في الحلقات إذا لزم الأمر. |
| static [CreateMidpoints](../../aspose.gis.geotools/geometryoperations/createmidpoints/)(IGeometry) | إنشاء نقاط وسطية بإضافة نقطة جديدة في الوسط لكل مقطع. |
| static [DeleteNearPoints](../../aspose.gis.geotools/geometryoperations/deletenearpoints/)(IGeometry, NearPointsCleanerOptions) | حذف النقاط التي تكون قريبة جدًا من بعضها البعض. |
| static [ExtractGeometryCollection](../../aspose.gis.geotools/geometryoperations/extractgeometrycollection/)(VectorLayer) | استخراج مجموعة الهندسة من الطبقة |
| static [GetCenterlineLength](../../aspose.gis.geotools/geometryoperations/getcenterlinelength/#getcenterlinelength_1)(IEnumerable&lt;Point&gt;) | الحصول على طول الخط المركزي |
| static [GetCenterlineLength](../../aspose.gis.geotools/geometryoperations/getcenterlinelength/#getcenterlinelength)(Polygon) | الحصول على طول الخط المركزي |
| static [MakeVoronoiGraph](../../aspose.gis.geotools/geometryoperations/makevoronoigraph/)(IEnumerable&lt;IPoint&gt;) | إنشاء مخطط "Voronoi" لمجموعة من النقاط (المواقع) |
| static [OrderGeometryCollection](../../aspose.gis.geotools/geometryoperations/ordergeometrycollection/)(IGeometry) | ترتيب مجموعة الهندسة حسب النوع إلى أربع مجموعات (نقطة، خط، مضلع ونوع آخر) |
| static [SimplifySegments](../../aspose.gis.geotools/geometryoperations/simplifysegments/)(IGeometry, SimplifySegmentsOptions) | حذف النقاط الواقعة على نفس المقطع. |

## ملاحظات

خوارزميات أخرى يمكنك العثور عليها في طرق [`Geometry`](../../aspose.gis.geometries/geometry/)

### انظر أيضًا

* namespace [Aspose.Gis.GeoTools](../../aspose.gis.geotools/)
* assembly [Aspose.GIS](../../)


