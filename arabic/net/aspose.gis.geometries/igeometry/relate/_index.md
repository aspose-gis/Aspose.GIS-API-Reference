---
title: "IGeometry.Relate"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كانت مصفوفة تقاطع DE9IM لهذا الشكل وشكل محدد تطابق النمط المقدم"
type: docs
weight: 290
url: /ar/net/aspose.gis.geometries/igeometry/relate/
---
## IGeometry.Relate method

يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم.

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |
| intersectionPatternMatrix | String | نمط للمطابقة معه. يجب أن تكون سلسلة بطول يساوي 9. كل حرف من السلسلة يمثل البُعد المتوقع لتقاطع: الحرف 0 - بين داخل الهندستين. الحرف 1 - بين داخل هذه الهندسة وحدود هندسة أخرى. الحرف 2 - بين داخل هذه الهندسة وخارج هندسة أخرى. الحرف 3 - بين حدود هذه الهندسة وداخل هندسة أخرى. الحرف 4 - بين حدود الهندستين. الحرف 5 - بين حدود هذه الهندسة وخارج هندسة أخرى. الحرف 6 - بين خارج هذه الهندسة وداخل هندسة أخرى. الحرف 7 - بين خارج هذه الهندسة وحدود هندسة أخرى. الحرف 8 - بين خارج الهندستين. القيم الممكنة لكل حرف هي: * - أي قيمة;F - لا تقاطع;T - أي تقاطع;0 - تقاطع نقطة (مثال: نقطة مشتركة);1 - تقاطع خط (مثال: مقطع خط مشترك);2 - تقاطع مساحة (مثال: جزء مشترك من مضلع); على سبيل المثال، نمط التقاطع "F0*******" يعني أنه لا يجب أن يكون هناك تقاطع بين داخل الهندستين وأن يكون تقاطع حدود الهندستين نقطة. راجع مواصفات OpenGIS Simple Features لمزيد من التفاصيل حول نمط مصفوفة التقاطع. |

### قيمة الإرجاع

`true` إذا كانت مصفوفة التقاطع هذه تطابق النمط؛ `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *other* هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

هذه الطريقة تُنشئ مصفوفة تقاطع DE-9IM وتطابقها مع النمط. راجع مواصفات OpenGIS Simple Features لمزيد من التفاصيل حول مصفوفة تقاطع DE-9IM.

## أمثلة

الكود التالي:

```csharp
geometry.Relate(other, "T*F**FFF*");
```

سيتحقق مما إذا كانت الهندسات متساوية مكانيًا.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


