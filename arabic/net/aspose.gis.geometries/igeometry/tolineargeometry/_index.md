---
title: "IGeometry.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحصّل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام التسامح الافتراضي"
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

هندسة لا تحتوي على هندسات منحنية. هذا يعادل `ToLinearGeometry` مع `tolerance` الافتراضي. يتم تعريف `tolerance` الافتراضي بواسطة [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذه الهندسة:  بالنسبة إلى نظام الإحداثيات المُسقَط (SRS) يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5` لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

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
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الشكل المنحني، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الشكل الحد الأقصى لكل ربع حاليًا وهو يساوي 10000 نقطة. |

### قيمة الإرجاع

هندسة لا تحتوي على هندسات منحنية. تم تطبيق التحويلات التالية: يتم تحويل CircularStrings إلى خطية (تحويلها إلى LineStrings مع *tolerance* المحدد) يتم دمج CompoundCurves في `LineString`s يتم تحويل CurvePolygons إلى Polygons يتم تحويل MultiCurves إلى MultiLineStrings يتم تحويل MultiSurfaces إلى MultiPolygons  نتيجةً لذلك، تكون قيمة [`HasCurveGeometry`](../hascurvegeometry/) للهندسة الناتجة `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


