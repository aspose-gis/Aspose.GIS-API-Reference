---
title: "LabelingRule 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | 이 규칙이 "else-rule"인지 여부를 나타내는 값을 가져옵니다. |
| is_filter_rule | bool | r | 이 규칙이 "filter-rule"인지 여부를 나타내는 값을 가져옵니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | 피처에 적용할 라벨링입니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | 필터 규칙과 일치하지 않을 때마다 피처에 라벨링을 적용하는 새 규칙을 생성합니다. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

필터 규칙과 일치하지 않을 때마다 피처에 라벨링을 적용하는 새 규칙을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | 적용할 라벨링. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | 새 LabelingRule 객체. |


