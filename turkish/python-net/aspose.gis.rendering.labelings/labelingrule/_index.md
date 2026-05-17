---
title: "LabelingRule Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Bu kuralın "else-rule" olup olmadığını gösteren bir değer alır. |
| is_filter_rule | bool | r | Bu kuralın "filter-rule" olup olmadığını gösteren bir değer alır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Özelliğe uygulanacak etiketleme. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Filtre kuralı ile eşleşmediğinde özelliğe bir etiketleme uygulayan yeni bir kural oluşturur. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Filtre kuralı ile eşleşmediğinde özelliğe bir etiketleme uygulayan yeni bir kural oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Uygulanacak etiketleme. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Yeni LabelingRule nesnesi. |


