---
title: "ICurve.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ICurve. تحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 50
url: /ar/net/aspose.gis.geometries/icurve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public ILineString ToLinearGeometry()
```

### قيمة الإرجاع

[`ILineString`](../../ilinestring/) التي تقرب أو تعادل هذه المنحنى. هذا هو ما يعادل `ToLinearGeometry` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي: بالنسبة إلى نظام الإحداثيات المُسقَّط (SRS) يكون التسامح 0.001 متر (بوحدات SRS) بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التسامح `1e-5` درجة (بوحدات SRS) بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5` لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [ILineString](../../ilinestring/)
* interface [ICurve](../)
* namespace [Aspose.Gis.Geometries](../../icurve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public ILineString ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` للاستخدام. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

[`ILineString`](../../ilinestring/) التي تقرب أو تعادل هذا المنحنى: إذا كان هذا الكائن هو [`ILineString`](../../ilinestring/) نفسه فإن النتيجة تعادل هذا الكائن. إذا كان هذا الكائن هو [`ICircularString`](../../icircularstring/) فإن النتيجة هي السلسلة الدائرية المُخطَّطة بالتسامح المحدد *tolerance*. إذا كان هذا الكائن هو [`ICompoundCurve`](../../icompoundcurve/) - جميع المنحنيات منه تُخطَّط ثم تُدمج في [`ILineString`](../../ilinestring/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [ILineString](../../ilinestring/)
* interface [ICurve](../)
* namespace [Aspose.Gis.Geometries](../../icurve/)
* assembly [Aspose.GIS](../../../)


