---
title: "Geometry.Crosses"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كان هذا الشكل وشكل محدد يتقاطعان"
type: docs
weight: 170
url: /ar/net/aspose.gis.geometries/geometry/crosses/
---
## Geometry.Crosses method

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

```csharp
public bool Crosses(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل \"يتقاطع مكانيًا\" مع شكل آخر. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

هذه الطريقة تختبر ما إذا كانت الأشكال تتقاطع وفقًا لمصفوفة تقاطع DE-9IM. يتقاطع شكلان إذا كان لديهما بعض نقاط الداخلية المشتركة ولكن ليس كلها، وكان بُعد التقاطع أقل من بُعد أحد الشكلين على الأقل. أي: يتقاطع شكلان من نوع [`LineString`](../../linestring/) إذا شكلا حرف 'X'، ويتقاطع [`LineString`](../../linestring/) مع [`Polygon`](../../polygon/) إذا مر الـ LineString عبر داخل المضلع. راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة \"يتقاطع مكانيًا\".

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


