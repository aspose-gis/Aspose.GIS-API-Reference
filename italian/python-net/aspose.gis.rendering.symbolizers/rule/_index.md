---
title: "Classe Rule"
type: docs
weight: 90
url: /it/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Restituisce un valore che indica se questa regola è "else-rule". |
| is_filter_rule | bool | r | Restituisce un valore che indica se questa regola è "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Simbolizzatore da applicare alla feature. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Crea una nuova regola che applica un simbolizzatore alla feature ogni volta che non corrisponde a nessuna regola di filtro. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Crea una nuova regola che applica un simbolizzatore alla feature ogni volta che non corrisponde a nessuna regola di filtro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Simbolizzatore da applicare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Nuovo oggetto Rule. |


