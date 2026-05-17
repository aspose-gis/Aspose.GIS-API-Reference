---
title: "VectorMapLayer‑klass"
type: docs
weight: 390
url: /sv/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Skapar en ny instans med standard‑symboliserare. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Skapar en ny instans med standard‑symboliserare. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Skapar en ny instans med standard‑symboliserare. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Skapar en ny instans med standard‑symboliserare. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Skapar ny instans. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Skapar ny instans. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Funktionsekvensen som representeras av denna <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Anger warp‑alternativ för kartlagret. |
| opacitet | double | läs/skriv | Opacitet för lagret. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Symboliserare att använda för att rendera lagrets funktioner. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importerar stil från Styled Layer Descriptor‑filen som finns på den angivna sökvägen. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importerar stil från Styled Layer Descriptor‑filen som finns på den angivna sökvägen. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importerar stil från den angivna Styled Layer Descriptor‑strängen. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Skapar en ny instans med standard‑symboliserare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features-sekvens. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Skapar en ny instans med standard‑symboliserare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features-sekvens. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliserare att använda för att rendera lagret. Om <see langword=\"null\" />, används standard‑symboliserare. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Skapar en ny instans med standard‑symboliserare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features-sekvens. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliserare att använda för att rendera lagret. Om <see langword=\"null\" />, används standard‑symboliserare. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, används standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Anger ett värde för en källspatial referens (lager\\sekvens) om den saknas. Standard‑null kommer att användas. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Skapar en ny instans med standard‑symboliserare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorlager. |
| keep_open | bool | <see langword="true" /> för att lämna lagret öppet efter att [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)-objektet har frigjorts; annars <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorlager. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliserare att använda för att rendera lagret. Om <see langword=\"null\" />, används standard‑symboliserare. |
| keep_open | bool | <see langword="true" /> för att lämna lagret öppet efter att [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)-objektet har frigjorts; annars <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorlager. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliserare att använda för att rendera lagret. Om <see langword=\"null\" />, används standard‑symboliserare. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, används standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Anger ett värde för en källspatial referens (lager\\sekvens) om den saknas. Standard‑null kommer att användas. |
| keep_open | bool | <see langword="true" /> för att lämna lagret öppet efter att [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)-objektet har frigjorts; annars <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektorlager. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliserare att använda för att rendera lagret. Om <see langword=\"null\" />, används standard‑symboliserare. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Märkning att använda för att märka funktioner i lagret. Om <see langword=\"null\" />, används standard‑[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| keep_open | bool | <see langword="true" /> för att lämna lagret öppet efter att [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)-objektet har frigjorts; annars <see langword="false" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importerar stil från Styled Layer Descriptor‑filen som finns på den angivna sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till Styled Layer Descriptor‑filen. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importalternativ. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importerar stil från Styled Layer Descriptor‑filen som finns på den angivna sökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till Styled Layer Descriptor‑filen. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importalternativ. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importerar stil från den angivna Styled Layer Descriptor‑strängen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sld | string | Stiliserad lagerbeskrivning. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Importalternativ. |

