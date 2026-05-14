---
title: "RuleBasedLabeling.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RuleBasedLabeling. تُضيف LabelingRule جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.rendering.labelings/rulebasedlabeling/add/
---
## Add(Func&lt;Feature, bool&gt;, Labeling) {#add_1}

يضيف [`LabelingRule`](../../labelingrule/) جديدًا.

```csharp
public void Add(Func<Feature, bool> filter, Labeling labeling)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فلتر | Func`2 | يحدد متى يجب تطبيق التوسيم على عنصر. |
| تسمية | التسمية | التوسيم لتطبيقه على عنصر عندما *filter* يُعيد true. |

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* class [Labeling](../../labeling/)
* class [RuleBasedLabeling](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling/)
* assembly [Aspose.GIS](../../../)

---

## Add(LabelingRule) {#add}

يضيف قاعدة.

```csharp
public void Add(LabelingRule rule)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| قاعدة | LabelingRule | قاعدة للإضافة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [LabelingRule](../../labelingrule/)
* class [RuleBasedLabeling](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling/)
* assembly [Aspose.GIS](../../../)


