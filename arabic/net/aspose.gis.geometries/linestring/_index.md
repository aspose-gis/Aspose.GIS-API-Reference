---
title: "الفئة LineString"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Geometries.LineString. خط متعدد الرؤوس"
type: docs
weight: 2900
url: /ar/net/aspose.gis.geometries/linestring/
---
## LineString class

خط متعدد الرؤوس.

```csharp
public class LineString : Curve, ILineString
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LineString](linestring/#constructor)() | ينشئ مثيلاً جديداً من الفئة `LineString`. |
| [LineString](linestring/#constructor_2)(IEnumerable&lt;IPoint&gt;) | ينشئ مثيلاً جديداً من الفئة `LineString`. |
| [LineString](linestring/#constructor_1)(ILineString) | ينشئ مثيلاً جديداً من الفئة `LineString`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا [`Geometry`](../geometry/). |
| [Count](../../aspose.gis.geometries/linestring/count/) { get; } | يحصل على عدد النقاط في `LineString`. |
| [Dimension](../../aspose.gis.geometries/curve/dimension/) { get; } | يحصل على البعد الطوبولوجي لهذا [`Geometry`](../geometry/). |
| override [EndPoint](../../aspose.gis.geometries/linestring/endpoint/) { get; } | يعيد نسخة من نقطة النهاية للمنحنى. |
| override [GeometryType](../../aspose.gis.geometries/linestring/geometrytype/) { get; } | يحصل على نوع الـ geometry. |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الـ geometry هي أو تحتوي على هندسة منحنية (غير خطية). |
| [HasM](../../aspose.gis.geometries/linestring/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي M. |
| [HasZ](../../aspose.gis.geometries/linestring/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي Z. |
| [IsClosed](../../aspose.gis.geometries/curve/isclosed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المنحنى مغلقًا. يكون المنحنى مغلقًا إذا كانت نقطة البداية مساوية لنقطة النهاية. |
| override [IsEmpty](../../aspose.gis.geometries/linestring/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| [Item](../../aspose.gis.geometries/linestring/item/) { get; set; } | يحصل أو يعيّن الـ [`IPoint`](../ipoint/) عند الفهرس المحدد. |
| [SpatialReferenceSystem](../../aspose.gis.geometries/linestring/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذه المثيلة. يمكن أن تكون هذه الخاصية `null` إذا لم يتم تعيين SpatialReferenceSystem. تعيين SpatialReferenceSystem جديد لن يؤدي إلى أي تحويل إحداثي، بل سيتغير المرجع فقط. |
| override [StartPoint](../../aspose.gis.geometries/linestring/startpoint/) { get; } | يعيد نسخة من نقطة البداية للمنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint/#addpoint)(IPoint) | يضيف نقطة إلى نهاية الخط. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint/#addpoint_1)(double, double) | يضيف نقطة إلى نهاية الخط. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint/#addpoint_2)(double, double, double) | يضيف نقطة إلى نهاية الخط. |
| [AddPoint](../../aspose.gis.geometries/linestring/addpoint/#addpoint_3)(double, double, double, double) | يضيف نقطة إلى نهاية الخط. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| override [Clone](../../aspose.gis.geometries/linestring/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [Equals](../../aspose.gis.geometries/linestring/equals/#equals)(ILineString) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis.geometries/linestring/equals/#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetEnumerator](../../aspose.gis.geometries/linestring/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| override [GetHashCode](../../aspose.gis.geometries/linestring/gethashcode/)() | يعمل كدالة تجزئة افتراضية. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| override [Reverse](../../aspose.gis.geometries/linestring/reverse/)() | يعكس ترتيب النقاط في هذا `LineString`. |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| override [SetEmpty](../../aspose.gis.geometries/linestring/setempty/)() | يجعل هذا [`Geometry`](../geometry/) فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكانيًا مساوية لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/linestring/toeditable/#toeditable_2)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. (3 طرق) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. (2 طرق) |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. (2 طرق) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يحوّل هذه الهندسة إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذه الهندسة وهندسة محددة. |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |
| [operator ==](../../aspose.gis.geometries/linestring/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.gis.geometries/linestring/op_inequality/) | ينفّذ العامل !=. |

### انظر أيضًا

* class [Curve](../curve/)
* interface [ILineString](../ilinestring/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


