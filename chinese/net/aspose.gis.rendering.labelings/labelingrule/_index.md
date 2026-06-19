---
title: "类 LabelingRule"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Rendering.Labelings.LabelingRule 类。用于 RuleBasedLabeling 的用户自定义规则"
type: docs
weight: 4080
url: /zh/net/aspose.gis.rendering.labelings/labelingrule/
---
## LabelingRule class

用于 [`RuleBasedLabeling`](../rulebasedlabeling/) 的用户定义规则。

```csharp
public class LabelingRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Filter](../../aspose.gis.rendering.labelings/labelingrule/filter/) { get; } | 确定 \"filter-rule\" 是否应对要素应用标注。如果返回 `true` 则使用标注；否则，跳过该要素。 |
| [IsElseRule](../../aspose.gis.rendering.labelings/labelingrule/iselserule/) { get; } | 获取一个值，指示此规则是否为 \"else-rule\"。 |
| [IsFilterRule](../../aspose.gis.rendering.labelings/labelingrule/isfilterrule/) { get; } | 获取一个值，指示此规则是否为 \"filter-rule\"。 |
| [Labeling](../../aspose.gis.rendering.labelings/labelingrule/labeling/) { get; } | 要应用于要素的标注。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateElseRule](../../aspose.gis.rendering.labelings/labelingrule/createelserule/)(Labeling) | 创建新规则，当要素不匹配任何过滤规则时对其应用标注。 |
| static [CreateFilterRule](../../aspose.gis.rendering.labelings/labelingrule/createfilterrule/)(Func&lt;Feature, bool&gt;, Labeling) | 创建新规则，当要素通过过滤时对其应用标注。 |

### 另见

* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


