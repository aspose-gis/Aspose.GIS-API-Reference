---
title: "MultiCurve.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة MultiCurve. تحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام التسامح المحدد"
type: docs
weight: 70
url: /ar/net/aspose.gis.geometries/multicurve/tolineargeometry/
---
## ToLinearGeometry(double) {#tolineargeometry_5}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

ـ[`IMultiLineString`](../../imultilinestring/) التي تقرب أو تعادل هذا [`IMultiCurve`](../../imulticurve/): إذا كان هذا الكائن هو نفسه [`IMultiLineString`](../../imultilinestring/) فإن النتيجة تعادل هذا الكائن. إذا لم يكن هذا الكائن هو [`IMultiLineString`](../../imultilinestring/) - يتم تحويل جميع المنحنيات إلى خطية ويتم إنشاء `IMultiLineString` جديد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiLineString](../../imultilinestring/)
* class [MultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../multicurve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry() {#tolineargeometry_4}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IMultiLineString ToLinearGeometry()
```

### قيمة الإرجاع

ـ[`IMultiLineString`](../../imultilinestring/) التي تقرب أو تعادل هذا [`IMultiCurve`](../../imulticurve/). هذه هي المكافئة لـ[`ToLinearGeometry`](../../imulticurve/tolineargeometry/) مع `tolerance` الافتراضية. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذه الهندسة: بالنسبة إلى SRS الإسقاطية يكون التسامح 0.001 متر (بوحدات SRS) بالنسبة إلى SRS الجغرافية يكون التسامح `1e-5` درجة (بوحدات SRS) بالنسبة إلى SRS غير المعروفة يكون التسامح `1e-5`. لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة [`ToLinearGeometry`](../../imulticurve/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiLineString](../../imultilinestring/)
* class [MultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../multicurve/)
* assembly [Aspose.GIS](../../../)


