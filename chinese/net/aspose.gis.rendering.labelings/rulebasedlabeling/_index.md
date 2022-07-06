---
title: RuleBasedLabeling
second_title: Aspose.GIS for .NET API 参考
description: 根据用户定义的规则对特征应用标签
type: docs
weight: 1580
url: /zh/net/aspose.gis.rendering.labelings/rulebasedlabeling/
---
## RuleBasedLabeling class

根据用户定义的规则对特征应用标签。

```csharp
public class RuleBasedLabeling : Labeling, IReadOnlyList<LabelingRule>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RuleBasedLabeling](rulebasedlabeling)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.rendering.labelings/rulebasedlabeling/count) { get; } | 获取规则数。 |
| [Item](../../aspose.gis.rendering.labelings/rulebasedlabeling/item) { get; } | 获取指定索引处的规则。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add#add)(LabelingRule) | 添加规则。 |
| [Add](../../aspose.gis.rendering.labelings/rulebasedlabeling/add#add_1)(Func&lt;Feature, bool&gt;, Labeling) | 添加新的[`LabelingRule`](../labelingrule)。 |
| [AddElseRule](../../aspose.gis.rendering.labelings/rulebasedlabeling/addelserule)(Labeling) | 添加将应用于不匹配任何过滤规则的特征的标签。 |
| [GetEnumerator](../../aspose.gis.rendering.labelings/rulebasedlabeling/getenumerator)() | 返回一个遍历规则的枚举器。 |

### 也可以看看

* class [Labeling](../labeling)
* class [LabelingRule](../labelingrule)
* 命名空间 [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->