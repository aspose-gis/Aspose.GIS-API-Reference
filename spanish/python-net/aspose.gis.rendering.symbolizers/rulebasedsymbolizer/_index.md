---
title: "Clase RuleBasedSymbolizer"
type: docs
weight: 100
url: /es/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Inicializa una nueva instancia de la clase RuleBasedSymbolizer |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | El [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) no dibuja nada y omite efectivamente el renderizado de una geometría a la que se aplica. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(rule)](#add_rule_1) | Agrega una regla. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Agrega un simbolizador que se aplicará a los elementos que no coincidan con ninguna regla de filtrado. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Inicializa una nueva instancia de la clase RuleBasedSymbolizer

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Agrega una regla.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Regla a agregar. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Agrega un simbolizador que se aplicará a los elementos que no coincidan con ninguna regla de filtrado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Un simbolizador. |

