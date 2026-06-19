---
title: "IMultiCurve.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IMultiCurve. يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التحمل الافتراضي"
type: docs
weight: 20
url: /ar/net/aspose.gis.geometries/imulticurve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IMultiLineString ToLinearGeometry()
```

### قيمة الإرجاع

`[`IMultiLineString`](../../imultilinestring/)` الذي يقترب أو يعادل هذا [`IMultiCurve`](../). هذا هو المكافئ لـ `ToLinearGeometry` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي:  بالنسبة إلى نظام الإحداثيات المسقط (SRS) يكون التحمل 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التحمل `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التحمل `1e-5`. للمزيد من التفاصيل حول التحولات المطبقة راجع مواصفات `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiLineString](../../imultilinestring/)
* interface [IMultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../imulticurve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

`[`IMultiLineString`](../../imultilinestring/)` الذي يقترب أو يعادل هذا [`IMultiCurve`](../): إذا كان هذا الكائن هو [`IMultiLineString`](../../imultilinestring/) نفسه فإن النتيجة مكافئة لهذا الكائن. إذا لم يكن هذا الكائن هو [`IMultiLineString`](../../imultilinestring/) - يتم تحويل جميع المنحنيات إلى خطية ويتم إنشاء `IMultiLineString` جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiLineString](../../imultilinestring/)
* interface [IMultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../imulticurve/)
* assembly [Aspose.GIS](../../../)


