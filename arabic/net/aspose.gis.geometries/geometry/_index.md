---
title: "الفئة Geometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Geometries.Geometry. الفئة الجذرية المجردة لهرمية الأشكال الهندسية"
type: docs
weight: 2700
url: /ar/net/aspose.gis.geometries/geometry/
---
## Geometry class

الفئة الجذرية المجردة لتسلسل الهرمية الهندسية.

```csharp
public abstract class Geometry : IGeometry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا `Geometry`. |
| abstract [Dimension](../../aspose.gis.geometries/geometry/dimension/) { get; } | يحصل على البُعد الطوبولوجي لهذا `Geometry`. إذا كان البُعد غير معروف (مثلاً لمجموعة GEOMETRYCOLLECTION فارغة) يتم إرجاع Point. |
| abstract [GeometryType](../../aspose.gis.geometries/geometry/geometrytype/) { get; } | يحصل على نوع الـ geometry. |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الـ geometry هي أو تحتوي على هندسة منحنية (غير خطية). |
| virtual [HasM](../../aspose.gis.geometries/geometry/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي M. |
| virtual [HasZ](../../aspose.gis.geometries/geometry/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي Z. |
| virtual [IsEmpty](../../aspose.gis.geometries/geometry/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| abstract [SpatialReferenceSystem](../../aspose.gis.geometries/geometry/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذا الكائن. يمكن أن تكون هذه الخاصية `null` إذا كان SpatialReferenceSystem غير معروف. تعيين SpatialReferenceSystem جديد لن يؤدي إلى أي تحويل إحداثيات، بل سيتغير المرجع فقط. |
| static [Null](../../aspose.gis.geometries/geometry/null/) { get; } | يحصل على مثيل من الشكل الهندسي الفارغ (null). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/#asbinary)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/#asbinary_1)(WkbVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage_1)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage_2)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext_1)(WktVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext_2)(WktVariant, NumericFormat) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| abstract [Clone](../../aspose.gis.geometries/geometry/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/#intersects)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/#intersects_1)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| virtual [SetEmpty](../../aspose.gis.geometries/geometry/setempty/)() | يجعل هذا `Geometry` فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكانيًا مساوية لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/geometry/toeditable/#toeditable)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/#toeditable_1)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/#tolineargeometry)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/#tolineargeometry_1)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يحوّل هذه الهندسة إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذه الهندسة وهندسة محددة. |
| [Within](../../aspose.gis.geometries/geometry/within/#within)(Extent) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/#within_1)(IGeometry) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |
| static [FromBinary](../../aspose.gis.geometries/geometry/frombinary/#frombinary)(byte[]) | ينشئ شكلًا هندسيًا من تمثيله الثنائي المعروف (Well-Known Binary). |
| static [FromBinary](../../aspose.gis.geometries/geometry/frombinary/#frombinary_1)(byte[], SpatialReferenceSystem) | ينشئ شكلًا هندسيًا من تمثيله الثنائي المعروف (Well-Known Binary). |
| static [FromText](../../aspose.gis.geometries/geometry/fromtext/#fromtext)(string) | ينشئ شكلًا هندسيًا من تمثيله النصي المعروف (Well-Known Text). |
| static [FromText](../../aspose.gis.geometries/geometry/fromtext/#fromtext_1)(string, SpatialReferenceSystem) | ينشئ شكلًا هندسيًا من تمثيله النصي المعروف (Well-Known Text). |

### انظر أيضًا

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


