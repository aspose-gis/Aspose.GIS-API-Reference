---
title: "RuleBasedSymbolizer 类"
type: docs
weight: 100
url: /zh/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | 初始化 RuleBasedSymbolizer 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 该 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 不绘制任何内容，并有效地跳过对其所应用的几何体的渲染。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(rule)](#add_rule_1) | 添加规则。 |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | 添加一个符号化器，该符号化器将应用于不匹配任何过滤规则的要素。 |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

初始化 RuleBasedSymbolizer 类的新实例

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

添加规则。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 要添加的规则。 |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

添加一个符号化器，该符号化器将应用于不匹配任何过滤规则的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 一个符号化器。 |

