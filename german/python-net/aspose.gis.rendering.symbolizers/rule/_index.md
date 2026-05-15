---
title: "Rule Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Gibt einen Wert zurück, der angibt, ob diese Regel eine \"else-rule\" ist. |
| is_filter_rule | bool | r | Gibt einen Wert zurück, der angibt, ob diese Regel eine \"filter-rule\" ist. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Symbolizer, der auf das Feature angewendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Erstellt eine neue Regel, die einen Symbolizer auf das Feature anwendet, wenn es keiner Filterregel entspricht. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Erstellt eine neue Regel, die einen Symbolizer auf das Feature anwendet, wenn es keiner Filterregel entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Symbolizer, der angewendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Neues Rule-Objekt. |


