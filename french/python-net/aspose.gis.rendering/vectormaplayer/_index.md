---
title: "Classe VectorMapLayer"
type: docs
weight: 390
url: /fr/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Crée une nouvelle instance avec le symboliseur par défaut. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Crée une nouvelle instance avec le symboliseur par défaut. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Crée une nouvelle instance avec le symboliseur par défaut. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Crée une nouvelle instance avec le symboliseur par défaut. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Crée une nouvelle instance. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Crée une nouvelle instance. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | La séquence de fonctionnalités représentée par ce <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Spécifie les options de déformation de la couche cartographique. |
| opacité | double | r/w | Opacité de la couche. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Symboliseur à utiliser pour rendre les fonctionnalités de la couche. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importe le style depuis le fichier Styled Layer Descriptor situé au chemin spécifié. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importe le style depuis le fichier Styled Layer Descriptor situé au chemin spécifié. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importe le style depuis la chaîne Styled Layer Descriptor spécifiée. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Crée une nouvelle instance avec le symboliseur par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Séquence d'entités. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Crée une nouvelle instance avec le symboliseur par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Séquence d'entités. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le symboliseur par défaut sera utilisé. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Crée une nouvelle instance avec le symboliseur par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Séquence d'entités. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le symboliseur par défaut sera utilisé. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, le [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) par défaut sera utilisé. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spécifie une valeur pour une référence spatiale source (couche\\séquence) si elle est manquante. La valeur null par défaut sera utilisée. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Crée une nouvelle instance avec le symboliseur par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Couche vectorielle. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) soit libéré ; sinon, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Couche vectorielle. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le symboliseur par défaut sera utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) soit libéré ; sinon, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Couche vectorielle. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le symboliseur par défaut sera utilisé. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, le [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) par défaut sera utilisé. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spécifie une valeur pour une référence spatiale source (couche\\séquence) si elle est manquante. La valeur null par défaut sera utilisée. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) soit libéré ; sinon, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Couche vectorielle. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le symboliseur par défaut sera utilisé. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, le [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) par défaut sera utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) soit libéré ; sinon, <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importe le style depuis le fichier Styled Layer Descriptor situé au chemin spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Options d'importation. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importe le style depuis le fichier Styled Layer Descriptor situé au chemin spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Options d'importation. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importe le style depuis la chaîne Styled Layer Descriptor spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sld | string | Descripteur de couche stylisée. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Options d'importation. |

