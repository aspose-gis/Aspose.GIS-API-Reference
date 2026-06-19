---
title: "IGeometry.Crosses"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كان هذا الشكل وشكل محدد يتقاطعان"
type: docs
weight: 160
url: /ar/net/aspose.gis.geometries/igeometry/crosses/
---
## IGeometry.Crosses method

يحدد ما إذا كانت هذه الـ geometry وهندسة محددة تتقاطع.

```csharp
public bool Crosses(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "تتقاطع مكانيًا" مع هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت الهندسات تتقاطع وفقًا لمصفوفة تقاطع DE-9IM. تتقاطع هندستان إذا كان لديهما بعض نقاط الداخلية المشتركة ولكن ليس كلها، وكان بُعد التقاطع أقل من بُعد إحدى الهندسات على الأقل. أي: يتقاطع خطان من نوع [`LineString`](../../linestring/) إذا شكلا حرف "X"، ويتقاطع خط من نوع `LineString` مع [`Polygon`](../../polygon/) إذا مر الخط عبر داخل المضلع. راجع مواصفات OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "التقاطع مكانيًا".

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


