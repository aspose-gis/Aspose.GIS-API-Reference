---
title: "LabelingRule クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | このルールが "else-rule" かどうかを示す値を取得します。 |
| is_filter_rule | bool | r | このルールが "filter-rule" かどうかを示す値を取得します。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | フィーチャに適用するラベリングです。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | フィルタールールに一致しない場合に、フィーチャにラベリングを適用する新しいルールを作成します。 |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

フィルタールールに一致しない場合に、フィーチャにラベリングを適用する新しいルールを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | 適用するラベリング。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | 新しい LabelingRule オブジェクト。 |


