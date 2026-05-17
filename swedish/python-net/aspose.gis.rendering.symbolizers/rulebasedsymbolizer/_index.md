---
title: "RuleBasedSymbolizer-klass"
type: docs
weight: 100
url: /sv/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Initierar en ny instans av RuleBasedSymbolizer-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Den [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ritar ingenting och hoppar effektivt över rendering av en geometri som den tillämpas på. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(rule)](#add_rule_1) | Lägger till en regel. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Lägger till en symboliserare som kommer att tillämpas på funktioner som inte matchar någon filtreringsregel. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Initierar en ny instans av RuleBasedSymbolizer-klassen

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Lägger till en regel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Regel att lägga till. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Lägger till en symboliserare som kommer att tillämpas på funktioner som inte matchar någon filtreringsregel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | En symboliserare. |

