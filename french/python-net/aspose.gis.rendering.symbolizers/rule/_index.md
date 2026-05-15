---
title: "Classe Rule"
type: docs
weight: 90
url: /fr/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Obtient une valeur indiquant si cette règle est "else-rule". |
| is_filter_rule | bool | r | Obtient une valeur indiquant si cette règle est "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Symboliseur à appliquer à l'entité. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Crée une nouvelle règle qui applique un symboliseur à l'entité chaque fois qu'elle ne correspond à aucune règle de filtre. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Crée une nouvelle règle qui applique un symboliseur à l'entité chaque fois qu'elle ne correspond à aucune règle de filtre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Symboliseur à appliquer. |

**Returns**

| Type | Description |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Nouvel objet Rule. |


