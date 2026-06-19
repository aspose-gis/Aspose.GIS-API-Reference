---
title: "Feature.GetValuesList"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Feature الطريقة. يحصل على قيم تسلسل السمات كقائمة"
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
| الفاصل | سلسلة تُستخدم لفصل اسم السمة وقيمة الفهرس في التسلسل. |
| العدد | عدد القيم التي سيتم إرجاعها (القيمة المفقودة تُملأ كـ null) |

### قيمة الإرجاع

قائمة القيم للسمات التي تختلف أسماؤها حسب قيمة فهرس التسلسل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | قيمة هذه السمة غير مُحددة لهذا العنصر. |
| InvalidCastException | النوع المطلوب لا يُطبق الواجهة IConvertible. |
| InvalidCastException | قيمة السمة هي `null`، لكن النوع المطلوب هو نوع قيمة. |
| FormatException | فشل التحويل لأن القيمة بتنسيق غير صحيح. |
| OverflowException | فشل التحويل بسبب تجاوز السعة. |

## ملاحظات

هذا يستخدم [`GetValue`](../getvalue/) للحصول على قيمة واحدة. لذلك، تقوم هذه الطريقة بتحويل القيمة تلقائيًا إلى النوع المطلوب في معامل النوع العام. إذا لم يتم العثور على السمة ذات الفهرس 0 فستولد استثناء ArgumentException.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


