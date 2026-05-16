---
title: "Classe Map"
type: docs
weight: 100
url: /it/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Map()](#Map__1) | Crea una nuova istanza della classe <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Crea una nuova istanza della classe <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Colore di sfondo della mappa. Predefinito a . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Specifica i limiti della mappa da renderizzare.<br/>            Se impostato a <see langword=\"null\" />, l'estensione viene calcolata durante il rendering per includere tutte le geometrie in tutti i livelli. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Altezza visiva della mappa. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Specifica il padding da aggiungere all'estensione. |
| resolution | double | r/w | Risoluzione da utilizzare per renderizzare questa mappa e per convertire tra [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Predefinita a 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) della mappa. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Larghezza visiva della mappa. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Crea un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) con colorizzatore predefinito e lo aggiunge alla mappa. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Crea un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) con simbolizzatore predefinito e lo aggiunge alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta. |
| [add(map_layer)](#add_map_layer_9) | Aggiunge un livello alla mappa. I livelli vengono renderizzati in ordine di aggiunta. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Renderizza la mappa in un file. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Renderizza la mappa in un file. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Crea una nuova istanza della classe <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Crea una nuova istanza della classe <c>Map</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Larghezza della mappa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Altezza della mappa. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una sequenza di feature da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una sequenza di feature da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Una sequenza di feature da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Uno symbolizer da utilizzare per il rendering. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Crea un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) con colorizzatore predefinito e lo aggiunge alla mappa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Un livello vettoriale da rappresentare con [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Un colorizer da utilizzare per il rendering. Se <see langword="null" />, viene usato il colorizer predefinito. |
| keep_open | bool | <see langword="true" /> per lasciare il livello raster aperto dopo che l'oggetto [Map](/psd/python-net/aspose.gis.rendering/map/) è stato eliminato;<br/>            <see langword="false" /> per eliminare il livello. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Crea un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) con simbolizzatore predefinito e lo aggiunge alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello vettoriale da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword="true" /> per lasciare il livello vettoriale aperto dopo che l'oggetto [Map](/psd/python-net/aspose.gis.rendering/map/) è stato eliminato;<br/>            <see langword="false" /> per eliminare il livello. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello vettoriale da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |
| keep_open | bool | <see langword="true" /> per lasciare il livello vettoriale aperto dopo che l'oggetto [Map](/psd/python-net/aspose.gis.rendering/map/) è stato eliminato;<br/>            <see langword="false" /> per eliminare il livello. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello vettoriale da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato il [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predefinito. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specifica un valore per un riferimento spaziale di origine (layer\\sequence) se mancante. Verrà usato null di default. |
| keep_open | bool | <see langword="true" /> per lasciare il livello aperto dopo che l'oggetto [Map](/psd/python-net/aspose.gis.rendering/map/) è stato eliminato; altrimenti, <see langword="false" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Crea e aggiunge un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) alla mappa. I livelli sono renderizzati nell'ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello vettoriale da rappresentare con [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato il [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predefinito. |
| keep_open | bool | <see langword="true" /> per lasciare il livello aperto dopo che l'oggetto [Map](/psd/python-net/aspose.gis.rendering/map/) è stato eliminato; altrimenti, <see langword="false" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Aggiunge un livello alla mappa. I livelli vengono renderizzati in ordine di aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Il livello da aggiungere. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Renderizza la mappa in un file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_path | string | Percorso del file di output. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer da utilizzare. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Renderizza la mappa in un file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file di output. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer da utilizzare. |

