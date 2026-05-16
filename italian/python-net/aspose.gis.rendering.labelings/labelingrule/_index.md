---
title: "Classe LabelingRule"
type: docs
weight: 30
url: /it/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Restituisce un valore che indica se questa regola è "else-rule". |
| is_filter_rule | bool | r | Restituisce un valore che indica se questa regola è "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Etichettatura da applicare alla feature. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Crea una nuova regola che applica un'etichettatura alla feature ogni volta che non corrisponde a nessuna regola di filtro. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Crea una nuova regola che applica un'etichettatura alla feature ogni volta che non corrisponde a nessuna regola di filtro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Etichettatura da applicare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Nuovo oggetto LabelingRule. |


