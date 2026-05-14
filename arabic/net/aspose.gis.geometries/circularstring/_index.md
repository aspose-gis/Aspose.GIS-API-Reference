---
title: "الفئة CircularString"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Geometries.CircularString. منحنى متعدد الرؤوس مع استيفاء دائري بين النقاط."
type: docs
weight: 2660
url: /ar/net/aspose.gis.geometries/circularstring/
---
## CircularString class

منحنى متعدد الرؤوس مع استيفاء دائري بين النقاط.

```csharp
public class CircularString : Curve, ICircularString
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [CircularString](circularstring/#constructor)() | يُنشئ مثيلاً جديداً لفئة `CircularString`. |
| [CircularString](circularstring/#constructor_1)(ICircularString) | يُنشئ مثيلاً جديداً لفئة `CircularString`. |
| [CircularString](circularstring/#constructor_2)(IEnumerable&lt;IPoint&gt;) | يُنشئ مثيلاً جديداً لفئة `CircularString`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا [`Geometry`](../geometry/). |
| [Count](../../aspose.gis.geometries/circularstring/count/) { get; } | يحصل على عدد النقاط في `CircularString`. |
| [Dimension](../../aspose.gis.geometries/curve/dimension/) { get; } | يحصل على البعد الطوبولوجي لهذا [`Geometry`](../geometry/). |
| override [EndPoint](../../aspose.gis.geometries/circularstring/endpoint/) { get; } | يعيد نسخة من نقطة النهاية للمنحنى. |
| override [GeometryType](../../aspose.gis.geometries/circularstring/geometrytype/) { get; } | يحصل على نوع الهندسة. |
| override [HasCurveGeometry](../../aspose.gis.geometries/circularstring/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| [HasM](../../aspose.gis.geometries/circularstring/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية M. |
| [HasZ](../../aspose.gis.geometries/circularstring/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية Z. |
| [IsClosed](../../aspose.gis.geometries/curve/isclosed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المنحنى مغلقاً. يكون المنحنى مغلقاً إذا كانت نقطة البداية مساوية لنقطة النهاية. |
| override [IsEmpty](../../aspose.gis.geometries/circularstring/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| [Item](../../aspose.gis.geometries/circularstring/item/) { get; set; } | يحصل أو يضبط الـ [`IPoint`](../ipoint/) عند الفهرس المحدد. |
| [SpatialReferenceSystem](../../aspose.gis.geometries/circularstring/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذا المثيل. يمكن أن تكون هذه الخاصية `null` إذا لم يتم تعيين SpatialReferenceSystem. تعيين SpatialReferenceSystem جديد لن يقوم بأي تحويل إحداثيات، فقط سيتغير المرجع. |
| override [StartPoint](../../aspose.gis.geometries/circularstring/startpoint/) { get; } | يعيد نسخة من نقطة البداية للمنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint)(IPoint) | يضيف نقطة إلى نهاية السلسلة الدائرية. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_1)(double, double) | يضيف نقطة إلى نهاية السلسلة الدائرية. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_2)(double, double, double) | يضيف نقطة إلى نهاية السلسلة الدائرية. |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_3)(double, double, double, double) | يضيف نقطة إلى نهاية السلسلة الدائرية. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| override [Clone](../../aspose.gis.geometries/circularstring/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [Equals](../../aspose.gis.geometries/circularstring/equals/#equals)(ICircularString) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis.geometries/circularstring/equals/#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetEnumerator](../../aspose.gis.geometries/circularstring/getenumerator/)() | يعيد عدّادًا يتنقل عبر المجموعة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| override [GetHashCode](../../aspose.gis.geometries/circularstring/gethashcode/)() | يعمل كدالة التجزئة الافتراضية. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| override [Reverse](../../aspose.gis.geometries/circularstring/reverse/)() | يعكس ترتيب النقاط في هذا `CircularString`. |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| override [SetEmpty](../../aspose.gis.geometries/circularstring/setempty/)() | يجعل هذا [`Geometry`](../geometry/) فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكافئة مكانيًا لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/circularstring/toeditable/#toeditable)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. (3 طرق) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذا الشكل باستخدام `tolerance` الافتراضي. (طريقتان) |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذا الشكل باستخدام `tolerance` المحدد. (طريقتان) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يترجم هذا الشكل إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كان هذا الشكل وشكل محدد يلامسان بعضهما. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذا الشكل وشكلًا محددًا. |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | يحدد ما إذا كان هذا الشكل داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | يحدد ما إذا كان هذا الشكل داخل شكل محدد. |
| [operator ==](../../aspose.gis.geometries/circularstring/op_equality/) | ينفذ العامل ==. |
| [operator !=](../../aspose.gis.geometries/circularstring/op_inequality/) | ينفذ العامل !=. |

## ملاحظات

يتكون `CircularString` من مقطع أو أكثر من أقواس دائرية متصلة من النهاية إلى النهاية. تحدد النقاط الثلاث الأولى المقطع الأول. النقطة الأولى هي نقطة بداية القوس. النقطة الثانية هي أي نقطة وسيطة على القوس غير نقطة البداية أو النهاية. النقطة الثالثة هي نهاية القوس. يتم تعريف الأقواس اللاحقة بنقاطها الوسيطة ونقاط النهاية فقط، حيث تُعرّف نقطة البداية ضمنياً كنقطة نهاية المقطع السابق.

### انظر أيضًا

* class [Curve](../curve/)
* interface [ICircularString](../icircularstring/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


