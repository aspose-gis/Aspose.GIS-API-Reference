---
title: "RuleBasedSymbolizer Класс"
type: docs
weight: 100
url: /ru/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Инициализирует новый экземпляр класса RuleBasedSymbolizer |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Элемент [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ничего не рисует и фактически пропускает отрисовку геометрии, к которой он применён. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(rule)](#add_rule_1) | Добавляет правило. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Добавляет символизатор, который будет применяться к объектам, которые не соответствуют ни одному правилу фильтрации. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Инициализирует новый экземпляр класса RuleBasedSymbolizer

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Добавляет правило.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Правило для добавления. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Добавляет символизатор, который будет применяться к объектам, которые не соответствуют ни одному правилу фильтрации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Символизатор. |

