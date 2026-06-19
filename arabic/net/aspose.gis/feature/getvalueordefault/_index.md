---
title: "Feature.GetValueOrDefault"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. يحصل على قيمة سمة أو DefaultValue إذا كانت القيمة غير مُحددة أو null"
type: docs
weight: 40
url: /ar/net/aspose.gis/feature/getvalueordefault/
---
## GetValueOrDefault&lt;T&gt;(string) {#getvalueordefault_1}

يحصل على قيمة سمة، أو [`DefaultValue`](../../featureattribute/defaultvalue/) إذا كانت القيمة غير مُحددة أو `null`.

```csharp
public T GetValueOrDefault<T>(string attributeName)
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

هذه الطريقة تحول القيمة تلقائيًا إلى النوع المطلوب في معامل النوع العام.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValueOrDefault(string, object) {#getvalueordefault}

يحصل على قيمة سمة، أو [`DefaultValue`](../../featureattribute/defaultvalue/) إذا كانت القيمة غير مُحددة أو `null`.

```csharp
public object GetValueOrDefault(string attributeName, object defaultValue = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| attributeName | String | اسم السمة. |
| defaultValue | Object | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة. القيمة الافتراضية هي `null`. |

### قيمة الإرجاع

قيمة السمة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | قيمة هذه السمة غير مُحددة لهذا العنصر. |

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValueOrDefault&lt;T&gt;(string, object) {#getvalueordefault_2}

يحصل على قيمة سمة، أو [`DefaultValue`](../../featureattribute/defaultvalue/) إذا كانت القيمة غير مُحددة أو `null`.

```csharp
public T GetValueOrDefault<T>(string attributeName, object defaultValue)
```

| معامل | الوصف |
| --- | --- |
| T | النوع المطلوب للقيمة. |
| attributeName | اسم السمة. |
| defaultValue | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة. |

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

هذه الطريقة تحول القيمة تلقائيًا إلى النوع المطلوب في معامل النوع العام.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


