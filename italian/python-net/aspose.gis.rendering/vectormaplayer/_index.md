---
title: "Classe VectorMapLayer"
type: docs
weight: 390
url: /it/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Crea una nuova istanza con lo symbolizer predefinito. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Crea una nuova istanza con lo symbolizer predefinito. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Crea una nuova istanza con lo symbolizer predefinito. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Crea una nuova istanza con lo symbolizer predefinito. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Crea una nuova istanza. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Crea una nuova istanza. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | La sequenza di feature rappresentata da questo <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Specifica le opzioni di warp del livello della mappa. |
| opacità | double | r/w | Opacità del livello. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Symbolizer da utilizzare per renderizzare le feature del livello. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importa lo stile dal file Styled Layer Descriptor situato al percorso specificato. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importa lo stile dal file Styled Layer Descriptor situato al percorso specificato. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importa lo stile dalla stringa Styled Layer Descriptor specificata. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Crea una nuova istanza con lo symbolizer predefinito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sequenza di feature. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Crea una nuova istanza con lo symbolizer predefinito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sequenza di feature. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer da utilizzare per renderizzare il livello. Se <see langword="null" />, verrà usato lo symbolizer predefinito. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Crea una nuova istanza con lo symbolizer predefinito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sequenza di feature. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer da utilizzare per renderizzare il livello. Se <see langword="null" />, verrà usato lo symbolizer predefinito. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato il [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predefinito. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specifica un valore per un riferimento spaziale di origine (layer\\sequence) se mancante. Verrà usato null di default. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Crea una nuova istanza con lo symbolizer predefinito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Livello vettoriale. |
| keep_open | bool | <see langword=\"true\" /> per lasciare il livello aperto dopo che l'oggetto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) è stato eliminato; altrimenti, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Livello vettoriale. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer da utilizzare per renderizzare il livello. Se <see langword="null" />, verrà usato lo symbolizer predefinito. |
| keep_open | bool | <see langword=\"true\" /> per lasciare il livello aperto dopo che l'oggetto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) è stato eliminato; altrimenti, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Livello vettoriale. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer da utilizzare per renderizzare il livello. Se <see langword="null" />, verrà usato lo symbolizer predefinito. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato il [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predefinito. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Specifica un valore per un riferimento spaziale di origine (layer\\sequence) se mancante. Verrà usato null di default. |
| keep_open | bool | <see langword=\"true\" /> per lasciare il livello aperto dopo che l'oggetto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) è stato eliminato; altrimenti, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Livello vettoriale. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer da utilizzare per renderizzare il livello. Se <see langword="null" />, verrà usato lo symbolizer predefinito. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etichettatura da usare per etichettare le feature nel livello. Se <see langword="null" />, verrà utilizzato il [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predefinito. |
| keep_open | bool | <see langword=\"true\" /> per lasciare il livello aperto dopo che l'oggetto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) è stato eliminato; altrimenti, <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importa lo stile dal file Styled Layer Descriptor situato al percorso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso al file Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opzioni di importazione. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importa lo stile dal file Styled Layer Descriptor situato al percorso specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso al file Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opzioni di importazione. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importa lo stile dalla stringa Styled Layer Descriptor specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sld | string | Descrittore di livello stilizzato. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opzioni di importazione. |

