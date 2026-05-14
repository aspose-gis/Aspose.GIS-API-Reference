---
title: "Geometry.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام التسامح الافتراضي"
type: docs
weight: 400
url: /ar/net/aspose.gis.geometries/geometry/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IGeometry ToLinearGeometry()
```

### قيمة الإرجاع

هندسة لا تحتوي على هندسات منحنية. هذا ما يعادل [`ToLinearGeometry`](../../igeometry/tolineargeometry/) مع `tolerance` الافتراضي. يتم تعريف `tolerance` الافتراضي بواسطة [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذه الهندسة: بالنسبة لنظام الإسناد المكاني (SRS) المُسقَّط يكون التسامح 0.001 متر (بوحدات SRS) بالنسبة لنظام الإسناد المكاني الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS) بالنسبة لنظام الإسناد المكاني غير المعروف يكون التسامح `1e-5` للحصول على مزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات [`ToLinearGeometry`](../../igeometry/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
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

هندسة لا تحتوي على هندسات منحنية. يتم تطبيق التحويلات التالية: يتم تقويم CircularStrings (تحويلها إلى LineStrings مع *tolerance* المحدد) يتم دمج CompoundCurves في `LineString`s يتم تحويل CurvePolygons إلى Polygons يتم تحويل MultiCurves إلى MultiLineStrings يتم تحويل MultiSurfaces إلى MultiPolygons نتيجة لذلك، تكون قيمة [`HasCurveGeometry`](../../igeometry/hascurvegeometry/) للهندسة الناتجة `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


