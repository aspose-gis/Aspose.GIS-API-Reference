---
title: "VectorMapLayer Sınıfı"
type: docs
weight: 390
url: /tr/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Varsayılan sembolleyici ile yeni bir örnek oluşturur. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Varsayılan sembolleyici ile yeni bir örnek oluşturur. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Varsayılan sembolleyici ile yeni bir örnek oluşturur. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Varsayılan sembolleyici ile yeni bir örnek oluşturur. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Yeni bir örnek oluşturur. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Yeni bir örnek oluşturur. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Bu <c>VectorMapLayer</c> tarafından temsil edilen özellik dizisi. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Harita katmanının bükülme seçeneklerini belirtir. |
| opaklık | double | r/w | Katmanın opaklığı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Katmanın özelliklerini işlemek için kullanılacak sembolleyici. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Belirtilen yoldaki Styled Layer Descriptor dosyasından stili içe aktarır. |
| [import_sld(path, options)](#import_sld_path_options_2) | Belirtilen yoldaki Styled Layer Descriptor dosyasından stili içe aktarır. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Belirtilen Styled Layer Descriptor dizesinden stili içe aktarır. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Varsayılan sembolleyici ile yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Özellikler dizisi. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Varsayılan sembolleyici ile yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Özellikler dizisi. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Katmanı işlemek için kullanılacak sembolleyici. Eğer <see langword="null" />, varsayılan sembolleyici kullanılacaktır. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Varsayılan sembolleyici ile yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Özellikler dizisi. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Katmanı işlemek için kullanılacak sembolleyici. Eğer <see langword="null" />, varsayılan sembolleyici kullanılacaktır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, varsayılan [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Eksikse kaynak uzamsal referans (layer\sequence) için bir değer belirtir. Varsayılan null kullanılacaktır. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Varsayılan sembolleyici ile yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektör katmanı. |
| keep_open | bool | <see langword=\"true\" /> katmanı, [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) nesnesi serbest bırakıldıktan sonra açık bırakmak için; aksi takdirde <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Katmanı işlemek için kullanılacak sembolleyici. Eğer <see langword="null" />, varsayılan sembolleyici kullanılacaktır. |
| keep_open | bool | <see langword=\"true\" /> katmanı, [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) nesnesi serbest bırakıldıktan sonra açık bırakmak için; aksi takdirde <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Katmanı işlemek için kullanılacak sembolleyici. Eğer <see langword="null" />, varsayılan sembolleyici kullanılacaktır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, varsayılan [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Eksikse kaynak uzamsal referans (layer\sequence) için bir değer belirtir. Varsayılan null kullanılacaktır. |
| keep_open | bool | <see langword=\"true\" /> katmanı, [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) nesnesi serbest bırakıldıktan sonra açık bırakmak için; aksi takdirde <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Katmanı işlemek için kullanılacak sembolleyici. Eğer <see langword="null" />, varsayılan sembolleyici kullanılacaktır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, varsayılan [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |
| keep_open | bool | <see langword=\"true\" /> katmanı, [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) nesnesi serbest bırakıldıktan sonra açık bırakmak için; aksi takdirde <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Belirtilen yoldaki Styled Layer Descriptor dosyasından stili içe aktarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Styled Layer Descriptor dosyasının yolu. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | İçe aktarma seçenekleri. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Belirtilen yoldaki Styled Layer Descriptor dosyasından stili içe aktarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Styled Layer Descriptor dosyasının yolu. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | İçe aktarma seçenekleri. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Belirtilen Styled Layer Descriptor dizesinden stili içe aktarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sld | string | Stil Katmanı Tanımlayıcısı. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | İçe aktarma seçenekleri. |

