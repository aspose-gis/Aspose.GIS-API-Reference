---
title: "LabelingRule 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | 获取一个值，指示此规则是否为 "else-rule"。 |
| is_filter_rule | bool | r | 获取一个值，指示此规则是否为 "filter-rule"。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | 要应用于要素的标注。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | 创建一个新规则，在要素不匹配任何过滤规则时应用标注。 |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

创建一个新规则，在要素不匹配任何过滤规则时应用标注。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | 要应用的标注。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | 新的 LabelingRule 对象。 |


