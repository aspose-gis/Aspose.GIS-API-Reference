---
title: "فئة RuleBasedLabeling"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Rendering.Labelings.RuleBasedLabeling. تطبق تسمية على العنصر وفقًا للقواعد المعرفة من قبل المستخدم"
type: docs
weight: 4140
url: /ar/net/aspose.gis.rendering.labelings/rulebasedlabeling/
---
## RuleBasedLabeling class

يطبق تسمية على الميزة وفقًا للقواعد المعرفة من قبل المستخدم.

```csharp
public class RuleBasedLabeling : Labeling, IReadOnlyList<LabelingRule>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [RuleBasedLabeling](rulebasedlabeling/)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.gis.rendering.labelings/rulebasedlabeling/count/) { get; } | يحصل على عدد القواعد. |
| [Item](../../aspose.gis.rendering.labelings/rulebasedlabeling/item/) { get; } | يحصل على القاعدة في الفهرس المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add/#add)(LabelingRule) | يضيف قاعدة. |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add/#add_1)(Func&lt;Feature, bool&gt;, Labeling) | يضيف [`LabelingRule`](../labelingrule/) جديدًا. |
| [AddElseRule](../../aspose.gis.rendering.labelings/rulebasedlabeling/addelserule/)(Labeling) | يضيف تسمية سيتم تطبيقها على العناصر التي لا تطابق أي قاعدة تصفية. |
| [GetEnumerator](../../aspose.gis.rendering.labelings/rulebasedlabeling/getenumerator/)() | يعيد عدّادًا يتنقل عبر القواعد. |

### انظر أيضًا

* class [Labeling](../labeling/)
* class [LabelingRule](../labelingrule/)
* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


