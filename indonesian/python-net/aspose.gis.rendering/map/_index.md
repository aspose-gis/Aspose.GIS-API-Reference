---
title: "Kelas Map"
type: docs
weight: 100
url: /id/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Map()](#Map__1) | Membuat instance baru dari kelas <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Membuat instance baru dari kelas <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Warna latar belakang peta. Defaultnya . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Menentukan batas peta yang akan dirender.<br/>            Jika disetel ke <see langword=\"null\" />, ekstensi dihitung selama rendering untuk mencakup semua geometri di semua lapisan. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Tinggi visual peta. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Menentukan padding yang ditambahkan ke ekstensi. |
| resolution | double | r/w | Resolusi yang digunakan untuk merender peta ini dan mengonversi antara [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Defaultnya 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) peta. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Lebar visual peta. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Membuat [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) dengan colorizer default dan menambahkannya ke peta. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Membuat [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dengan symbolizer default dan menambahkannya ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan. |
| [add(map_layer)](#add_map_layer_9) | Menambahkan lapisan ke peta. Lapisan dirender dalam urutan penambahan. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Merender peta ke dalam sebuah file. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Merender peta ke dalam sebuah file. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Membuat instance baru dari kelas <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Membuat instance baru dari kelas <c>Map</c>.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Lebar peta. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Tinggi peta. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Simbolizer yang digunakan untuk merender. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) akan digunakan. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Membuat [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) dengan colorizer default dan menambahkannya ke peta.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Lapisan vektor untuk direpresentasikan oleh [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Pewarna yang digunakan untuk merender. Jika <see langword=\"null\" />, pewarna default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan raster tetap terbuka setelah objek [Map](/psd/python-net/aspose.gis.rendering/map/) dibuang;<br/>            <see langword=\"false\" /> untuk membuang lapisan. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Membuat [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dengan symbolizer default dan menambahkannya ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan vektor tetap terbuka setelah objek [Map](/psd/python-net/aspose.gis.rendering/map/) dibuang;<br/>            <see langword=\"false\" /> untuk membuang lapisan. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan vektor tetap terbuka setelah objek [Map](/psd/python-net/aspose.gis.rendering/map/) dibuang;<br/>            <see langword=\"false\" /> untuk membuang lapisan. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) default akan digunakan. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Menentukan nilai untuk referensi spasial sumber (lapisan\\urutan) jika tidak ada. Null default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [Map](/psd/python-net/aspose.gis.rendering/map/) dibuang; jika tidak, <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Membuat dan menambahkan [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ke peta. Lapisan dirender sesuai urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan vektor untuk direpresentasikan oleh [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Pelabelan yang digunakan untuk memberi label pada fitur di lapisan. Jika <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [Map](/psd/python-net/aspose.gis.rendering/map/) dibuang; jika tidak, <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Menambahkan lapisan ke peta. Lapisan dirender dalam urutan penambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Lapisan yang akan ditambahkan. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Merender peta ke dalam sebuah file.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_path | string | Jalur ke file output. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer yang akan digunakan. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Merender peta ke dalam sebuah file.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file output. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer yang akan digunakan. |

