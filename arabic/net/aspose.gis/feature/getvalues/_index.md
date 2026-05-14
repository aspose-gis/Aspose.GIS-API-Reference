---
title: "Feature.GetValues"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تُرجع القيم لجميع السمات في مصفوفة"
type: docs
weight: 50
url: /ar/net/aspose.gis/feature/getvalues/
---
## Feature.GetValues method

يعيد القيم لجميع السمات في مصفوفة.

```csharp
public int GetValues(object[] values, object defaultValue = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيم | Object[] | المصفوفة التي سيتم نسخ قيم السمات إليها. |
| defaultValue | Object | القيمة التي يجب إرجاعها إذا كانت قيمة السمة مفقودة (غير مُعيَّنة). القيمة الافتراضية هي `null`. يُنصح باستخدام 'DBNull.Value' للفصل بين القيم 'unset' و '`null`'. |

### قيمة الإرجاع

تم نسخ عدد من السمات.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| InvalidOperationException | السمة غير مقفلة. |

## ملاحظات

يتم نسخ قيم السمات للميزة إلى مصفوفة القيم التي يتم تمريرها كمعامل. بالنسبة للسمات ذات القيمة غير المُعيَّنة، يتم إرجاع المعامل 'unsetValue' المحدد. لا يلزم أن يتطابق طول مصفوفة القيم مع عدد السمات في الميزة. إذا كان طول المصفوفة أكبر من عدد السمات، يتم نسخ جميع قيم السمات إلى المصفوفة؛ وإذا كان أصغر، يتم نسخ عدد قيم السمات يساوي طول المصفوفة فقط إلى المصفوفة، بدءًا من قيمة السمة ذات الفهرس 0.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


