---
title: "فئة LabelingRule"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة "else-rule". |
| is_filter_rule | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | التسمية لتطبيقها على الميزة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | ينشئ قاعدة جديدة تطبق تسمية على الميزة كلما لم تتطابق مع أي قاعدة تصفية. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

ينشئ قاعدة جديدة تطبق تسمية على الميزة كلما لم تتطابق مع أي قاعدة تصفية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | التصنيف للتطبيق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | كائن LabelingRule جديد. |


