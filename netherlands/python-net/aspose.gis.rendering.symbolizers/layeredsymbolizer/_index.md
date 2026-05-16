---
title: "LayeredSymbolizer Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Creëert een nieuw exemplaar. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | De [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) tekent niets en slaat effectief het renderen van een geometrie waarop het wordt toegepast over. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Bepaalt de rendervolgorde.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render alle symbolizers voor het object, vervolgens doorgaan naar het volgende object. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render alle objecten met de symbolizer, vervolgens doorgaan naar de volgende symbolizer. </li><br/>            </ul> |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Voegt de opgegeven symbolizer toe. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Creëert een nieuw exemplaar.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Bepaalt de rendervolgorde.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render het object met alle symbolizers, vervolgens doorgaan naar het volgende object. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render alle objecten met een symbolizer, vervolgens doorgaan met het tekenen van objecten naar de volgende symbolizer. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Voegt de opgegeven symbolizer toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | De toe te voegen symbolizer. |

