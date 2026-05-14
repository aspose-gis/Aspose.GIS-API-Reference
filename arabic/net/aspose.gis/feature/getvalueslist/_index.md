---
title: "Feature.GetValuesList"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تحصل على قيم تسلسل السمات كقائمة"
type: docs
weight: 70
url: /ar/net/aspose.gis/feature/getvalueslist/
---
## Feature.GetValuesList&lt;T&gt; method

يحصل على قيم تسلسل السمات كقائمة.

```csharp
public List<T> GetValuesList<T>(string attributeName, string separator, int count = 0)
```

| معامل | الوصف |
| --- | --- |
| T | النوع المطلوب للقيم. |
| attributeName | اسم السمة. |
| فاصل | سلسلة تُستخدم لفصل اسم السمة وقيمة الفهرس في التسلسل. |
| عدد | عدد القيم التي يجب إرجاعها (القيم المفقودة تُملأ كقيمة null) |

### قيمة الإرجاع

قائمة القيم للسمات التي تختلف أسماؤها حسب قيمة فهرس التسلسل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | قيمة هذه السمة غير مُحددة لهذه الميزة. |
| InvalidCastException | النوع المطلوب لا يُطبق الواجهة IConvertible. |
| InvalidCastException | قيمة السمة هي `null`، لكن النوع المطلوب هو نوع قيمي. |
| FormatException | فشل التحويل لأن القيمة بتنسيق غير صحيح. |
| OverflowException | فشل التحويل بسبب تجاوز السعة. |

## ملاحظات

يستخدم هذا [`GetValue`](../getvalue/) للحصول على قيمة واحدة. لذا، تقوم هذه الطريقة بتحويل القيمة تلقائيًا إلى النوع المطلوب في معامل النوع العام. إذا لم يتم العثور على السمة ذات الفهرس 0 فستُنشئ استثناء ArgumentException.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


