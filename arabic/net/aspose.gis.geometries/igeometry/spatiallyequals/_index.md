---
title: "IGeometry.SpatiallyEquals"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "IGeometry طريقة. يحدد ما إذا كانت هذه الهندسة متساوية مكانيًا لهندسة محددة"
type: docs
weight: 320
url: /ar/net/aspose.gis.geometries/igeometry/spatiallyequals/
---
## IGeometry.SpatiallyEquals method

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للأشكال غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الأشكال إلى نفس نظام الإسناد المكاني. |

## ملاحظات

تختبر هذه الطريقة المساواة من حيث مصفوفة تقاطع DE-9IM. لا تعتمد على ترتيب المكونات (مثل ترتيب الحلقات الداخلية في المضلع)، أو قيم Z و M. أساسًا، تختبر أن الهندستين تشغلان نفس "المساحة" عند إسقاطهما على الفضاء ثنائي الأبعاد. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*F**FFF*");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


