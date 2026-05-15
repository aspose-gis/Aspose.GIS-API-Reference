---
title: "Κλάση Rule"
type: docs
weight: 90
url: /el/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο κανόνας είναι "else-rule". |
| is_filter_rule | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο κανόνας είναι "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Συμβολιστής που θα εφαρμοστεί στο χαρακτηριστικό. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Δημιουργεί νέο κανόνα που εφαρμόζει έναν συμβολιστή στο χαρακτηριστικό όποτε δεν ταιριάζει με κανέναν κανόνα φίλτρου. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Δημιουργεί νέο κανόνα που εφαρμόζει έναν συμβολιστή στο χαρακτηριστικό όποτε δεν ταιριάζει με κανέναν κανόνα φίλτρου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Συμβολιστής προς εφαρμογή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Νέο αντικείμενο Rule. |


