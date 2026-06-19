---
title: "RuleBasedSymbolizer.Add"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RuleBasedSymbolizer 方法。添加新规则"
type: docs
weight: 40
url: /zh/net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/add/
---
## Add(Func&lt;Feature, bool&gt;, VectorSymbolizer) {#add_1}

添加新的 [`Rule`](../../rule/)。

```csharp
public void Add(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 过滤器 | Func`2 | 确定何时将符号化器应用于要素。 |
| 符号化器 | VectorSymbolizer | 当 *filter* 返回 true 时要应用于要素的符号化器。 |

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [VectorSymbolizer](../../vectorsymbolizer/)
* class [RuleBasedSymbolizer](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rulebasedsymbolizer/)
* assembly [Aspose.GIS](../../../)

---

## Add(Rule) {#add}

添加一条规则。

```csharp
public void Add(Rule rule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 规则 | Rule | 要添加的规则。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [Rule](../../rule/)
* class [RuleBasedSymbolizer](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rulebasedsymbolizer/)
* assembly [Aspose.GIS](../../../)


