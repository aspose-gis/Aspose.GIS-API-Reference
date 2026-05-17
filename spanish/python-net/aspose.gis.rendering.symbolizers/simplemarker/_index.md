---
title: "Clase SimpleMarker"
type: docs
weight: 130
url: /es/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | Inicializa una nueva instancia de la clase [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
| [SimpleMarker(other)](#SimpleMarker_other_2) | Inicializa una nueva instancia de la clase [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | Especifica el color y la transparencia para el relleno. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | Especifica qué lado de la forma del marcador se alineará horizontalmente con la ubicación del punto. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el desplazamiento horizontal desde la ubicación de un punto hasta el punto de anclaje de la forma. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | El [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) no dibuja nada y omite efectivamente el renderizado de una geometría a la que se aplica. |
| rotación | double | r/w | Especifica la rotación del símbolo alrededor de su punto central, en grados decimales.<br/>            Los valores positivos indican rotación en sentido horario, los valores negativos indican rotación en sentido antihorario. |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | Especifica la forma del marcador. |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el tamaño del marcador. |
| stroke_color | System.Drawing.Color | r/w | Especifica el color y la transparencia asignados a la línea. |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Especifica una matriz de distancias que indica las longitudes de guiones y espacios alternados<br/>            en líneas discontinuas. |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Determina cómo se renderizan las líneas en la intersección de segmentos de línea. |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Especifica cómo deben dibujarse las líneas del símbolo. |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el ancho de la línea. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Especifica qué lado de la forma del marcador se alineará verticalmente con la ubicación del punto. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el desplazamiento vertical desde la ubicación de un punto hasta el punto de anclaje de la forma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

Inicializa una nueva instancia de la clase [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

Inicializa una nueva instancia de la clase [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | El otro [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) del cual copiar datos. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Una copia de esta instancia. |


