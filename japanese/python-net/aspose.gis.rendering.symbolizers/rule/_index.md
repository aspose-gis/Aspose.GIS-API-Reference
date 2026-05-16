---
title: "Rule クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | このルールが "else-rule" かどうかを示す値を取得します。 |
| is_filter_rule | bool | r | このルールが "filter-rule" かどうかを示す値を取得します。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | フィーチャに適用するシンボライザ。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | フィーチャにシンボライザを適用する新しいルールを作成します（フィルタールールに一致しない場合）。 |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

フィーチャにシンボライザを適用する新しいルールを作成します（フィルタールールに一致しない場合）。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 適用するシンボライザ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 新しい Rule オブジェクト。 |


