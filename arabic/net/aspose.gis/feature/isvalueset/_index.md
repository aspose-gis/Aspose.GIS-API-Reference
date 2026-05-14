---
title: "Feature.IsValueSet"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تتحقق مما إذا كانت قيمة الخاصية مُعينة في هذه الميزة"
type: docs
weight: 90
url: /ar/net/aspose.gis/feature/isvalueset/
---
## Feature.IsValueSet method

يفحص ما إذا كانت قيمة السمة مُعينة في هذه الميزة.

```csharp
public bool IsValueSet(string attributeName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| attributeName | String | اسم السمة. |

### قيمة الإرجاع

`true` إذا تم تعيين قيمة الخاصية المحددة؛ وإلا `false`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | السمة غير مقفلة. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| ArgumentNullException | اسم السمة هو `null`. |

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


