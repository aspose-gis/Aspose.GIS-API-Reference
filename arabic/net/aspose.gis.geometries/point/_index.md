---
title: "الفئة Point"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Geometries.Point فئة. النقطة تمثل موقعًا واحدًا في فضاء الإحداثيات"
type: docs
weight: 2970
url: /ar/net/aspose.gis.geometries/point/
---
## Point class

النقطة `Point` تمثل موقعًا واحدًا في فضاء الإحداثيات.

```csharp
public class Point : Geometry, IPoint
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Point](point/#constructor)() | يُنشئ مثيلًا جديدًا من فئة `Point`. |
| [Point](point/#constructor_1)(IPoint) | يُنشئ مثيلًا جديدًا من فئة `Point`. |
| [Point](point/#constructor_2)(double, double) | يُنشئ مثيلًا جديدًا من فئة `Point`. |
| [Point](point/#constructor_3)(double, double, double) | يُنشئ مثيلًا جديدًا من فئة `Point`. |
| [Point](point/#constructor_4)(double, double, double, double) | يُنشئ مثيلًا جديدًا من فئة `Point`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا [`Geometry`](../geometry/). |
| override [Dimension](../../aspose.gis.geometries/point/dimension/) { get; } | يحصل على البعد الطوبولوجي لهذا [`Geometry`](../geometry/). |
| override [GeometryType](../../aspose.gis.geometries/point/geometrytype/) { get; } | يحصل على نوع الهندسة. |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| override [HasM](../../aspose.gis.geometries/point/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان لهذا المثيل إحداثي M. |
| override [HasZ](../../aspose.gis.geometries/point/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية Z. |
| virtual [IsEmpty](../../aspose.gis.geometries/geometry/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| [M](../../aspose.gis.geometries/point/m/) { get; set; } | يحصل أو يعيّن قيمة لإحداثي m. |
| override [SpatialReferenceSystem](../../aspose.gis.geometries/point/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذا الكائن. يمكن أن تكون هذه الخاصية `null` إذا كان SpatialReferenceSystem غير معروف. تعيين SpatialReferenceSystem جديد لن يؤدي إلى أي تحويل إحداثيات، بل سيتغير المرجع فقط. |
| [X](../../aspose.gis.geometries/point/x/) { get; set; } | يحصل أو يعيّن قيمة لإحداثي x. |
| [Y](../../aspose.gis.geometries/point/y/) { get; set; } | يحصل أو يعيّن قيمة لإحداثي y. |
| [Z](../../aspose.gis.geometries/point/z/) { get; set; } | يحصل أو يعيّن قيمة لإحداثي z. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| override [Clone](../../aspose.gis.geometries/point/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [Equals](../../aspose.gis.geometries/point/equals/#equals)(IPoint) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis.geometries/point/equals/#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| override [GetHashCode](../../aspose.gis.geometries/point/gethashcode/)() | يعمل كدالة التجزئة الافتراضية. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| override [SetEmpty](../../aspose.gis.geometries/point/setempty/)() | يجعل هذا [`Geometry`](../geometry/) فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكافئة مكانيًا لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/point/toeditable/#toeditable_1)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. (طريقتان) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يترجم هذا الشكل إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كان هذا الشكل وشكل محدد يلامسان بعضهما. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذا الشكل وشكلًا محددًا. |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | يحدد ما إذا كان هذا الشكل داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | يحدد ما إذا كان هذا الشكل داخل شكل محدد. |
| [operator ==](../../aspose.gis.geometries/point/op_equality/) | ينفذ العامل ==. |
| [operator !=](../../aspose.gis.geometries/point/op_inequality/) | ينفذ العامل !=. |

### انظر أيضًا

* class [Geometry](../geometry/)
* interface [IPoint](../ipoint/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


