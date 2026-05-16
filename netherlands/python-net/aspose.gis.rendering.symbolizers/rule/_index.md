---
title: "Rule-klasse"
type: docs
weight: 90
url: /nl/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Haalt een waarde op die aangeeft of deze regel een "else-rule" is. |
| is_filter_rule | bool | r | Haalt een waarde op die aangeeft of deze regel een "filter-rule" is. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Symbolizer die op het object moet worden toegepast. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Maakt een nieuwe regel aan die een symbolizer op het object toepast wanneer het niet overeenkomt met een filterregel. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Maakt een nieuwe regel aan die een symbolizer op het object toepast wanneer het niet overeenkomt met een filterregel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Symbolizer om toe te passen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Nieuw Rule-object. |


