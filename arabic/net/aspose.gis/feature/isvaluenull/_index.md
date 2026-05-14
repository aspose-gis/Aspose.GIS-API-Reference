---
title: "Feature.IsValueNull"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تحدد ما إذا كانت الخاصية المحددة قد تم تعيينها صراحةً إلى قيمة null"
type: docs
weight: 80
url: /ar/net/aspose.gis/feature/isvaluenull/
---
## Feature.IsValueNull method

يحدد ما إذا كانت السمة المحددة قد تم تعيينها صراحةً إلى القيمة `null`.

```csharp
public bool IsValueNull(string attributeName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| attributeName | String | اسم السمة. |

### قيمة الإرجاع

`true` إذا كانت قيمة الخاصية `null`؛ وإلا `false`.

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


