---
title: "IMultiSurface.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IMultiSurface. تحصل على نسخة تقريبية أو مكافئة غير منحنية لهذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 20
url: /ar/net/aspose.gis.geometries/imultisurface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IMultiPolygon ToLinearGeometry()
```

### قيمة الإرجاع

‏[`IMultiPolygon`](../../imultipolygon/) تقريبية أو مكافئة لهذا [`IMultiSurface`](../). هذه هي المكافئة لـ `ToLinearGeometry` مع `tolerance` الافتراضية. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي:  بالنسبة إلى نظام الإحداثيات المُسقَّط (SRS) يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى نظام الإحداثيات الجغرافي (SRS) يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى نظام إحداثيات غير معروف يكون التسامح `1e-5` للحصول على مزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IMultiPolygon](../../imultipolygon/)
* interface [IMultiSurface](../)
* namespace [Aspose.Gis.Geometries](../../imultisurface/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IMultiPolygon ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` للاستخدام. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

‏[`IMultiPolygon`](../../imultipolygon/) تقريبية أو مكافئة لهذا [`IMultiSurface`](../):  إذا كان هذا الكائن هو نفسه [`IMultiPolygon`](../../imultipolygon/) فإن النتيجة مكافئة لهذا الكائن. إذا لم يكن هذا الكائن [`IMultiPolygon`](../../imultipolygon/) - يتم تحويل جميع الأسطح إلى خطية ويتم إنشاء `IMultiPolygon` جديد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IMultiPolygon](../../imultipolygon/)
* interface [IMultiSurface](../)
* namespace [Aspose.Gis.Geometries](../../imultisurface/)
* assembly [Aspose.GIS](../../../)


