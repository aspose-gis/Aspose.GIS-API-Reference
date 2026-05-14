---
title: "Feature.SetValue"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تعيين قيمة جديدة لسمة."
type: docs
weight: 100
url: /ar/net/aspose.gis/feature/setvalue/
---
## Feature.SetValue&lt;T&gt; method

يضبط قيمة جديدة لسمة.

```csharp
public void SetValue<T>(string attributeName, T value)
```

| معامل | الوصف |
| --- | --- |
| T | نوع القيمة. |
| attributeName | اسم الخاصية. |
| قيمة | قيمة السمة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidCastException | نوع القيمة لا يُطبق الواجهة IConvertible. |
| FormatException | فشل التحويل لأن القيمة بتنسيق غير صحيح. |
| OverflowException | فشل التحويل بسبب تجاوز السعة. |

## ملاحظات

تحول هذه الطريقة القيمة تلقائيًا إلى نوع السمة.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


