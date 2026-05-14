---
title: "Geometry.SpatiallyEquals"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة."
type: docs
weight: 370
url: /ar/net/aspose.gis.geometries/geometry/spatiallyequals/
---
## Geometry.SpatiallyEquals method

يحدد ما إذا كانت هذه الهندسة مكافئة مكانيًا لهندسة محددة.

```csharp
public bool SpatiallyEquals(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "مساوية مكانيًا" لهندسة محددة. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

تختبر هذه الطريقة المساواة من حيث مصفوفة تقاطع DE-9IM. لا تعتمد على ترتيب المكونات (مثل ترتيب الحلقات الداخلية في المضلع)، أو قيم Z و M. أساسًا، تختبر أن الهندستين تشغلان نفس "المساحة" عند إسقاطهما على الفضاء ثنائي الأبعاد. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*F**FFF*");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM.

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


