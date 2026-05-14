---
title: "Geometry.Disjoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كان هذا الشكل الهندسي منفصلًا عن شكل هندسي محدد."
type: docs
weight: 190
url: /ar/net/aspose.gis.geometries/geometry/disjoint/
---
## Geometry.Disjoint method

يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.

```csharp
public bool Disjoint(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل الهندسي "منفصل مكانيًا" عن شكل هندسي آخر. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

هذه الطريقة تختبر ما إذا كانت الأشكال الهندسية منفصلة من حيث مصفوفة تقاطع DE-9IM. أساسًا، تختبر أن الشكلين لا يملكان نقاطًا مشتركة. هذه الطريقة تعادل:

```csharp
this.Relate(other, "FF*FF****");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM.

### انظر أيضًا

* method [Intersects](../../igeometry/intersects/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


