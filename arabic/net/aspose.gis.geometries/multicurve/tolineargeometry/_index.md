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
| التسامح | Double | قيمة `tolerance` للاستخدام. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

كائن [`IMultiLineString`](../../imultilinestring/) يقترب أو يعادل هذا [`IMultiCurve`](../../imulticurve/): إذا كان هذا الكائن هو نفسه [`IMultiLineString`](../../imultilinestring/) فإن النتيجة تعادل هذا الكائن إذا لم يكن هذا الكائن [`IMultiLineString`](../../imultilinestring/) - يتم تحويل جميع المنحنيات إلى خطية ويتم إنشاء `IMultiLineString` جديد

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

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

كائن [`IMultiLineString`](../../imultilinestring/) يقترب أو يعادل هذا [`IMultiCurve`](../../imulticurve/). هذا يعادل [`ToLinearGeometry`](../../imulticurve/tolineargeometry/) باستخدام `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذه الهندسة: بالنسبة إلى نظام الإسناد المكاني المُسقَط (SRS) يكون التسامح 0.001 متر (بوحدات SRS)؛ بالنسبة إلى نظام الإسناد المكاني الجغرافي يكون التسامح `1e-5` درجة (بوحدات SRS)؛ بالنسبة إلى نظام إسناد مكاني غير معروف يكون التسامح `1e-5`. لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات [`ToLinearGeometry`](../../imulticurve/tolineargeometry/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IMultiLineString](../../imultilinestring/)
* class [MultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../multicurve/)
* assembly [Aspose.GIS](../../../)


