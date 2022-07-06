---
title: RuleBasedSymbolizer
second_title: Aspose.GIS for .NET API 参考
description: 根据用户定义的规则将符号器应用于特征几何
type: docs
weight: 1820
url: /zh/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---
## RuleBasedSymbolizer class

根据用户定义的规则将符号器应用于特征几何。

```csharp
public class RuleBasedSymbolizer : VectorSymbolizer, IReadOnlyList<Rule>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RuleBasedSymbolizer](rulebasedsymbolizer)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/count) { get; } | 获取规则数。 |
| [Item](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/item) { get; } | 获取指定索引处的规则。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add#add)(Rule) | 添加规则。 |
| [Add](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add#add_1)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | 添加新的[`Rule`](../rule)。 |
| [AddElseRule](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/addelserule)(VectorSymbolizer) | 添加一个符号器，该符号器将应用于与任何过滤规则不匹配的要素。 |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/rulebasedsymbolizer/getenumerator)() | 返回一个遍历规则的枚举器。 |

### 也可以看看

* class [VectorSymbolizer](../vectorsymbolizer)
* class [Rule](../rule)
* 命名空间 [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->