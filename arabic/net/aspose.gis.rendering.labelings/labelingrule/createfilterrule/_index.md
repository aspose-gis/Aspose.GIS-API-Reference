---
title: "LabelingRule.CreateFilterRule"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة LabelingRule. تنشئ قاعدة جديدة تطبق تسمية على المعلم كلما اجتاز filter"
type: docs
weight: 20
url: /ar/net/aspose.gis.rendering.labelings/labelingrule/createfilterrule/
---
## LabelingRule.CreateFilterRule method

ينشئ قاعدة جديدة تطبق تصنيفًا على العنصر كلما اجتاز الفلتر.

```csharp
public static LabelingRule CreateFilterRule(Func<Feature, bool> filter, Labeling labeling)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فلتر | Func`2 | يحدد متى يجب استخدام التسمية. |
| تسمية | التسمية | التسمية لتطبيقها. |

### قيمة الإرجاع

كائن LabelingRule جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الفلتر هو `null`. |

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* class [Labeling](../../labeling/)
* class [LabelingRule](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../labelingrule/)
* assembly [Aspose.GIS](../../../)


