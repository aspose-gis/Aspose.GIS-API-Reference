---
title: "IGeometry.Disjoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كان هذا الشكل الهندسي منفصلًا عن شكل هندسي محدد"
type: docs
weight: 180
url: /ar/net/aspose.gis.geometries/igeometry/disjoint/
---
## IGeometry.Disjoint method

يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.

```csharp
public bool Disjoint(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل الهندسي "منفصل مكانيًا" عن شكل هندسي آخر. `false` غير ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت الأشكال الهندسية منفصلة وفقًا لمصفوفة تقاطع DE-9IM. أساسًا، تختبر أن شكلين هندسيين لا يملكان نقاطًا مشتركة. هذه الطريقة تعادل:

```csharp
this.Relate(other, "FF*FF****");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM.

### انظر أيضًا

* method [Intersects](../intersects/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


