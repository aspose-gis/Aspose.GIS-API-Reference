---
title: "Clase Map"
type: docs
weight: 100
url: /es/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Map()](#Map__1) | Crea una nueva instancia de la clase <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Crea una nueva instancia de la clase <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Color de fondo del mapa. Por defecto es . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Especifica los límites del mapa a renderizar.<br/>            Si se establece en <see langword=\"null\" />, la extensión se calcula durante el renderizado para incluir todas las geometrías en todas las capas. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Altura visual del mapa. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Especifica el relleno a añadir a la extensión. |
| resolution | double | r/w | Resolución a usar para renderizar este mapa y convertir entre [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Por defecto es 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) del mapa. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anchura visual del mapa. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Crea un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) con el colorizador predeterminado y lo añade al mapa. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Crea un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) con el simbolizador predeterminado y lo añade al mapa. Las capas se renderizan en orden de adición. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición. |
| [add(map_layer)](#add_map_layer_9) | Agrega una capa al mapa. Las capas se renderizan en orden de adición. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Renderiza el mapa en un archivo. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Renderiza el mapa en un archivo. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Crea una nueva instancia de la clase <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Crea una nueva instancia de la clase <c>Map</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Ancho del mapa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Altura del mapa. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una secuencia de características a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una secuencia de características a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una secuencia de características a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador para usar en el renderizado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Crea un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) con el colorizador predeterminado y lo añade al mapa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Una capa vectorial a representar mediante [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Un colorizador para usar en el renderizado. Si <see langword=\"null\" />, se usa el colorizador predeterminado. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa raster abierta después de que el objeto [Map](/psd/python-net/aspose.gis.rendering/map/) sea eliminado;<br/>            <see langword=\"false\" /> para eliminar la capa. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Crea un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) con el simbolizador predeterminado y lo añade al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa vectorial a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa vectorial abierta después de que el objeto [Map](/psd/python-net/aspose.gis.rendering/map/) sea eliminado;<br/>            <see langword=\"false\" /> para eliminar la capa. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa vectorial a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa vectorial abierta después de que el objeto [Map](/psd/python-net/aspose.gis.rendering/map/) sea eliminado;<br/>            <see langword=\"false\" /> para eliminar la capa. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa vectorial a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará el [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predeterminado. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Especifica un valor para una referencia espacial de origen (capa\\secuencia) si falta. Se usará null por defecto. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [Map](/psd/python-net/aspose.gis.rendering/map/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Crea y añade un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa vectorial a representar mediante [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará el [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predeterminado. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [Map](/psd/python-net/aspose.gis.rendering/map/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Agrega una capa al mapa. Las capas se renderizan en orden de adición.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | La capa a agregar. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Renderiza el mapa en un archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_path | string | Ruta al archivo de salida. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderizador a usar. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Renderiza el mapa en un archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo de salida. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderizador a usar. |

