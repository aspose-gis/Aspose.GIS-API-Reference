---
title: "IGeometryCollection.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometryCollection. يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 60
url: /ar/net/aspose.gis.geometries/igeometrycollection/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IGeometryCollection ToLinearGeometry()
```

### قيمة الإرجاع

‏شكل هندسي لا يحتوي على أشكال منحنية. هذا هو المكافئ لـ `ToLinearGeometry` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي:  بالنسبة إلى نظام الإحداثيات المُسقَّط (SRS) يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5` للمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../igeometrycollection/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IGeometryCollection ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

هندسة لا تحتوي على هندسات منحنية. يتم تطبيق التحولات التالية: يتم تحويل CircularStrings إلى خطوط مستقيمة (تحويل إلى LineStrings مع *tolerance* المحدد) يتم دمج CompoundCurves في `LineString`s يتم تحويل CurvePolygons إلى Polygons يتم تحويل MultiCurves إلى MultiCurves يتم تحويل MultiSurfaces إلى MultiPolygons  ونتيجة لذلك، تكون قيمة [`HasCurveGeometry`](../../igeometry/hascurvegeometry/) للهندسة الناتجة `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../igeometrycollection/)
* assembly [Aspose.GIS](../../../)


