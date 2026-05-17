---
title: "Clase SimpleLine"
type: docs
weight: 120
url: /es/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | Crea una nueva instancia. |
| [SimpleLine(other)](#SimpleLine_other_2) | Inicializa una nueva instancia de la clase [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | Especifica cómo se renderizan las líneas en sus extremos. |
| color | System.Drawing.Color | r/w | Especifica el color y la transparencia asignados a la línea. |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Especifica una matriz de distancias que indica las longitudes de guiones y espacios alternados<br/>            en líneas discontinuas. |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Determina cómo se renderizan las líneas en la intersección de segmentos de línea. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | El [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) no dibuja nada y omite efectivamente el renderizado de una geometría a la que se aplica. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el desplazamiento desde la línea original.<br/>            Para una distancia positiva, el desplazamiento estará en el lado izquierdo de la línea de entrada (relativo a la dirección de la línea).<br/>            Para una distancia negativa, estará en el lado derecho. |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Especifica cómo deben dibujarse las líneas del símbolo. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el ancho de la línea. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

Crea una nueva instancia.

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

Inicializa una nueva instancia de la clase [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | El otro [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) para copiar datos de. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | Una copia de esta instancia. |


