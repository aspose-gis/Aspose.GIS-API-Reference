---
title: "LabelingRule Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο κανόνας είναι "else-rule". |
| is_filter_rule | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο κανόνας είναι "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Labeling για εφαρμογή στο feature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Δημιουργεί νέο κανόνα που εφαρμόζει μια ετικετοποίηση στο feature όποτε δεν ταιριάζει με κανέναν filter rule. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Δημιουργεί νέο κανόνα που εφαρμόζει μια ετικετοποίηση στο feature όποτε δεν ταιριάζει με κανέναν filter rule.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Ετικετοποίηση για εφαρμογή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Νέο αντικείμενο LabelingRule. |


