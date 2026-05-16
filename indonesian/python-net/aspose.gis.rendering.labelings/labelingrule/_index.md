---
title: "Kelas LabelingRule"
type: docs
weight: 30
url: /id/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Mendapatkan nilai yang menunjukkan apakah aturan ini adalah "else-rule". |
| is_filter_rule | bool | r | Mendapatkan nilai yang menunjukkan apakah aturan ini adalah "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Label yang diterapkan pada fitur. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Membuat aturan baru yang menerapkan label pada fitur setiap kali tidak cocok dengan aturan filter apa pun. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Membuat aturan baru yang menerapkan label pada fitur setiap kali tidak cocok dengan aturan filter apa pun.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Labeling untuk diterapkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Objek LabelingRule baru. |


