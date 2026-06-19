---
title: "IMultiSurface.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IMultiSurface. يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذا الشكل الهندسي باستخدام التسامح الافتراضي"
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

‏[`IMultiPolygon`](../../imultipolygon/) التي تقرب أو تعادل هذا [`IMultiSurface`](../). هذا هو المكافئ لـ `ToLinearGeometry` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل الهندسي: بالنسبة إلى SRS الإسقاطي يكون التسامح 0.001 متر (بوحدات SRS) بالنسبة إلى SRS الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS) بالنسبة إلى SRS غير المعروف يكون التسامح `1e-5` للحصول على مزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

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
| التسامح | Double | قيمة `tolerance` المراد استخدامها. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

‏[`IMultiPolygon`](../../imultipolygon/) التي تقرب أو تعادل هذا [`IMultiSurface`](../): إذا كان هذا الكائن هو [`IMultiPolygon`](../../imultipolygon/) نفسه فإن النتيجة تعادل هذا الكائن إذا لم يكن هذا الكائن هو [`IMultiPolygon`](../../imultipolygon/) - يتم تحويل جميع الأسطح إلى خطية ويتم إنشاء `IMultiPolygon` جديد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أصغر من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بهذه الطريقة، بحيث لا يمكن إكمال العملية. |

### انظر أيضًا

* interface [IMultiPolygon](../../imultipolygon/)
* interface [IMultiSurface](../)
* namespace [Aspose.Gis.Geometries](../../imultisurface/)
* assembly [Aspose.GIS](../../../)


