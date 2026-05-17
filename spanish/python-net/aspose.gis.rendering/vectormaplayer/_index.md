---
title: "Clase VectorMapLayer"
type: docs
weight: 390
url: /es/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Crea una nueva instancia con el simbolizador predeterminado. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Crea una nueva instancia con el simbolizador predeterminado. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Crea una nueva instancia con el simbolizador predeterminado. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Crea una nueva instancia con el simbolizador predeterminado. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Crea una nueva instancia. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Crea una nueva instancia. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | La secuencia de características representada por este <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Especifica opciones de deformación de la capa del mapa. |
| opacity | double | r/w | Opacidad de la capa. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Simbolizador a usar para renderizar las características de la capa. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Importa estilo desde el archivo Styled Layer Descriptor ubicado en la ruta especificada. |
| [import_sld(path, options)](#import_sld_path_options_2) | Importa estilo desde el archivo Styled Layer Descriptor ubicado en la ruta especificada. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Importa estilo desde la cadena Styled Layer Descriptor especificada. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Crea una nueva instancia con el simbolizador predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Secuencia de entidades. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Crea una nueva instancia con el simbolizador predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Secuencia de entidades. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizador a usar para renderizar la capa. Si <see langword=\"null\" />, se usará el simbolizador predeterminado. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Crea una nueva instancia con el simbolizador predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Secuencia de entidades. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizador a usar para renderizar la capa. Si <see langword=\"null\" />, se usará el simbolizador predeterminado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará el [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predeterminado. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Especifica un valor para una referencia espacial de origen (capa\\secuencia) si falta. Se usará null por defecto. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Crea una nueva instancia con el simbolizador predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Capa vectorial. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Capa vectorial. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizador a usar para renderizar la capa. Si <see langword=\"null\" />, se usará el simbolizador predeterminado. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Capa vectorial. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizador a usar para renderizar la capa. Si <see langword=\"null\" />, se usará el simbolizador predeterminado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará el [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predeterminado. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Especifica un valor para una referencia espacial de origen (capa\\secuencia) si falta. Se usará null por defecto. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Capa vectorial. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizador a usar para renderizar la capa. Si <see langword=\"null\" />, se usará el simbolizador predeterminado. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Etiquetado a usar para etiquetar características en la capa. Si <see langword=\"null\" />, se utilizará el [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) predeterminado. |
| keep_open | bool | <see langword=\"true\" /> para dejar la capa abierta después de que el objeto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) sea eliminado; de lo contrario, <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Importa estilo desde el archivo Styled Layer Descriptor ubicado en la ruta especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opciones de importación. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Importa estilo desde el archivo Styled Layer Descriptor ubicado en la ruta especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opciones de importación. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Importa estilo desde la cadena Styled Layer Descriptor especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sld | string | Descriptor de capa con estilo. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opciones de importación. |

