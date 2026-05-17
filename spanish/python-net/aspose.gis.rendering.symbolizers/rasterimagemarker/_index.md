---
title: "Clase RasterImageMarker"
type: docs
weight: 80
url: /es/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica la altura del marcador. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | especifica qué lado de la forma del marcador se alineará horizontalmente con la ubicación del punto. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el desplazamiento horizontal desde la ubicación de un punto hasta el punto de anclaje de la forma. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | El [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) no dibuja nada y omite efectivamente el renderizado de una geometría a la que se aplica. |
| opacity | double | r/w | Opacidad de la capa. El valor predeterminado es 1.0. |
| rotación | double | r/w | Especifica la rotación del símbolo alrededor de su punto central, en grados decimales.<br/>            Los valores positivos indican rotación en sentido horario, los valores negativos indican rotación en sentido antihorario. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Especifica qué lado de la forma del marcador se alineará verticalmente con la ubicación del punto. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el desplazamiento vertical desde la ubicación de un punto hasta el punto de anclaje de la forma. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el ancho del marcador. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_path | string | Ruta al archivo. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Inicializa una nueva instancia de la clase [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | El otro [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) para copiar datos de. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Una copia de esta instancia. |


