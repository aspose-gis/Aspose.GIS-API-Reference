---
title: "Curve.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Curve. تحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 70
url: /ar/net/aspose.gis.geometries/curve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public ILineString ToLinearGeometry()
```

### قيمة الإرجاع

[`ILineString`](../../ilinestring/) التي تقرب أو تعادل هذا المنحنى. هذا هو المكافئ لـ [`ToLinearGeometry`](../../icurve/tolineargeometry/) مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي:  لـ SRS المُسقَّط يكون التسامح 0.001 متر (بوحدات SRS)  لـ SRS الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS)  لـ SRS غير معروف يكون التسامح `1e-5` لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات [`ToLinearGeometry`](../../icurve/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [ILineString](../../ilinestring/)
* class [Curve](../)
* namespace [Aspose.Gis.Geometries](../../curve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

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
* class [Curve](../)
* namespace [Aspose.Gis.Geometries](../../curve/)
* assembly [Aspose.GIS](../../../)


