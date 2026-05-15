---
title: "RuleBasedSymbolizer Classe"
type: docs
weight: 100
url: /fr/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Initialise une nouvelle instance de la classe RuleBasedSymbolizer |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Le [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ne dessine rien et saute effectivement le rendu d'une géométrie à laquelle il est appliqué. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(rule)](#add_rule_1) | Ajoute une règle. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Ajoute un symboliseur qui sera appliqué aux entités qui ne correspondent à aucune règle de filtrage. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Initialise une nouvelle instance de la classe RuleBasedSymbolizer

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Ajoute une règle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Règle à ajouter. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Ajoute un symboliseur qui sera appliqué aux entités qui ne correspondent à aucune règle de filtrage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Un symboliseur. |

