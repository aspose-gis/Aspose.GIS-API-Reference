---
title: "Feature.SetValues"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تُعيّن قيمًا جديدة لجميع السمات. كما يُنصح باستخدام طريقة CopyValues لتبسيط تعيين القيم في استدعاء واحد"
type: docs
weight: 120
url: /ar/net/aspose.gis/feature/setvalues/
---
## Feature.SetValues method

يُعيّن قيمًا جديدة لجميع السمات. كما يُنصح باستخدام طريقة [`CopyValues`](../copyvalues/) لتبسيط تعيين القيم في استدعاء واحد.

```csharp
public int SetValues(object[] values)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيم | Object[] | المصفوفة التي تحتوي على القيم الجديدة. |

### قيمة الإرجاع

عدد قيم السمات التي تم تعيينها.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعامل لا يمكن أن يكون `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidCastException | نوع القيمة لا يُطبق الواجهة IConvertible. |
| FormatException | فشل التحويل لأن القيمة بتنسيق غير صحيح. |
| OverflowException | فشل التحويل بسبب تجاوز السعة. |

## ملاحظات

هذه الطريقة تحول كل قيمة تلقائيًا إلى نوع السمة. لا يلزم أن يتطابق طول مصفوفة القيم مع عدد السمات في العنصر. إذا كان طول المصفوفة أكبر من عدد السمات، تُنسخ جميع قيم المصفوفة إلى السمات؛ وإذا كان أصغر، تُنسخ فقط عدد القيم المتساوي لطول المصفوفة إلى السمات، بدءًا من قيمة السمة ذات الفهرس 0.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


