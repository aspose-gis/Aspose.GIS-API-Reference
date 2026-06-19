---
title: "IGeometry.Within"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كانت هذه الهندسة داخل نطاق محدد"
type: docs
weight: 380
url: /ar/net/aspose.gis.geometries/igeometry/within/
---
## Within(Extent) {#within}

يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد.

```csharp
public bool Within(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | المدى. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة داخل النطاق؛ `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* method [Contains](../../../aspose.gis/extent/contains/)
* class [Extent](../../../aspose.gis/extent/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة.

```csharp
public bool Within(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "موجودة مكانيًا داخل" هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت هندسة واحدة داخل أخرى وفقًا لمصفوفة تقاطع DE-9IM. تكون الهندسة داخل أخرى إذا كانت الهندسة الأخرى تحتوي على كل نقطة من الهندسة وتتقاطع داخليات الهندستين. هذه الطريقة تعادل:

```csharp
this.Relate(other, "T*F**F***");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "الموجود مكانيًا داخل".

### انظر أيضًا

* method [SpatiallyContains](../spatiallycontains/)
* method [CoveredBy](../coveredby/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


