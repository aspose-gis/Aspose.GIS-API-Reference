---
title: "GeometryCollection.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeometryCollection. تحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام التسامح الافتراضي."
type: docs
weight: 220
url: /ar/net/aspose.gis.geometries/geometrycollection/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IGeometryCollection ToLinearGeometry()
```

### قيمة الإرجاع

هندسة لا تحتوي على هندسات منحنية. هذه هي المكافئة لـ [`ToLinearGeometry`](../../igeometrycollection/tolineargeometry/) مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذه الهندسة:  بالنسبة إلى نظام الإحداثيات المُسقَّط (SRS) يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5` للحصول على مزيد من التفاصيل حول التحولات المطبقة راجع مواصفة [`ToLinearGeometry`](../../igeometrycollection/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometryCollection](../../igeometrycollection/)
* class [GeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../geometrycollection/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IGeometryCollection ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المستخدمة. يضمن أن النتيجة أقل من `tolerance` بعيدًا عن الهندسة المنحنية. |

### قيمة الإرجاع

هندسة لا تحتوي على هندسات منحنية. يتم تطبيق التحولات التالية: يتم تحويل CircularStrings إلى خطوط مستقيمة (تحويل إلى LineStrings مع *tolerance* المحدد) يتم دمج CompoundCurves في `LineString`s يتم تحويل CurvePolygons إلى Polygons يتم تحويل MultiCurves إلى MultiCurves يتم تحويل MultiSurfaces إلى MultiPolygons  ونتيجة لذلك، تكون قيمة [`HasCurveGeometry`](../../igeometry/hascurvegeometry/) للهندسة الناتجة `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometryCollection](../../igeometrycollection/)
* class [GeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../geometrycollection/)
* assembly [Aspose.GIS](../../../)


