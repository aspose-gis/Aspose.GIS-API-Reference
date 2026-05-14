---
title: "Geometry.Relate"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت مصفوفة تقاطع DE9IM لهذا الشكل وشكل محدد تطابق النمط المقدم"
type: docs
weight: 300
url: /ar/net/aspose.gis.geometries/geometry/relate/
---
## Geometry.Relate method

يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم.

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |
| intersectionPatternMatrix | String | نمط للمطابقة معه. يجب أن تكون سلسلة بطول يساوي 9. كل حرف من السلسلة يمثل البُعد المتوقع لتقاطع: الحرف 0 - بين داخل الأشكال. الحرف 1 - بين داخل هذا الشكل وحدود شكل آخر. الحرف 2 - بين داخل هذا الشكل وخارج شكل آخر. الحرف 3 - بين حدود هذا الشكل وداخل شكل آخر. الحرف 4 - بين حدود الأشكال. الحرف 5 - بين حدود هذا الشكل وخارج شكل آخر. الحرف 6 - بين خارج هذا الشكل وداخل شكل آخر. الحرف 7 - بين خارج هذا الشكل وحدود شكل آخر. الحرف 8 - بين خارج الأشكال. القيم الممكنة لكل حرف هي: * - أي قيمة;F - لا تقاطع;T - أي تقاطع;0 - تقاطع نقطة (مثال: نقطة مشتركة);1 - تقاطع خط (مثال: جزء مشترك من خط);2 - تقاطع مساحة (مثال: جزء مشترك من مضلع); على سبيل المثال، نمط تقاطع \"F0*******\" يعني أنه لا يجب أن يكون هناك تقاطع بين داخل الأشكال وأن تقاطع حدود الأشكال يجب أن يكون نقطة. راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول نمط مصفوفة التقاطع. |

### قيمة الإرجاع

`true` إذا كانت مصفوفة التقاطع هذه تطابق النمط؛ `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *other* هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

هذه الطريقة تُنشئ مصفوفة تقاطع DE-9IM وتطابقها مع النمط. راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول مصفوفة تقاطع DE-9IM.

## أمثلة

الكود التالي:

```csharp
geometry.Relate(other, "T*F**FFF*");
```

سيكشف ما إذا كانت الأشكال متساوية مكانيًا.

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


