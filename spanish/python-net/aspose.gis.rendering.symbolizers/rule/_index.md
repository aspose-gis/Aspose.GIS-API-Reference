---
title: "Clase Rule"
type: docs
weight: 90
url: /es/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Obtiene un valor que indica si esta regla es "else-rule". |
| is_filter_rule | bool | r | Obtiene un valor que indica si esta regla es "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Simbolizador para aplicar a la entidad. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Crea una nueva regla que aplica un simbolizador a la entidad siempre que no coincida con ninguna regla de filtro. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Crea una nueva regla que aplica un simbolizador a la entidad siempre que no coincida con ninguna regla de filtro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Simbolizador para aplicar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Nuevo objeto Rule. |


