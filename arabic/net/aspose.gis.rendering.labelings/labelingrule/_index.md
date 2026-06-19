---
title: "فئة LabelingRule"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Rendering.Labelings.LabelingRule. قاعدة معرفة من قبل المستخدم لـ RuleBasedLabeling"
type: docs
weight: 4080
url: /ar/net/aspose.gis.rendering.labelings/labelingrule/
---
## LabelingRule class

قاعدة معرفة من قبل المستخدم لـ [`RuleBasedLabeling`](../rulebasedlabeling/).

```csharp
public class LabelingRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Filter](../../aspose.gis.rendering.labelings/labelingrule/filter/) { get; } | يحدد ما إذا كان "filter-rule" يجب أن يطبق التسمية على العنصر. إذا أرجع `true` يتم استخدام التسمية؛ وإلا يتم تخطي العنصر. |
| [IsElseRule](../../aspose.gis.rendering.labelings/labelingrule/iselserule/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة هي "else-rule". |
| [IsFilterRule](../../aspose.gis.rendering.labelings/labelingrule/isfilterrule/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة هي "filter-rule". |
| [Labeling](../../aspose.gis.rendering.labelings/labelingrule/labeling/) { get; } | التسمية التي تُطبق على العنصر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateElseRule](../../aspose.gis.rendering.labelings/labelingrule/createelserule/)(Labeling) | ينشئ قاعدة جديدة تُطبق تسمية على العنصر كلما لم تتطابق مع أي قاعدة تصفية. |
| static [CreateFilterRule](../../aspose.gis.rendering.labelings/labelingrule/createfilterrule/)(Func&lt;Feature, bool&gt;, Labeling) | ينشئ قاعدة جديدة تُطبق تسمية على العنصر كلما اجتاز الفلتر. |

### انظر أيضًا

* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


