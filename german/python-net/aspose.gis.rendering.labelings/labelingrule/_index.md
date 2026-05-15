---
title: "LabelingRule Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Gibt einen Wert zurück, der angibt, ob diese Regel eine \"else-rule\" ist. |
| is_filter_rule | bool | r | Gibt einen Wert zurück, der angibt, ob diese Regel eine \"filter-rule\" ist. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Beschriftung, die auf das Feature angewendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Erstellt eine neue Regel, die eine Beschriftung auf das Feature anwendet, wenn es keiner Filterregel entspricht. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Erstellt eine neue Regel, die eine Beschriftung auf das Feature anwendet, wenn es keiner Filterregel entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Beschriftung, die angewendet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Neues LabelingRule-Objekt. |


