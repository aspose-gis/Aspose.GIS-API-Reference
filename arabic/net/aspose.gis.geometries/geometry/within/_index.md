---
title: "Geometry.Within"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت هذه الهندسة داخل نطاق محدد"
type: docs
weight: 450
url: /ar/net/aspose.gis.geometries/geometry/within/
---
## Within(Extent) {#within}

يحدد ما إذا كان هذا الشكل داخل نطاق محدد.

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
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

يحدد ما إذا كان هذا الشكل داخل شكل محدد.

```csharp
public bool Within(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "موجودة مكانيًا" داخل هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت هندسة واحدة داخل أخرى من حيث مصفوفة تقاطع DE-9IM. تكون الهندسة داخل أخرى إذا كانت الهندسة الأخرى تحتوي على كل نقطة من الهندسة وتتقاطع داخليات الهندستين. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*F**F***");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "موجودة مكانيًا".

### انظر أيضًا

* method [SpatiallyContains](../../igeometry/spatiallycontains/)
* method [CoveredBy](../../igeometry/coveredby/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


