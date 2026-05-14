---
title: "RuleBasedSymbolizer.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RuleBasedSymbolizer. تضيف قاعدة جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/
---
## Add(Func&lt;Feature, bool&gt;, VectorSymbolizer) {#add_1}

تضيف قاعدة جديدة [`Rule`](../../rule/).

```csharp
public void Add(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فلتر | Func`2 | يحدد متى يجب تطبيق symbolizer على ميزة. |
| symbolizer | VectorSymbolizer | symbolizer لتطبيقه على ميزة عندما يُعيد *filter* true. |

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* class [VectorSymbolizer](../../vectorsymbolizer/)
* class [RuleBasedSymbolizer](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rulebasedsymbolizer/)
* assembly [Aspose.GIS](../../../)

---

## Add(Rule) {#add}

يضيف قاعدة.

```csharp
public void Add(Rule rule)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قاعدة | Rule | قاعدة للإضافة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [Rule](../../rule/)
* class [RuleBasedSymbolizer](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rulebasedsymbolizer/)
* assembly [Aspose.GIS](../../../)


