---
title: "Geometry.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التسامح الافتراضي"
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

شكل هندسي لا يحتوي على أشكال منحنية. هذا هو ما يعادل [`ToLinearGeometry`](../../igeometry/tolineargeometry/) مع `tolerance` الافتراضي. `tolerance` الافتراضي يُعرّف بواسطة [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل الهندسي:  بالنسبة إلى نظام الإسناد المكاني (SRS) المُسقَّط يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإسناد المكاني الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إسناد غير معروف يكون التسامح `1e-5` للمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات [`ToLinearGeometry`](../../igeometry/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

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
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الشكل المنحني، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الشكل الحد الأقصى لكل ربع حاليًا وهو يساوي 10000 نقطة. |

### قيمة الإرجاع

شكل هندسي لا يحتوي على أشكال منحنية. التحويلات التالية تُطبق: يتم تقويم CircularStrings (تحويلها إلى LineStrings مع *tolerance* المحدد) تُدمج CompoundCurves في `LineString`s تُحول CurvePolygons إلى Polygons تُحول MultiCurves إلى MultiLineStrings تُحول MultiSurfaces إلى MultiPolygons  نتيجة لذلك، تكون قيمة [`HasCurveGeometry`](../../igeometry/hascurvegeometry/) للشكل الناتج `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


