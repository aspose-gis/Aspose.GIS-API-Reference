---
title: "Rule Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Bu kuralın "else-rule" olup olmadığını gösteren bir değer alır. |
| is_filter_rule | bool | r | Bu kuralın "filter-rule" olup olmadığını gösteren bir değer alır. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Özelliğe uygulanacak sembolleyici. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Filtre kuralıyla eşleşmediği her durumda bir sembolleyiciyi özelliğe uygulayan yeni bir kural oluşturur. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Filtre kuralıyla eşleşmediği her durumda bir sembolleyiciyi özelliğe uygulayan yeni bir kural oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Uygulanacak sembolleyici. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Yeni Rule nesnesi. |


