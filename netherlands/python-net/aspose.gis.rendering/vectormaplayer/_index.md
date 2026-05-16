---
title: "VectorMapLayer Klasse"
type: docs
weight: 390
url: /nl/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Maakt een nieuwe instantie met standaard symbolizer. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Maakt een nieuwe instantie met standaard symbolizer. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Maakt een nieuwe instantie met standaard symbolizer. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Maakt een nieuwe instantie met standaard symbolizer. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Creëert een nieuw exemplaar. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Creëert een nieuw exemplaar. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | De reeks kenmerken die wordt gerepresenteerd door deze <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Specificeert warp-opties van de kaartlaag. |
| opacity | double | r/w | Doorzichtigheid van de laag. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Symbolizer om te gebruiken om kenmerken van de laag te renderen. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importeert stijl vanuit Styled Layer Descriptor-bestand op het opgegeven pad. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importeert stijl vanuit Styled Layer Descriptor-bestand op het opgegeven pad. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importeert stijl vanuit de opgegeven Styled Layer Descriptor-tekenreeks. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Maakt een nieuwe instantie met standaard symbolizer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Reeks van features. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Maakt een nieuwe instantie met standaard symbolizer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Reeks van features. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer om te gebruiken om de laag te renderen. Als <see langword="null" />, wordt de standaard symbolizer gebruikt. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Maakt een nieuwe instantie met standaard symbolizer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Reeks van features. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer om te gebruiken om de laag te renderen. Als <see langword="null" />, wordt de standaard symbolizer gebruikt. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt de standaard [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specificeert een waarde voor een bron ruimtelijke referentie (laag\reeks) als deze ontbreekt. Standaard null wordt gebruikt. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Maakt een nieuwe instantie met standaard symbolizer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vectorlaag. |
| keep_open | bool | <see langword=\"true\" /> om de laag open te laten nadat het [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) object is vrijgegeven; anders, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vectorlaag. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer om te gebruiken om de laag te renderen. Als <see langword="null" />, wordt de standaard symbolizer gebruikt. |
| keep_open | bool | <see langword=\"true\" /> om de laag open te laten nadat het [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) object is vrijgegeven; anders, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vectorlaag. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer om te gebruiken om de laag te renderen. Als <see langword="null" />, wordt de standaard symbolizer gebruikt. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt de standaard [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specificeert een waarde voor een bron ruimtelijke referentie (laag\reeks) als deze ontbreekt. Standaard null wordt gebruikt. |
| keep_open | bool | <see langword=\"true\" /> om de laag open te laten nadat het [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) object is vrijgegeven; anders, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vectorlaag. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer om te gebruiken om de laag te renderen. Als <see langword="null" />, wordt de standaard symbolizer gebruikt. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Labeling om te gebruiken om kenmerken in de laag te labelen. Als <see langword="null" />, wordt de standaard [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) gebruikt. |
| keep_open | bool | <see langword=\"true\" /> om de laag open te laten nadat het [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) object is vrijgegeven; anders, <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importeert stijl vanuit Styled Layer Descriptor-bestand op het opgegeven pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het Styled Layer Descriptor-bestand. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importopties. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importeert stijl vanuit Styled Layer Descriptor-bestand op het opgegeven pad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het Styled Layer Descriptor-bestand. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importopties. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importeert stijl vanuit de opgegeven Styled Layer Descriptor-tekenreeks.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sld | string | Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importopties. |

