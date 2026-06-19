---
title: "الواجهة IGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Geometries.IGeometry. الفئة الجذرية للواجهة في هرمية Geometries"
type: docs
weight: 2780
url: /ar/net/aspose.gis.geometries/igeometry/
---
## IGeometry interface

فئة الجذر للواجهة في تسلسل هرمية الأشكال الهندسية

```csharp
public interface IGeometry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Dimension](../../aspose.gis.geometries/igeometry/dimension/) { get; } | يحصل على البُعد الطوبولوجي لهذا `IGeometry`. إذا كان البُعد غير معروف (مثلاً لمجموعة GEOMETRYCOLLECTION فارغة) يتم إرجاع Point. |
| [GeometryType](../../aspose.gis.geometries/igeometry/geometrytype/) { get; } | يحصل على نوع الـ geometry. |
| [HasCurveGeometry](../../aspose.gis.geometries/igeometry/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الـ geometry هي أو تحتوي على هندسة منحنية (غير خطية). |
| [HasM](../../aspose.gis.geometries/igeometry/hasm/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي M. |
| [HasZ](../../aspose.gis.geometries/igeometry/hasz/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي Z. |
| [IsEmpty](../../aspose.gis.geometries/igeometry/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل فارغًا (يمثل مجموعة نقاط فارغة). |
| [IsSimple](../../aspose.gis.geometries/igeometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/igeometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| [SpatialReferenceSystem](../../aspose.gis.geometries/igeometry/spatialreferencesystem/) { get; } | يحصل على نظام الإحداثيات المكاني (SpatialReferenceSystem) لهذا المثيل. يمكن أن تكون هذه الخاصية `null` إذا كان نظام الإحداثيات غير معروف. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AsBinary](../../aspose.gis.geometries/igeometry/asbinary/#asbinary)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsBinary](../../aspose.gis.geometries/igeometry/asbinary/#asbinary_1)(WkbVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage_1)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage_2)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext_1)(WktVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext_2)(WktVariant, NumericFormat) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [Clone](../../aspose.gis.geometries/igeometry/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/igeometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/igeometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/igeometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/igeometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/igeometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [GetArea](../../aspose.gis.geometries/igeometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/igeometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/igeometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/igeometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/igeometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetExtent](../../aspose.gis.geometries/igeometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [GetLength](../../aspose.gis.geometries/igeometry/getlength/)() | يحسب طول هذه الهندسة. |
| [Intersection](../../aspose.gis.geometries/igeometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/igeometry/intersects/#intersects)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/igeometry/intersects/#intersects_1)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/igeometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/igeometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [SpatiallyContains](../../aspose.gis.geometries/igeometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/igeometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكانيًا مساوية لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/igeometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/igeometry/toeditable/#toeditable)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/igeometry/toeditable/#toeditable_1)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometry/tolineargeometry/#tolineargeometry)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometry/tolineargeometry/#tolineargeometry_1)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. |
| [Touches](../../aspose.gis.geometries/igeometry/touches/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [Union](../../aspose.gis.geometries/igeometry/union/)(IGeometry) | يوحد هذه الهندسة وهندسة محددة. |
| [Within](../../aspose.gis.geometries/igeometry/within/#within)(Extent) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/igeometry/within/#within_1)(IGeometry) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |

### انظر أيضًا

* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


