---
title: "RuleBasedSymbolizer 클래스"
type: docs
weight: 100
url: /ko/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | RuleBasedSymbolizer 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 해당 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 은 아무것도 그리지 않으며 적용된 기하학의 렌더링을 효과적으로 건너뜁니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(rule)](#add_rule_1) | 규칙을 추가합니다. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | 필터링 규칙과 일치하지 않는 피처에 적용될 심볼라이저를 추가합니다. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

RuleBasedSymbolizer 클래스의 새 인스턴스를 초기화합니다.

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

규칙을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | 추가할 규칙. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

필터링 규칙과 일치하지 않는 피처에 적용될 심볼라이저를 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 심볼라이저. |

