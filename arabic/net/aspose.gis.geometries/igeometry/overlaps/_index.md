---
title: "IGeometry.Overlaps"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة"
type: docs
weight: 280
url: /ar/net/aspose.gis.geometries/igeometry/overlaps/
---
## IGeometry.Overlaps method

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت الهندسات تتداخل وفق مصفوفة تقاطع DE-9IM. تتداخل هندستان إذا كان لديهما بعض نقاط الداخلية المشتركة ولكن ليس جميعها، وكان تقاطع الهندسات له نفس البعد مثل الهندسات نفسها. بالنسبة لهندستين من نوع Point أو هندستين من نوع Surface تكون هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*T***T**");
```

بالنسبة لهندستين من نوع Line تكون هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "1*T***T**");
```

بالنسبة إلى هندستين لا تتساوي أبعادهما [`Dimension`](../dimension/) تُعيد هذه الطريقة دائمًا `false`. راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "spatially overlaps".

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


