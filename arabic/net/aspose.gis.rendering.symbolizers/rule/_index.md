---
title: "الفئة Rule"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Rendering.Symbolizers.Rule. قاعدة معرفة من قبل المستخدم لـ RuleBasedSymbolizer."
type: docs
weight: 4370
url: /ar/net/aspose.gis.rendering.symbolizers/rule/
---
## Rule class

قاعدة معرفة من قبل المستخدم لـ [`RuleBasedSymbolizer`](../rulebasedsymbolizer/).

```csharp
public class Rule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Filter](../../aspose.gis.rendering.symbolizers/rule/filter/) { get; } | يحدد ما إذا كان "filter-rule" يجب أن يطبق الرمز على الميزة. إذا أعاد `true` يتم استخدام الرمز؛ وإلا يتم تخطي الميزة. |
| [IsElseRule](../../aspose.gis.rendering.symbolizers/rule/iselserule/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة هي "else-rule". |
| [IsFilterRule](../../aspose.gis.rendering.symbolizers/rule/isfilterrule/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة هي "filter-rule". |
| [Symbolizer](../../aspose.gis.rendering.symbolizers/rule/symbolizer/) { get; } | الرمز لتطبيقه على الميزة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateElseRule](../../aspose.gis.rendering.symbolizers/rule/createelserule/)(VectorSymbolizer) | ينشئ قاعدة جديدة تطبق رمزًا على الميزة كلما لم تتطابق مع أي قاعدة تصفية. |
| static [CreateFilterRule](../../aspose.gis.rendering.symbolizers/rule/createfilterrule/)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | ينشئ قاعدة جديدة تطبق رمزًا على الميزة كلما نجحت في التصفية. |

### انظر أيضًا

* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


