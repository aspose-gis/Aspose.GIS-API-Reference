---
title: "Rule 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | 이 규칙이 "else-rule"인지 여부를 나타내는 값을 가져옵니다. |
| is_filter_rule | bool | r | 이 규칙이 "filter-rule"인지 여부를 나타내는 값을 가져옵니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | 피처에 적용할 심볼라이저. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | 필터 규칙과 일치하지 않을 때마다 피처에 심볼라이저를 적용하는 새 규칙을 생성합니다. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

필터 규칙과 일치하지 않을 때마다 피처에 심볼라이저를 적용하는 새 규칙을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 적용할 심볼라이저. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 새 Rule 객체. |


