---
title: "Rule.CreateFilterRule"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Rule. تنشئ قاعدة جديدة تطبق رمزًا على العنصر كلما اجتاز الفلتر"
type: docs
weight: 20
url: /ar/net/aspose.gis.rendering.symbolizers/rule/createfilterrule/
---
## Rule.CreateFilterRule method

ينشئ قاعدة جديدة تطبق رمزًا على الميزة كلما نجحت في التصفية.

```csharp
public static Rule CreateFilterRule(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فلتر | Func`2 | يحدد متى يجب استخدام المُرمّز. |
| symbolizer | VectorSymbolizer | الرمز لتطبيقه. |

### قيمة الإرجاع

كائن القاعدة الجديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الفلتر هو `null`. |

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* class [VectorSymbolizer](../../vectorsymbolizer/)
* class [Rule](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rule/)
* assembly [Aspose.GIS](../../../)


