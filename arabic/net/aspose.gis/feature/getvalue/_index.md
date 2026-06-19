---
title: "Feature.GetValue"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تحصل على قيمة السمة."
type: docs
weight: 30
url: /ar/net/aspose.gis/feature/getvalue/
---
## GetValue(string) {#getvalue}

يحصل على قيمة سمة.

```csharp
public object GetValue(string attributeName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| attributeName | String | اسم السمة. |

### قيمة الإرجاع

قيمة السمة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | قيمة هذه السمة غير مُحددة لهذا العنصر. |

## ملاحظات

إذا لم تكن الطبقة تتطلب أن تحتوي ميزاتها على قيم لجميع السمات المعرفة للطبقة، قد تفشل هذه الطريقة مع InvalidOperationException عند طلب قيمة مفقودة. عند العمل مع مثل هذه الطبقات، يُنصح باستخدام [`GetValueOrDefault`](../getvalueordefault/).

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValue&lt;T&gt;(string) {#getvalue_1}

يحصل على قيمة سمة.

```csharp
public T GetValue<T>(string attributeName)
```

| معامل | الوصف |
| --- | --- |
| T | النوع المطلوب للقيمة. |
| attributeName | اسم السمة. |

### قيمة الإرجاع

قيمة السمة.

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

هذه الطريقة تحول القيمة تلقائيًا إلى النوع المطلوب في معامل النوع العام. إذا لم تكن الطبقة تتطلب أن تحتوي ميزاتها على قيم لجميع السمات المعرفة للطبقة، قد تفشل هذه الطريقة مع InvalidOperationException عند طلب قيمة مفقودة. عند العمل مع مثل هذه الطبقات، يُنصح باستخدام [`GetValueOrDefault`](../getvalueordefault/).

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


