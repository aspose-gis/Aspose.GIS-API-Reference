---
title: "Map klass"
type: docs
weight: 100
url: /sv/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Map()](#Map__1) | Skapar en ny instans av <c>Map</c>-klassen. |
| [Map(width, height)](#Map_width_height_2) | Skapar en ny instans av <c>Map</c>-klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | läs/skriv | Bakgrundsfärg för kartan. Standard är . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Anger gränserna för kartan som ska renderas.<br/>            Om den är satt till <see langword="null" />, beräknas omfattningen under rendering för att inkludera alla geometrier i alla lager. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuell höjd för kartan. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger utfyllnad att lägga till i omfattningen. |
| resolution | double | r/w | Upplösning som ska användas för att rendera denna karta och för att konvertera mellan [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Standard är 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) för kartan. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuell bredd för kartan. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Skapar en [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) med standard‑colorizer och lägger till den i kartan. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Skapar en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) med standard‑symbolizer och lägger till den i kartan. Lager renderas i tilläggsordning. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning. |
| [add(map_layer)](#add_map_layer_9) | Lägger till ett lager i kartan. Lager renderas i tilläggsordning. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Renderar kartan till en fil. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Renderar kartan till en fil. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Skapar en ny instans av <c>Map</c>-klassen.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Skapar en ny instans av <c>Map</c>-klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Bredd på kartan. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Höjd på kartan. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | En sekvens av funktioner att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | En sekvens av funktioner att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | En sekvens av funktioner att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symboliserare att använda för rendering. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kommer att användas. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Skapar en [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) med standard‑colorizer och lägger till den i kartan.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Ett vektorlager att representera med [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | En färgsättare att använda för rendering. Om <see langword=\"null\" />, används standardfärgsättare. |
| keep_open | bool | <see langword=\"true\" /> för att lämna rasterlagret öppet efter att [Map](/psd/python-net/aspose.gis.rendering/map/)‑objektet har frigjorts;<br/>            <see langword=\"false\" /> för att frigöra lagret. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Skapar en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) med standard‑symbolizer och lägger till den i kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett vektorlager att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> för att lämna vektorlager öppet efter att [Map](/psd/python-net/aspose.gis.rendering/map/)‑objektet har frigjorts;<br/>            <see langword=\"false\" /> för att frigöra lagret. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett vektorlager att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |
| keep_open | bool | <see langword=\"true\" /> för att lämna vektorlager öppet efter att [Map](/psd/python-net/aspose.gis.rendering/map/)‑objektet har frigjorts;<br/>            <see langword=\"false\" /> för att frigöra lagret. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett vektorlager att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, används standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Anger ett värde för en källspatial referens (lager\\sekvens) om den saknas. Standard‑null kommer att användas. |
| keep_open | bool | <see langword=\"true\" /> för att lämna lagret öppet efter att [Map](/psd/python-net/aspose.gis.rendering/map/)‑objektet har frigjorts; annars <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Skapar och lägger till en [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) till kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett vektorlager att representera med [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, används standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| keep_open | bool | <see langword=\"true\" /> för att lämna lagret öppet efter att [Map](/psd/python-net/aspose.gis.rendering/map/)‑objektet har frigjorts; annars <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Lägger till ett lager i kartan. Lager renderas i tilläggsordning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Lagret som ska läggas till. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Renderar kartan till en fil.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| utdata_sökväg | string | Sökväg till utdatafilen. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderare att använda. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Renderar kartan till en fil.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdatafilen. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderare att använda. |

