---
title: "Κλάση LayeredSymbolizer"
type: docs
weight: 20
url: /el/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Δημιουργεί νέο αντικείμενο. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Το [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) δεν σχεδιάζει τίποτα και ουσιαστικά παραλείπει την απόδοση μιας γεωμετρίας στην οποία εφαρμόζεται. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Καθορίζει τη σειρά απόδοσης.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            απεικονίζει όλους τους συμβολιστές για το χαρακτηριστικό, μετά προχωρά στο επόμενο χαρακτηριστικό. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            απεικονίζει όλα τα χαρακτηριστικά με τον συμβολιστή, μετά προχωρά στον επόμενο συμβολιστή. </li><br/>            </ul> |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Προσθέτει τον καθορισμένο συμβολιστή. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Δημιουργεί νέο αντικείμενο.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Καθορίζει τη σειρά απόδοσης.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            απεικονίζει το χαρακτηριστικό με όλους τους συμβολιστές, μετά προχωρά στο επόμενο χαρακτηριστικό. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            απεικονίζει όλα τα χαρακτηριστικά με έναν συμβολιστή, μετά προχωρά στη σχεδίαση χαρακτηριστικών προς τον επόμενο συμβολιστή. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Προσθέτει τον καθορισμένο συμβολιστή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Ο συμβολιστής προς προσθήκη. |

