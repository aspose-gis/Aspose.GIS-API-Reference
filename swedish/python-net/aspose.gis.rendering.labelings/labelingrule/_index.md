---
title: "LabelingRule-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Hämtar ett värde som indikerar om denna regel är "else-rule". |
| is_filter_rule | bool | r | Hämtar ett värde som indikerar om denna regel är "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Etikettering att tillämpa på objektet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Skapar en ny regel som tillämpar en etikettering på objektet när den inte matchar någon filterregel. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Skapar en ny regel som tillämpar en etikettering på objektet när den inte matchar någon filterregel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Märkning att tillämpa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Nytt LabelingRule-objekt. |


