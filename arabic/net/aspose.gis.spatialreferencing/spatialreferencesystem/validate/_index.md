---
title: "SpatialReferenceSystem.Validate"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. تحديد ما إذا كان هذا الـ SRS صالحًا."
type: docs
weight: 240
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/validate/
---
## SpatialReferenceSystem.Validate method

تحديد ما إذا كان هذا SRS صالحًا.

```csharp
public abstract bool Validate(out string errorMessage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| errorMessage | String& | إذا أعادت الطريقة `false`، فهذه هي وصف عدم الصلاحية. |

### قيمة الإرجاع

`true` إذا كان الـ SRS صالحًا، `false` غير ذلك.

## ملاحظات

يجب أن يكون الـ SRS صالحًا ويحتوي على إهليلج صالح. - يجب أن يحتوي الـ Geographic SRS على محور واحد بالاتجاه شرق/غرب، ومحور واحد بالاتجاه شمال/جنوب، ومحور اختياري أعلى/أسفل (يظهر المحور الاختياري عندما يكون الـ Geographic SRS مركبًا من SRS جغرافي ثنائي الأبعاد وVertical SRS). - يجب أن يحتوي الـ Projected SRS على محور واحد بالاتجاه شرق/غرب، ومحور واحد بالاتجاه شمال/جنوب، ومحور اختياري أعلى/أسفل (يظهر المحور الاختياري عندما يكون الـ Projected SRS مركبًا من SRS جغرافي ثنائي الأبعاد وVertical SRS). - يجب أن يحتوي الـ Geocentric SRS على محور واحد بالاتجاه شرق/غرب، ومحور واحد بالاتجاه شمال/جنوب، ومحور آخر واحد. - يجب أن يحتوي الـ Vertical SRS على محور واحد أعلى/أسفل. - يجب أن يحتوي الـ Local SRS على محور واحد على الأقل. اتجاهات المحاور لا تقاس بالمتر. - يجب أن يكون الـ Compound SRS مزيجًا من Geographic/Projected صالح وVertical SRS صالح.

### انظر أيضًا

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


