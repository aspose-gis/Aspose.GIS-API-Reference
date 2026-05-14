---
title: "IGeometry.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل باستخدام التسامح الافتراضي"
type: docs
weight: 350
url: /ar/net/aspose.gis.geometries/igeometry/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IGeometry ToLinearGeometry()
```

### قيمة الإرجاع

شكل لا يحتوي على أشكال منحنية. هذا يعادل `ToLinearGeometry` مع `tolerance` الافتراضي. `tolerance` الافتراضي يتم تعريفه بواسطة [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا الشكل: بالنسبة إلى SRS المُسقطة يكون التسامح 0.001 متر (بوحدات SRS) بالنسبة إلى SRS الجغرافية يكون التسامح `1e-5` درجة (بوحدات SRS) بالنسبة إلى SRS غير المعروفة يكون التسامح `1e-5` لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IGeometry ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المستخدمة. يتم ضمان أن النتيجة أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

شكل لا يحتوي على أشكال منحنية. التحويلات التالية تُطبق: يتم تحويل CircularStrings إلى شكل خطي (تحويل إلى LineStrings مع *tolerance* المحدد) يتم دمج CompoundCurves في `LineString`s يتم تحويل CurvePolygons إلى Polygons يتم تحويل MultiCurves إلى MultiLineStrings يتم تحويل MultiSurfaces إلى MultiPolygons نتيجةً لذلك، [`HasCurveGeometry`](../hascurvegeometry/) للشكل الناتج هو `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


