---
title: "Clase LabelingRule"
type: docs
weight: 30
url: /es/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Obtiene un valor que indica si esta regla es "else-rule". |
| is_filter_rule | bool | r | Obtiene un valor que indica si esta regla es "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Etiquetado a aplicar a la entidad. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Crea una nueva regla que aplica un etiquetado a la entidad siempre que no coincida con ninguna regla de filtro. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Crea una nueva regla que aplica un etiquetado a la entidad siempre que no coincida con ninguna regla de filtro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Etiquetado a aplicar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Nuevo objeto LabelingRule. |


