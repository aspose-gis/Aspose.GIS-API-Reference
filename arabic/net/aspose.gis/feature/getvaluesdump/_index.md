---
title: "Feature.GetValuesDump"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تُرجع القيم لجميع السمات في مصفوفة. يُنصح باستخدام طريقة GetValues لتجنب تخصيص الذاكرة الإضافي"
type: docs
weight: 60
url: /ar/net/aspose.gis/feature/getvaluesdump/
---
## Feature.GetValuesDump method

تُرجع القيم لجميع السمات في مصفوفة. يُنصح باستخدام طريقة [`GetValues`](../getvalues/) لتجنب تخصيص الذاكرة الإضافي.

```csharp
public object[] GetValuesDump(object defaultValue = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| defaultValue | Object | القيمة التي يجب إرجاعها إذا كانت قيمة السمة مفقودة (غير مُعيَّنة). القيمة الافتراضية هي `null`. يُنصح باستخدام 'DBNull.Value' للفصل بين القيم 'unset' و '`null`'. |

### قيمة الإرجاع

مصفوفة جديدة سيتم نسخ قيم السمات إليها.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| InvalidOperationException | السمة غير مقفلة. |

## ملاحظات

يتم نسخ قيم السمات للميزة إلى مصفوفة القيم التي يتم تمريرها كمعامل. بالنسبة للسمات ذات القيمة غير المُعيَّنة، يتم إرجاع المعامل 'unsetValue' المحدد.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


