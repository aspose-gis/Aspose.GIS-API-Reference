---
title: "الفئة Polygon"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Geometries.Polygon. الـ Polygon هو سطح مستوي يُعرّف بحد خارجي واحد و0 أو أكثر من الحدود الداخلية"
type: docs
weight: 2980
url: /ar/net/aspose.gis.geometries/polygon/
---
## Polygon class

الـ `Polygon` هو سطح مستوي، يُعرّف بحد خارجي واحد و0 أو أكثر من الحدود الداخلية.

```csharp
public class Polygon : Surface, IPolygon
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Polygon](polygon/#constructor)() | يُنشئ مثلاً جديداً من الفئة `Polygon`. |
| [Polygon](polygon/#constructor_1)(ILinearRing) | يُنشئ مثلاً جديداً من الفئة `Polygon`. |
| [Polygon](polygon/#constructor_2)(ILinearRing, IEnumerable&lt;ILinearRing&gt;) | يُنشئ مثلاً جديداً من الفئة `Polygon`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا [`Geometry`](../geometry/). |
| [Dimension](../../aspose.gis.geometries/surface/dimension/) { get; } | يحصل على البعد الطوبولوجي لهذا [`Geometry`](../geometry/). |
| [ExteriorRing](../../aspose.gis.geometries/polygon/exteriorring/) { get; set; } | يحصل على الحلقة الخارجية. |
| override [GeometryType](../../aspose.gis.geometries/polygon/geometrytype/) { get; } | يحصل على نوع الـ geometry. |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الـ geometry هي أو تحتوي على هندسة منحنية (غير خطية). |
| override [HasM](../../aspose.gis.geometries/polygon/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي M. |
| override [HasZ](../../aspose.gis.geometries/polygon/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي Z. |
| [InteriorRingsCount](../../aspose.gis.geometries/polygon/interiorringscount/) { get; } | يحصل على عدد الحلقات الداخلية. |
| override [IsEmpty](../../aspose.gis.geometries/polygon/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| override [SpatialReferenceSystem](../../aspose.gis.geometries/polygon/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذا الكائن. يمكن أن تكون هذه الخاصية `null` إذا كان SpatialReferenceSystem غير معروف. تعيين SpatialReferenceSystem جديد لن يؤدي إلى أي تحويل إحداثيات، بل سيتغير المرجع فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInteriorRing](../../aspose.gis.geometries/polygon/addinteriorring/)(ILinearRing) | يضيف حلقة داخلية. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| override [Clone](../../aspose.gis.geometries/polygon/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [Equals](../../aspose.gis.geometries/polygon/equals/#equals)(ICurvePolygon) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [Equals](../../aspose.gis.geometries/polygon/equals/#equals_1)(IPolygon) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| override [Equals](../../aspose.gis.geometries/polygon/equals/#equals_2)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| override [GetHashCode](../../aspose.gis.geometries/polygon/gethashcode/)() | يعمل كدالة تجزئة افتراضية. |
| [GetInteriorRing](../../aspose.gis.geometries/polygon/getinteriorring/)(int) | يحصل على الحلقة الداخلية حسب فهرستها. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| override [GetPointOnSurface](../../aspose.gis.geometries/polygon/getpointonsurface/)() | يجد نقطة مضمونة أن تكون على هذا المضلع. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| override [SetEmpty](../../aspose.gis.geometries/polygon/setempty/)() | يجعل هذا [`Geometry`](../geometry/) فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكانيًا مساوية لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/polygon/toeditable/#toeditable_1)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. (3 طرق) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/surface/tolineargeometry/)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. (2 طرق) |
| [ToLinearGeometry](../../aspose.gis.geometries/surface/tolineargeometry/)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. (2 طرق) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يحوّل هذه الهندسة إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذه الهندسة وهندسة محددة. |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |
| [operator ==](../../aspose.gis.geometries/polygon/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.gis.geometries/polygon/op_inequality/) | ينفّذ العامل !=. |

### انظر أيضًا

* class [Surface](../surface/)
* interface [IPolygon](../ipolygon/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


