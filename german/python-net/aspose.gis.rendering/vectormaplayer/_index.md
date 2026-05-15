---
title: "VectorMapLayer Klasse"
type: docs
weight: 390
url: /de/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Erstellt eine neue Instanz mit dem Standard‑Symbolisierer. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Erstellt eine neue Instanz mit dem Standard‑Symbolisierer. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Erstellt eine neue Instanz mit dem Standard‑Symbolisierer. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Erstellt eine neue Instanz mit dem Standard‑Symbolisierer. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Erstellt eine neue Instanz. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Erstellt eine neue Instanz. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Die Feature‑Sequenz, die durch dieses <c>VectorMapLayer</c> dargestellt wird. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Gibt Verzerrungsoptionen der Kartenebene an. |
| Deckkraft | double | r/w | Deckkraft der Ebene. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Symbolisierer zur Verwendung beim Rendern von Features der Ebene. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importiert Stil aus einer Styled‑Layer‑Descriptor‑Datei, die am angegebenen Pfad liegt. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importiert Stil aus einer Styled‑Layer‑Descriptor‑Datei, die am angegebenen Pfad liegt. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importiert Stil aus dem angegebenen Styled‑Layer‑Descriptor‑String. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Erstellt eine neue Instanz mit dem Standard‑Symbolisierer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature‑Sequenz. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Erstellt eine neue Instanz mit dem Standard‑Symbolisierer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature‑Sequenz. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolisierer zur Verwendung beim Rendern der Ebene. Wenn <see langword=\"null\" />, wird der Standard‑Symbolisierer verwendet. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Erstellt eine neue Instanz mit dem Standard‑Symbolisierer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature‑Sequenz. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolisierer zur Verwendung beim Rendern der Ebene. Wenn <see langword=\"null\" />, wird der Standard‑Symbolisierer verwendet. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird das Standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Gibt einen Wert für eine Quell‑räumliche Referenz (Ebene\\Sequenz) an, falls diese fehlt. Standard‑null wird verwendet. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Erstellt eine neue Instanz mit dem Standard‑Symbolisierer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorebene. |
| keep_open | bool | <see langword="true" /> um die Ebene nach dem Entsorgen des [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) Objekts offen zu lassen; andernfalls, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorebene. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolisierer zur Verwendung beim Rendern der Ebene. Wenn <see langword=\"null\" />, wird der Standard‑Symbolisierer verwendet. |
| keep_open | bool | <see langword="true" /> um die Ebene nach dem Entsorgen des [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) Objekts offen zu lassen; andernfalls, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorebene. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolisierer zur Verwendung beim Rendern der Ebene. Wenn <see langword=\"null\" />, wird der Standard‑Symbolisierer verwendet. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird das Standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Gibt einen Wert für eine Quell‑räumliche Referenz (Ebene\\Sequenz) an, falls diese fehlt. Standard‑null wird verwendet. |
| keep_open | bool | <see langword="true" /> um die Ebene nach dem Entsorgen des [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) Objekts offen zu lassen; andernfalls, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorebene. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolisierer zur Verwendung beim Rendern der Ebene. Wenn <see langword=\"null\" />, wird der Standard‑Symbolisierer verwendet. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Beschriftung, die zum Beschriften von Features in der Ebene verwendet wird. Wenn <see langword=\"null\" />, wird das Standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) verwendet. |
| keep_open | bool | <see langword="true" /> um die Ebene nach dem Entsorgen des [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) Objekts offen zu lassen; andernfalls, <see langword="false" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importiert Stil aus einer Styled‑Layer‑Descriptor‑Datei, die am angegebenen Pfad liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Styled‑Layer‑Descriptor‑Datei. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importoptionen. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importiert Stil aus einer Styled‑Layer‑Descriptor‑Datei, die am angegebenen Pfad liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Styled‑Layer‑Descriptor‑Datei. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importoptionen. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importiert Stil aus dem angegebenen Styled‑Layer‑Descriptor‑String.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sld | string | Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importoptionen. |

