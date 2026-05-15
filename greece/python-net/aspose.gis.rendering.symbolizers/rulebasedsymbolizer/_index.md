---
title: "Κλάση RuleBasedSymbolizer"
type: docs
weight: 100
url: /el/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/
---

**Summary:** Applies a symbolizer to feature geometries according to user-defined rules.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RuleBasedSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RuleBasedSymbolizer()](#RuleBasedSymbolizer__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RuleBasedSymbolizer |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Το [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) δεν σχεδιάζει τίποτα και ουσιαστικά παραλείπει την απόδοση μιας γεωμετρίας στην οποία εφαρμόζεται. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(rule)](#add_rule_1) | Προσθέτει έναν κανόνα. |
| [add_else_rule(symbolizer)](#add_else_rule_symbolizer_2) | Προσθέτει έναν συμβολιστή που θα εφαρμοστεί σε χαρακτηριστικά που δεν ταιριάζουν με κανόνα φιλτραρίσματος. |


### Constructor: RuleBasedSymbolizer() {#RuleBasedSymbolizer__1}


```
 RuleBasedSymbolizer() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης RuleBasedSymbolizer

### Method: add(rule) {#add_rule_1}


```
 add(rule) 
```

Προσθέτει έναν κανόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rule | [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Κανόνας προς προσθήκη. |

### Method: add_else_rule(symbolizer) {#add_else_rule_symbolizer_2}


```
 add_else_rule(symbolizer) 
```

Προσθέτει έναν συμβολιστή που θα εφαρμοστεί σε χαρακτηριστικά που δεν ταιριάζουν με κανόνα φιλτραρίσματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Ένας συμβολιστής. |

