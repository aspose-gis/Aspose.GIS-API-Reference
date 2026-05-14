---
title: "ISurface.ToLinearGeometry"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ISurface. تحصل على نسخة تقريبية أو مكافئة غير منحنية من هذا الشكل الهندسي باستخدام التسامح الافتراضي"
type: docs
weight: 30
url: /ar/net/aspose.gis.geometries/isurface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي.

```csharp
public IPolygon ToLinearGeometry()
```

### قيمة الإرجاع

كائن [`IPolygon`](../../ipolygon/) يقترب أو يعادل هذا `ISurface`. هذا يعادل `ToLinearGeometry` مع `tolerance` الافتراضي. قيمة `tolerance` الافتراضية تعتمد على [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) لهذا الشكل:  بالنسبة إلى SRS المُسقطة يكون التسامح 0.001 متر (بوحدات SRS)  بالنسبة إلى SRS الجغرافية يكون التسامح `1e-5` درجة (بوحدات SRS)  بالنسبة إلى SRS غير المعروفة يكون التسامح `1e-5` لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات `ToLinearGeometry`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IPolygon](../../ipolygon/)
* interface [ISurface](../)
* namespace [Aspose.Gis.Geometries](../../isurface/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد.

```csharp
public IPolygon ToLinearGeometry(double tolerance)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التسامح | Double | قيمة `tolerance` للاستخدام. النتيجة مضمونة أن تكون أقل من `tolerance` بعيدًا عن الهندسة المنحنية، ما لم يتجاوز عدد النقاط المطلوبة لتقويم الهندسة الحد الأقصى لكل ربع، وهو حاليًا يساوي 10000 نقطة. |

### قيمة الإرجاع

كائن [`IPolygon`](../../ipolygon/) يقترب أو يعادل هذا `ISurface`: إذا كان هذا الكائن هو [`IPolygon`](../../ipolygon/) نفسه تكون النتيجة معادلة لهذا الكائن إذا لم يكن هذا الكائن هو [`IPolygon`](../../ipolygon/) يتم تقويمه ويتم إنشاء [`IPolygon`](../../ipolygon/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` أقل من أو يساوي `0`. |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |

### انظر أيضًا

* interface [IPolygon](../../ipolygon/)
* interface [ISurface](../)
* namespace [Aspose.Gis.Geometries](../../isurface/)
* assembly [Aspose.GIS](../../../)


