---
title: "RuleBasedSymbolizer クラス"
type: docs
weight: 100
url: /ja/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | RuleBasedSymbolizer クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) は何も描画せず、適用されたジオメトリの描画を実質的にスキップします。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(rule)](#add_rule_1) | ルールを追加します。 |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | フィルタリングルールに一致しないフィーチャに適用されるシンボライザーを追加します。 |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

RuleBasedSymbolizer クラスの新しいインスタンスを初期化します。

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

ルールを追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 追加するルール。 |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

フィルタリングルールに一致しないフィーチャに適用されるシンボライザーを追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | シンボライザーです。 |

