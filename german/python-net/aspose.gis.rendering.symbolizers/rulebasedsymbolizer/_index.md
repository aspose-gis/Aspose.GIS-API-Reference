---
title: "RuleBasedSymbolizer Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Initialisiert eine neue Instanz der RuleBasedSymbolizer Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Der [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) zeichnet nichts und überspringt effektiv das Rendern einer Geometrie, auf die er angewendet wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(rule)](#add_rule_1) | Fügt eine Regel hinzu. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Fügt einen Symbolizer hinzu, der auf Features angewendet wird, die keiner Filterregel entsprechen. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Initialisiert eine neue Instanz der RuleBasedSymbolizer Klasse

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Fügt eine Regel hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Hinzu zufügende Regel. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Fügt einen Symbolizer hinzu, der auf Features angewendet wird, die keiner Filterregel entsprechen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Ein Symbolizer. |

