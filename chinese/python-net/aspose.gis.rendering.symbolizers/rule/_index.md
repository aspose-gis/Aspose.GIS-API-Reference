---
title: "Rule 类"
type: docs
weight: 90
url: /zh/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | 获取一个值，指示此规则是否为 "else-rule"。 |
| is_filter_rule | bool | r | 获取一个值，指示此规则是否为 "filter-rule"。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | 要应用于要素的符号化器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | 创建新的规则，在要素不匹配任何过滤规则时将符号化器应用于要素。 |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

创建新的规则，在要素不匹配任何过滤规则时将符号化器应用于要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 要应用的符号化器。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 新的 Rule 对象。 |


