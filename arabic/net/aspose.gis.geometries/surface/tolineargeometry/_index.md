---
title: "Surface.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Surface. يحصل على نسخة تقريبية أو مكافئة غير منحنى لهذه الهندسة باستخدام التسامح الافتراضي"
type: docs
weight: 40
url: /ar/net/aspose.gis.geometries/surface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IPolygon ToLinearGeometry()
```

### قيمة الإرجاع

`[`IPolygon`](../../ipolygon/)` الذي يقرّب أو يعادل هذا `ISurface`. هذا هو المكافئ لـ[`ToLinearGeometry`](../../isurface/tolineargeometry/) مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذه الهندسة:  بالنسبة إلى SRS المُسقطة يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى SRS الجغرافية يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى SRS غير المعروفة يكون التسامح `1e-5` للحصول على مزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات [`ToLinearGeometry`](../../isurface/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IPolygon](../../ipolygon/)
* class [Surface](../)
* namespace [Aspose.Gis.Geometries](../../surface/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IPolygon ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

‏[`IPolygon`](../../ipolygon/) تقريبية أو مكافئة لهذا `ISurface`: إذا كان هذا الكائن هو [`IPolygon`](../../ipolygon/) نفسه فإن النتيجة تكون مكافئة لهذا الكائن. إذا لم يكن هذا الكائن [`IPolygon`](../../ipolygon/) يتم تقويمه وإنشاء [`IPolygon`](../../ipolygon/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IPolygon](../../ipolygon/)
* class [Surface](../)
* namespace [Aspose.Gis.Geometries](../../surface/)
* assembly [Aspose.GIS](../../../)


