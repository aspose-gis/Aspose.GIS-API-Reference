---
title: "Geometry.Overlaps"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة"
type: docs
weight: 290
url: /ar/net/aspose.gis.geometries/geometry/overlaps/
---
## Geometry.Overlaps method

يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة.

```csharp
public bool Overlaps(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "تتداخل مكانيًا" مع هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت الهندسات تتداخل وفقًا لمصفوفة تقاطع DE-9IM. تتداخل هندستان إذا كان لديهما بعض نقاط الداخلية المشتركة ولكن ليس كلها، وكان تقاطع الهندسات له نفس البعد مثل الهندسات نفسها. بالنسبة لهندستين من نوع Point أو هندستين من نوع Surface تكون هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*T***T**");
```

بالنسبة لهندستين من نوع Line تكون هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "1*T***T**");
```

لهندستين ذات [`Dimension`](../../igeometry/dimension/) غير متساوية، تُعيد هذه الطريقة دائمًا `false`. راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "تتداخل مكانيًا".

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


