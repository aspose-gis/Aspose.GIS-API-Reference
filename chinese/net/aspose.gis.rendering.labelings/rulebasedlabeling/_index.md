---
title: "类 RuleBasedLabeling"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Rendering.Labelings.RuleBasedLabeling 类。根据用户定义的规则对要素应用标注。"
type: docs
weight: 4140
url: /zh/net/aspose.gis.rendering.labelings/rulebasedlabeling/
---
## RuleBasedLabeling class

根据用户定义的规则对要素应用标注。

```csharp
public class RuleBasedLabeling : Labeling, IReadOnlyList<LabelingRule>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RuleBasedLabeling](rulebasedlabeling/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.rendering.labelings/rulebasedlabeling/count/) { get; } | 获取规则的数量。 |
| [Item](../../aspose.gis.rendering.labelings/rulebasedlabeling/item/) { get; } | 获取指定索引处的规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add/#add)(LabelingRule) | 添加一条规则。 |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add/#add_1)(Func&lt;Feature, bool&gt;, Labeling) | 添加新的[`LabelingRule`](../labelingrule/)。 |
| [AddElseRule](../../aspose.gis.rendering.labelings/rulebasedlabeling/addelserule/)(Labeling) | 添加一个标注，用于未匹配任何过滤规则的要素。 |
| [GetEnumerator](../../aspose.gis.rendering.labelings/rulebasedlabeling/getenumerator/)() | 返回一个遍历规则的枚举器。 |

### 另见

* class [Labeling](../labeling/)
* class [LabelingRule](../labelingrule/)
* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


