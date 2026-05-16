---
title: "LabelingRule Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Haalt een waarde op die aangeeft of deze regel een "else-rule" is. |
| is_filter_rule | bool | r | Haalt een waarde op die aangeeft of deze regel een "filter-rule" is. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Labeling toe te passen op het object. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Maakt een nieuwe regel die een labeling toepast op een object wanneer het niet overeenkomt met een filterregel. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Maakt een nieuwe regel die een labeling toepast op een object wanneer het niet overeenkomt met een filterregel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Labeling toe te passen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Nieuw LabelingRule-object. |


