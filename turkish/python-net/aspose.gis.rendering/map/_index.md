---
title: "Map Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Map()](#Map__1) | <c>Map</c> sınıfının yeni bir örneğini oluşturur. |
| [Map(width, height)](#Map_width_height_2) | <c>Map</c> sınıfının yeni bir örneğini oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Haritanın arka plan rengi. Varsayılanı . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Renderlenecek haritanın sınırlarını belirtir.<br/>            Eğer <see langword=\"null\" /> olarak ayarlanırsa, kapsam, tüm katmanlardaki tüm geometrileri içerecek şekilde renderleme sırasında hesaplanır. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Haritanın görsel yüksekliği. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Kapsama eklenmek üzere dolgu miktarını belirtir. |
| resolution | double | r/w | Bu haritayı renderlemek ve [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) arasında dönüşüm yapmak için kullanılacak çözünürlük. Varsayılanı 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Haritanın [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) özelliği. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Haritanın görsel genişliği. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Varsayılan renkleyici ile bir [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) oluşturur ve haritaya ekler. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Varsayılan sembolleyici ile bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve haritaya ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir. |
| [add(map_layer)](#add_map_layer_9) | Haritaya bir katman ekler. Katmanlar ekleme sırasına göre işlenir. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Haritayı bir dosyaya işler. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Haritayı bir dosyaya işler. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

<c>Map</c> sınıfının yeni bir örneğini oluşturur.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

<c>Map</c> sınıfının yeni bir örneğini oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Haritanın genişliği. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Haritanın yüksekliği. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) tarafından temsil edilecek bir özellik dizisi. |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) tarafından temsil edilecek bir özellik dizisi. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) tarafından temsil edilecek bir özellik dizisi. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | İşleme için kullanılacak bir sembolleyici. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Varsayılan renkleyici ile bir [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) oluşturur ve haritaya ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Bu [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) ile temsil edilecek bir vektör katmanı. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | İşleme için kullanılacak bir renklendirici. Eğer <see langword="null" />, varsayılan renklendirici kullanılır. |
| keep_open | bool | <see langword="true" /> raster katmanını [Map](/psd/python-net/aspose.gis.rendering/map/) nesnesi yok edildikten sonra açık bırakmak için;<br/>            <see langword="false" /> katmanı yok etmek için. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Varsayılan sembolleyici ile bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve haritaya ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ile temsil edilecek bir vektör katmanı. |
| keep_open | bool | <see langword="true" /> vektör katmanını [Map](/psd/python-net/aspose.gis.rendering/map/) nesnesi yok edildikten sonra açık bırakmak için;<br/>            <see langword="false" /> katmanı yok etmek için. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ile temsil edilecek bir vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |
| keep_open | bool | <see langword="true" /> vektör katmanını [Map](/psd/python-net/aspose.gis.rendering/map/) nesnesi yok edildikten sonra açık bırakmak için;<br/>            <see langword="false" /> katmanı yok etmek için. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ile temsil edilecek bir vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, varsayılan [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Eksikse kaynak uzamsal referans (layer\sequence) için bir değer belirtir. Varsayılan null kullanılacaktır. |
| keep_open | bool | <see langword="true" /> katmanı [Map](/psd/python-net/aspose.gis.rendering/map/) nesnesi yok edildikten sonra açık bırakmak için; aksi takdirde, <see langword="false" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Haritaya bir [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) oluşturur ve ekler. Katmanlar ekleme sırasına göre renderlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bu [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ile temsil edilecek bir vektör katmanı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Katmandaki özellikleri etiketlemek için kullanılacak etiketleme. Eğer <see langword="null" />, varsayılan [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) kullanılacaktır. |
| keep_open | bool | <see langword="true" /> katmanı [Map](/psd/python-net/aspose.gis.rendering/map/) nesnesi yok edildikten sonra açık bırakmak için; aksi takdirde, <see langword="false" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Haritaya bir katman ekler. Katmanlar ekleme sırasına göre işlenir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Eklenecek katman. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Haritayı bir dosyaya işler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_path | string | Çıktı dosyasının yolu. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Kullanılacak renderlayıcı. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Haritayı bir dosyaya işler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı dosyasının yolu. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Kullanılacak renderlayıcı. |

