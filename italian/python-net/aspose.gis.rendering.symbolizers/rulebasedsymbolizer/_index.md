---
title: "Classe RuleBasedSymbolizer"
type: docs
weight: 100
url: /it/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Inizializza una nuova istanza della classe RuleBasedSymbolizer |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Il [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) non disegna nulla e salta efficacemente il rendering di una geometria a cui è applicato. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(rule)](#add_rule_1) | Aggiunge una regola. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Aggiunge un simbolizzatore che verrà applicato alle feature che non corrispondono a nessuna regola di filtraggio. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Inizializza una nuova istanza della classe RuleBasedSymbolizer

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Aggiunge una regola.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Regola da aggiungere. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Aggiunge un simbolizzatore che verrà applicato alle feature che non corrispondono a nessuna regola di filtraggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Un simbolizzatore. |

