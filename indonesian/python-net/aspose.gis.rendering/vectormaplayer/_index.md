---
title: "Kelas VectorMapLayer"
type: docs
weight: 390
url: /id/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Membuat instance baru dengan simbolizer default. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Membuat instance baru dengan simbolizer default. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Membuat instance baru dengan simbolizer default. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Membuat instance baru dengan simbolizer default. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Membuat instance baru. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Membuat instance baru. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Urutan fitur yang direpresentasikan oleh <c>VectorMapLayer</c> ini. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Menentukan opsi warp untuk lapisan peta. |
| opasitas | double | r/w | Opasitas lapisan. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Simbolizer yang digunakan untuk merender fitur-fitur lapisan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Mengimpor gaya dari file Styled Layer Descriptor yang terletak di jalur yang ditentukan. |
| [import_sld(path, options)](#import_sld_path_options_2) | Mengimpor gaya dari file Styled Layer Descriptor yang terletak di jalur yang ditentukan. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Mengimpor gaya dari string Styled Layer Descriptor yang ditentukan. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Membuat instance baru dengan simbolizer default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Membuat instance baru dengan simbolizer default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, simbolizer default akan digunakan. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Membuat instance baru dengan simbolizer default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, simbolizer default akan digunakan. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) default akan digunakan. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Menentukan nilai untuk referensi spasial sumber (lapisan\\urutan) jika tidak ada. Null default akan digunakan. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Membuat instance baru dengan simbolizer default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dibuang; jika tidak, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, simbolizer default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dibuang; jika tidak, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, simbolizer default akan digunakan. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) default akan digunakan. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Menentukan nilai untuk referensi spasial sumber (lapisan\\urutan) jika tidak ada. Null default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dibuang; jika tidak, <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, simbolizer default akan digunakan. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dibuang; jika tidak, <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Mengimpor gaya dari file Styled Layer Descriptor yang terletak di jalur yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opsi impor. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Mengimpor gaya dari file Styled Layer Descriptor yang terletak di jalur yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opsi impor. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Mengimpor gaya dari string Styled Layer Descriptor yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sld | string | Deskriptor Lapisan Bergaya. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Opsi impor. |

