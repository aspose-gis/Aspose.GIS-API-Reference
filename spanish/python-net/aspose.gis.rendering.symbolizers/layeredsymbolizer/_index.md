---
title: "Clase LayeredSymbolizer"
type: docs
weight: 20
url: /es/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Crea una nueva instancia. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | El [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) no dibuja nada y omite efectivamente el renderizado de una geometría a la que se aplica. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Determina el orden de renderizado.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            renderiza todos los simbolizadores para la entidad, luego procede a la siguiente entidad. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            renderiza todas las entidades con el simbolizador, luego procede al siguiente simbolizador. </li><br/>            </ul> |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Agrega el simbolizador especificado. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Crea una nueva instancia.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Determina el orden de renderizado.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            renderiza la entidad con todos los simbolizadores, luego procede a la siguiente entidad. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            renderiza todas las entidades con un simbolizador, luego continúa dibujando entidades al siguiente simbolizador. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Agrega el simbolizador especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | El simbolizador a agregar. |

