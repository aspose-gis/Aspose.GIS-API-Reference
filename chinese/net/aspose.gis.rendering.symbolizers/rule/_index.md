---
title: "类 Rule"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Rendering.Symbolizers.Rule 类。用于 RuleBasedSymbolizer 的用户定义规则"
type: docs
weight: 4370
url: /zh/net/aspose.gis.rendering.symbolizers/rule/
---
## Rule class

用于[`RuleBasedSymbolizer`](../rulebasedsymbolizer/)的用户定义规则。

```csharp
public class Rule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Filter](../../aspose.gis.rendering.symbolizers/rule/filter/) { get; } | 确定是否应将 "filter-rule" 应用于要素的符号器。如果返回 `true` 则使用该符号器；否则跳过要素。 |
| [IsElseRule](../../aspose.gis.rendering.symbolizers/rule/iselserule/) { get; } | 获取一个值，指示此规则是否为 "else-rule"。 |
| [IsFilterRule](../../aspose.gis.rendering.symbolizers/rule/isfilterrule/) { get; } | 获取一个值，指示此规则是否为 "filter-rule"。 |
| [Symbolizer](../../aspose.gis.rendering.symbolizers/rule/symbolizer/) { get; } | 要应用于要素的符号器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateElseRule](../../aspose.gis.rendering.symbolizers/rule/createelserule/)(VectorSymbolizer) | 创建新规则，当要素不匹配任何过滤规则时，将符号器应用于要素。 |
| static [CreateFilterRule](../../aspose.gis.rendering.symbolizers/rule/createfilterrule/)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | 创建新规则，当要素通过过滤时，将符号器应用于要素。 |

### 另见

* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


