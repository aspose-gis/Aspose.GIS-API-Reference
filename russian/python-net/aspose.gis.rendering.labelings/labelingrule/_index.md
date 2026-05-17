---
title: "Класс LabelingRule"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Возвращает значение, указывающее, является ли это правило "else-rule". |
| is_filter_rule | bool | r | Возвращает значение, указывающее, является ли это правило "filter-rule". |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | Подпись, применяемая к объекту. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | Создаёт новое правило, которое применяет подпись к объекту, когда он не соответствует ни одному правилу фильтра. |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

Создаёт новое правило, которое применяет подпись к объекту, когда он не соответствует ни одному правилу фильтра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | Маркировка для применения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | Новый объект LabelingRule. |


