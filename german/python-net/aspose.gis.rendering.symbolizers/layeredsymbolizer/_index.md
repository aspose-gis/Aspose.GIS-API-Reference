---
title: "LayeredSymbolizer Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Erstellt eine neue Instanz. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Der [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) zeichnet nichts und überspringt effektiv das Rendern einer Geometrie, auf die er angewendet wird. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Bestimmt die Renderreihenfolge.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            rendert alle Symbolisierer für das Feature, dann zum nächsten Feature fortfahren. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            rendert alle Features mit dem Symbolisierer, dann zum nächsten Symbolisierer fortfahren. </li><br/>            </ul> |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Fügt den angegebenen Symbolisierer hinzu. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Erstellt eine neue Instanz.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Bestimmt die Renderreihenfolge.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            rendert das Feature mit allen Symbolisierern und fährt dann mit dem nächsten Feature fort. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            rendert alle Features mit einem Symbolisierer und fährt dann mit dem Zeichnen der Features zum nächsten Symbolisierer fort. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Fügt den angegebenen Symbolisierer hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Der hinzuzufügende Symbolisierer. |

