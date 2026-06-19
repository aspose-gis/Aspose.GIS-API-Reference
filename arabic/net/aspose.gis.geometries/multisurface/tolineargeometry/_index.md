---
title: "MultiSurface.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة MultiSurface. تحصل على نسخة تقريبية أو مكافئة غير منحنية من هذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 60
url: /ar/net/aspose.gis.geometries/multisurface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_4}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IMultiPolygon ToLinearGeometry()
```

### قيمة الإرجاع

`[`IMultiPolygon`](../../imultipolygon/)` الذي يقترب أو يعادل هذا `[`IMultiSurface`](../../imultisurface/). هذا هو ما يعادل `[`ToLinearGeometry`](../../imultisurface/tolineargeometry/)` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على `[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)` لهذا الشكل الهندسي:  بالنسبة إلى نظام الإحداثيات الإسقاطي (SRS) يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5`. للمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة `[`ToLinearGeometry`](../../imultisurface/tolineargeometry/)`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiPolygon](../../imultipolygon/)
* class [MultiSurface](../)
* namespace [Aspose.Gis.Geometries](../../multisurface/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_5}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IMultiPolygon ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

`[`IMultiPolygon`](../../imultipolygon/)` الذي يقترب أو يعادل هذا `[`IMultiSurface`](../../imultisurface/):  إذا كان هذا الكائن هو نفسه `[`IMultiPolygon`](../../imultipolygon/)` فإن النتيجة تعادل هذا الكائن. إذا لم يكن هذا الكائن `[`IMultiPolygon`](../../imultipolygon/)` - يتم تحويل جميع الأسطح إلى خطية ويتم إنشاء `IMultiPolygon` جديد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiPolygon](../../imultipolygon/)
* class [MultiSurface](../)
* namespace [Aspose.Gis.Geometries](../../multisurface/)
* assembly [Aspose.GIS](../../../)


