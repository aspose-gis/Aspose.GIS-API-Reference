---
title: "RuleBasedSymbolizer Klasse"
type: docs
weight: 100
url: /nl/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Initialiseert een nieuwe instantie van de RuleBasedSymbolizer klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | De [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) tekent niets en slaat effectief het renderen van een geometrie waarop het wordt toegepast over. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(rule)](#add_rule_1) | Voegt een regel toe. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Voegt een symbolizer toe die wordt toegepast op features die niet overeenkomen met een filterregel. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Initialiseert een nieuwe instantie van de RuleBasedSymbolizer klasse

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Voegt een regel toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Regel om toe te voegen. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Voegt een symbolizer toe die wordt toegepast op features die niet overeenkomen met een filterregel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Een symbolizer. |

