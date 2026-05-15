---
title: "Map Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Map()](#Map__1) | Erstellt eine neue Instanz der <c>Map</c>-Klasse. |
| [Map(width, height)](#Map_width_height_2) | Erstellt eine neue Instanz der <c>Map</c>-Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Hintergrundfarbe der Karte. Standard ist . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Gibt die Grenzen der zu rendernden Karte an.<br/>            Wenn auf <see langword="null" /> gesetzt, wird der Umfang während des Renderns berechnet, um alle Geometrien in allen Ebenen einzuschließen. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuelle Höhe der Karte. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Gibt den Abstand an, der zum Umfang hinzugefügt werden soll. |
| resolution | double | r/w | Auflösung, die zum Rendern dieser Karte und zum Konvertieren zwischen [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) verwendet wird. Standard ist 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) der Karte. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Visuelle Breite der Karte. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Erstellt ein [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) mit Standard‑Colorizer und fügt es der Karte hinzu. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Erstellt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) mit Standard‑Symbolizer und fügt es der Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [add(map_layer)](#add_map_layer_9) | Fügt der Karte eine Ebene hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Rendert die Karte in eine Datei. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Rendert die Karte in eine Datei. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Erstellt eine neue Instanz der <c>Map</c>-Klasse.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Erstellt eine neue Instanz der <c>Map</c>-Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Breite der Karte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Höhe der Karte. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Eine Feature‑Sequenz, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Eine Feature‑Sequenz, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Eine Feature‑Sequenz, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Erstellt ein [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) mit Standard‑Colorizer und fügt es der Karte hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Eine Vektorebene, die durch [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) dargestellt wird. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Ein Colorizer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standard‑Colorizer verwendet. |
| keep_open | bool | <see langword=\"true\" /> um die Rasterebene nach dem Entsorgen des [Map](/psd/python-net/aspose.gis.rendering/map/)‑Objekts offen zu lassen;<br/>            <see langword=\"false\" /> um die Ebene zu entsorgen. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Erstellt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) mit Standard‑Symbolizer und fügt es der Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Vektorebene, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| keep_open | bool | <see langword=\"true\" /> um die Vektorebene nach dem Entsorgen des [Map](/psd/python-net/aspose.gis.rendering/map/)‑Objekts offen zu lassen;<br/>            <see langword=\"false\" /> um die Ebene zu entsorgen. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Vektorebene, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |
| keep_open | bool | <see langword=\"true\" /> um die Vektorebene nach dem Entsorgen des [Map](/psd/python-net/aspose.gis.rendering/map/)‑Objekts offen zu lassen;<br/>            <see langword=\"false\" /> um die Ebene zu entsorgen. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Vektorebene, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird das Standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Gibt einen Wert für eine Quell‑räumliche Referenz (Ebene\\Sequenz) an, falls diese fehlt. Standard‑null wird verwendet. |
| keep_open | bool | <see langword=\"true\" /> um die Ebene nach dem Entsorgen des [Map](/psd/python-net/aspose.gis.rendering/map/)‑Objekts offen zu lassen; andernfalls <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Erstellt und fügt ein [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) zur Karte hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Vektorebene, die durch [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dargestellt wird. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird das Standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |
| keep_open | bool | <see langword=\"true\" /> um die Ebene nach dem Entsorgen des [Map](/psd/python-net/aspose.gis.rendering/map/)‑Objekts offen zu lassen; andernfalls <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Fügt der Karte eine Ebene hinzu. Ebenen werden in Hinzufügungsreihenfolge gerendert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Die hinzuzufügende Ebene. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Rendert die Karte in eine Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_path | string | Pfad zur Ausgabedatei. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer zur Verwendung. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Rendert die Karte in eine Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ausgabedatei. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer zur Verwendung. |

