---
title: "فئة Rule"
type: docs
weight: 90
url: /ar/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة "else-rule". |
| is_filter_rule | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه القاعدة "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | المُرمِّز لتطبيقه على الميزة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | ينشئ قاعدة جديدة تُطبق مُرمِّزًا على الميزة كلما لم تتطابق مع أي قاعدة تصفية. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

ينشئ قاعدة جديدة تُطبق مُرمِّزًا على الميزة كلما لم تتطابق مع أي قاعدة تصفية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | المُرمِّز للتطبيق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | كائن قاعدة جديد. |


