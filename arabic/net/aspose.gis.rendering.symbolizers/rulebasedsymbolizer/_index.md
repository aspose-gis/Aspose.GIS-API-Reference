---
title: "الفئة RuleBasedSymbolizer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Rendering.Symbolizers.RuleBasedSymbolizer فئة. يطبق مُرمّزاً على أشكال الميزات وفقاً لقواعد معرفة من قبل المستخدم"
type: docs
weight: 4380
url: /ar/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---
## RuleBasedSymbolizer class

يطبق الـ symbolizer على هندسات العناصر وفقًا لقواعد معرفة من قبل المستخدم.

```csharp
public class RuleBasedSymbolizer : VectorSymbolizer, IReadOnlyList<Rule>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RuleBasedSymbolizer](rulebasedsymbolizer/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/count/) { get; } | يحصل على عدد القواعد. |
| [Item](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/item/) { get; } | يحصل على القاعدة في الفهرس المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/#add)(Rule) | يضيف قاعدة. |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/#add_1)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | يضيف قاعدة جديدة [`Rule`](../rule/). |
| [AddElseRule](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/addelserule/)(VectorSymbolizer) | يضيف مُرمّزاً سيُطبق على الميزات التي لا تتطابق مع أي قاعدة تصفية. |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/getenumerator/)() | يعيد مُعددًا يتنقل عبر القواعد. |

### انظر أيضًا

* class [VectorSymbolizer](../vectorsymbolizer/)
* class [Rule](../rule/)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


