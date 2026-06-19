---
title: "الفئة MultiPoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Geometries.MultiPoint. الـ MultiPoint هو مجموعة GeometryCollection أحادية البعد تحتوي عناصرها على Points"
type: docs
weight: 2940
url: /ar/net/aspose.gis.geometries/multipoint/
---
## MultiPoint class

الـ `MultiPoint` هو مجموعة [`GeometryCollection`](../geometrycollection/) أحادية البعد تحتوي عناصرها على [`Point`](../point/)s.

```csharp
public class MultiPoint : GeometryCollection, IMultiPoint
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MultiPoint](multipoint/)() | يُنشئ مثلاً جديداً من الفئة `MultiPoint`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | يحصل على عدد أبعاد الإحداثيات لهذا [`Geometry`](../geometry/). |
| [Count](../../aspose.gis.geometries/geometrycollection/count/) { get; } | يحصل على عدد الهندسات في هذه المجموعة. |
| [Dimension](../../aspose.gis.geometries/multipoint/dimension/) { get; } | يحصل على البعد الطوبولوجي لهذا [`Geometry`](../geometry/). |
| override [GeometryType](../../aspose.gis.geometries/multipoint/geometrytype/) { get; } | يحصل على نوع الـ geometry. |
| override [HasCurveGeometry](../../aspose.gis.geometries/geometrycollection/hascurvegeometry/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه الـ geometry هي أو تحتوي على هندسة منحنية (غير خطية). |
| override [HasM](../../aspose.gis.geometries/geometrycollection/hasm/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي M. |
| override [HasZ](../../aspose.gis.geometries/geometrycollection/hasz/) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثي Z. |
| override [IsEmpty](../../aspose.gis.geometries/geometrycollection/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| [Item](../../aspose.gis.geometries/geometrycollection/item/) { get; } | يحصل على [`IGeometry`](../igeometry/) في الفهرس المحدد. |
| override [SpatialReferenceSystem](../../aspose.gis.geometries/geometrycollection/spatialreferencesystem/) { get; set; } | يحصل على SpatialReferenceSystem لهذا الكائن. يمكن أن تكون هذه الخاصية `null` إذا كان SpatialReferenceSystem غير معروف. تعيين SpatialReferenceSystem جديد لن يؤدي إلى أي تحويل إحداثيات، بل سيتغير المرجع فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.gis.geometries/geometrycollection/add/)(IGeometry) | يضيف الهندسة المحددة إلى المجموعة. |
| [AddRange](../../aspose.gis.geometries/geometrycollection/addrange/)(IEnumerable&lt;IGeometry&gt;) | يضيف الهندسات المحددة إلى المجموعة. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | يصدّر هذه الـ geometry إلى تمثيل صورة. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها. |
| override [Clone](../../aspose.gis.geometries/multipoint/clone/)() | ينسخ هذا الكائن. |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة. |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة. |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع. |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | يطرح هندسة محددة من هذه الهندسة. |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [Equals](../../aspose.gis.geometries/geometrycollection/equals/)(IGeometryCollection) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis.geometries/geometrycollection/equals/)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | يحسب مساحة هذه الهندسة. |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | يحسب منطقة عازلة حول هذه الهندسة. |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | يحسب مركز الثقل لهذه الهندسة. |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | يحسب الغلاف المحدب لهذه الهندسة. |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [GetEnumerator](../../aspose.gis.geometries/geometrycollection/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| override [GetHashCode](../../aspose.gis.geometries/geometrycollection/gethashcode/)() | يعمل كدالة تجزئة افتراضية. |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | يحسب طول هذه الهندسة. |
| [GetPointOnSurface](../../aspose.gis.geometries/geometrycollection/getpointonsurface/)() | يجد نقطة مضمونة أن تكون على أحد الأسطح في هذه المجموعة. |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [RemoveAt](../../aspose.gis.geometries/geometrycollection/removeat/)(int) | يزيل الهندسة المحددة من المجموعة. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometrycollection/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. (2 طرق) |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| override [SetEmpty](../../aspose.gis.geometries/geometrycollection/setempty/)() | يجعل هذا [`Geometry`](../geometry/) فارغًا. |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة مكانيًا مساوية لهندسة محددة. |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [ToEditable](../../aspose.gis.geometries/multipoint/toeditable/#toeditable_2)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. (3 طرق) |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/geometrycollection/tolineargeometry/)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. (2 طرق) |
| [ToLinearGeometry](../../aspose.gis.geometries/geometrycollection/tolineargeometry/)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. (2 طرق) |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | يحوّل هذه الهندسة إلى تمثيل Svg. |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | يوحد هذه الهندسة وهندسة محددة. |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |

### انظر أيضًا

* class [GeometryCollection](../geometrycollection/)
* interface [IMultiPoint](../imultipoint/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


