---
title: "Класс Rule"
type: docs
weight: 90
url: /ru/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Возвращает значение, указывающее, является ли это правило "else-rule". |
| is_filter_rule | bool | r | Возвращает значение, указывающее, является ли это правило "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Символизатор, применяемый к объекту. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Создаёт новое правило, которое применяет символизатор к объекту, когда он не соответствует ни одному правилу фильтра. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Создаёт новое правило, которое применяет символизатор к объекту, когда он не соответствует ни одному правилу фильтра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Символизатор для применения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Новый объект Rule. |


