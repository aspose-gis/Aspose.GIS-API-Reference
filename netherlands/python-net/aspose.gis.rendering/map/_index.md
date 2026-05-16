---
title: "Map Klasse"
type: docs
weight: 100
url: /nl/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Map()](#Map__1) | Creëert een nieuw exemplaar van de <c>Map</c> klasse. |
| [Map(width, height)](#Map_width_height_2) | Creëert een nieuw exemplaar van de <c>Map</c> klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Achtergrondkleur van de kaart. Standaard is . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Specificeert de grenzen van de kaart om weer te geven.<br/>            Als ingesteld op <see langword=\"null\" />, wordt de omvang berekend tijdens het renderen om alle geometrieën in alle lagen op te nemen. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuele hoogte van de kaart. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Specificeert opvulling die aan de omvang moet worden toegevoegd. |
| resolution | double | r/w | Resolutie die gebruikt wordt om deze kaart weer te geven en om te converteren tussen [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Standaard is 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) van de kaart. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuele breedte van de kaart. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Creëert een [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) met standaard colorizer en voegt deze toe aan de kaart. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Creëert een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) met standaard symbolizer en voegt deze toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging. |
| [add(map_layer)](#add_map_layer_9) | Voegt een laag toe aan de kaart. Lagen worden gerenderd in toevoegingsvolgorde. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Rendert de kaart naar een bestand. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Rendert de kaart naar een bestand. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Creëert een nieuw exemplaar van de <c>Map</c> klasse.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Creëert een nieuw exemplaar van de <c>Map</c> klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Breedte van de kaart. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Hoogte van de kaart. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Een reeks kenmerken om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Een reeks kenmerken om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Een reeks kenmerken om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor het renderen. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Creëert een [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) met standaard colorizer en voegt deze toe aan de kaart.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Een vectorlaag om te representeren door [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Een colorizer om te gebruiken voor het renderen. Als <see langword="null" />, wordt de standaard colorizer gebruikt. |
| keep_open | bool | <see langword="true" /> om de rasterlaag open te laten nadat het [Map](/psd/python-net/aspose.gis.rendering/map/) object is verwijderd;<br/>            <see langword="false" /> om de laag te verwijderen. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Creëert een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) met standaard symbolizer en voegt deze toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een vectorlaag om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword="true" /> om de vectorlaag open te laten nadat het [Map](/psd/python-net/aspose.gis.rendering/map/) object is verwijderd;<br/>            <see langword="false" /> om de laag te verwijderen. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een vectorlaag om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |
| keep_open | bool | <see langword="true" /> om de vectorlaag open te laten nadat het [Map](/psd/python-net/aspose.gis.rendering/map/) object is verwijderd;<br/>            <see langword="false" /> om de laag te verwijderen. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een vectorlaag om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt de standaard [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specificeert een waarde voor een bron ruimtelijke referentie (laag\reeks) als deze ontbreekt. Standaard null wordt gebruikt. |
| keep_open | bool | <see langword="true" /> om de laag open te laten nadat het [Map](/psd/python-net/aspose.gis.rendering/map/) object is verwijderd; anders <see langword="false" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Creëert en voegt een [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) toe aan de kaart. Lagen worden gerenderd in volgorde van toevoeging.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een vectorlaag om te representeren door [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt de standaard [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |
| keep_open | bool | <see langword="true" /> om de laag open te laten nadat het [Map](/psd/python-net/aspose.gis.rendering/map/) object is verwijderd; anders <see langword="false" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Voegt een laag toe aan de kaart. Lagen worden gerenderd in toevoegingsvolgorde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | De laag die moet worden toegevoegd. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Rendert de kaart naar een bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_pad | string | Pad naar het uitvoerbestand. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer om te gebruiken. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Rendert de kaart naar een bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het uitvoerbestand. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer om te gebruiken. |

