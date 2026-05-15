---
title: "Classe LabelingRule"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Obtient une valeur indiquant si cette règle est "else-rule". |
| is_filter_rule | bool | r | Obtient une valeur indiquant si cette règle est "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Étiquetage à appliquer à l'entité. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Crée une nouvelle règle qui applique un étiquetage à l'entité chaque fois qu'elle ne correspond à aucune règle de filtrage. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Crée une nouvelle règle qui applique un étiquetage à l'entité chaque fois qu'elle ne correspond à aucune règle de filtrage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Étiquetage à appliquer. |

**Returns**

| Type | Description |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Nouvel objet LabelingRule. |


