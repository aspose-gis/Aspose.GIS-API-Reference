---
title: "RuleBasedLabeling.Add"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RuleBasedLabeling 方法。添加新的 LabelingRule"
type: docs
weight: 40
url: /zh/net/aspose.gis.rendering.labelings/rulebasedlabeling/add/
---
## Add(Func&lt;Feature, bool&gt;, Labeling) {#add_1}

添加新的 [`LabelingRule`](../../labelingrule/)。

```csharp
public void Add(Func<Feature, bool> filter, Labeling labeling)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 过滤器 | Func`2 | 确定何时应将标签应用于特征。 |
| 标注 | 标注 | 当 *filter* 返回 true 时对特征应用的标签。 |

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [Labeling](../../labeling/)
* class [RuleBasedLabeling](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling/)
* assembly [Aspose.GIS](../../../)

---

## Add(LabelingRule) {#add}

添加一条规则。

```csharp
public void Add(LabelingRule rule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 规则 | LabelingRule | 要添加的规则。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [LabelingRule](../../labelingrule/)
* class [RuleBasedLabeling](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../rulebasedlabeling/)
* assembly [Aspose.GIS](../../../)


