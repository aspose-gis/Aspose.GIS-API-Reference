---
title: "الفئة RuleBasedSymbolizer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Rendering.Symbolizers.RuleBasedSymbolizer الفئة. يطبق مُرمّزًا على أشكال المميزات وفقًا للقواعد المحددة من قبل المستخدم"
type: docs
weight: 4380
url: /ar/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---
## RuleBasedSymbolizer class

يطبق رمزًا على هندسات الميزة وفقًا للقواعد المعرفة من قبل المستخدم.

```csharp
public class RuleBasedSymbolizer : VectorSymbolizer, IReadOnlyList<Rule>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RuleBasedSymbolizer](rulebasedsymbolizer/)() | المُنشئ الافتراضي. |

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
| [AddElseRule](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/addelserule/)(VectorSymbolizer) | يضيف مُرمّزًا سيُطبق على المميزات التي لا تتطابق مع أي قاعدة تصفية. |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/getenumerator/)() | يعيد عدّادًا يتنقل عبر القواعد. |

### انظر أيضًا

* class [VectorSymbolizer](../vectorsymbolizer/)
* class [Rule](../rule/)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


