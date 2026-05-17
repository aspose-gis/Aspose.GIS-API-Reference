---
title: "Rule-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Hämtar ett värde som indikerar om denna regel är "else-rule". |
| is_filter_rule | bool | r | Hämtar ett värde som indikerar om denna regel är "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Symboliserare att tillämpa på objektet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Skapar en ny regel som tillämpar en symboliserare på objektet när den inte matchar någon filterregel. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Skapar en ny regel som tillämpar en symboliserare på objektet när den inte matchar någon filterregel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Symboliserare att tillämpa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Nytt Rule-objekt. |


