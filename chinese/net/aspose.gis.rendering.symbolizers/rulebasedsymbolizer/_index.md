---
title: "类 RuleBasedSymbolizer"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Rendering.Symbolizers.RuleBasedSymbolizer 类。根据用户定义的规则将符号器应用于要素几何体"
type: docs
weight: 4380
url: /zh/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---
## RuleBasedSymbolizer class

根据用户自定义的规则，将符号器应用于要素几何体。

```csharp
public class RuleBasedSymbolizer : VectorSymbolizer, IReadOnlyList<Rule>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RuleBasedSymbolizer](rulebasedsymbolizer/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/count/) { get; } | 获取规则的数量。 |
| [Item](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/item/) { get; } | 获取指定索引处的规则。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/#add)(Rule) | 添加一条规则。 |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/#add_1)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | 添加新的 [`Rule`](../rule/)。 |
| [AddElseRule](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/addelserule/)(VectorSymbolizer) | 添加一个符号器，该符号器将应用于不匹配任何过滤规则的要素。 |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/getenumerator/)() | 返回一个遍历规则的枚举器。 |

### 另见

* class [VectorSymbolizer](../vectorsymbolizer/)
* class [Rule](../rule/)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


