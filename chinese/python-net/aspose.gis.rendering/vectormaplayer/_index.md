---
title: "VectorMapLayer 类"
type: docs
weight: 390
url: /zh/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | 使用默认符号化器创建新实例。 |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | 使用默认符号化器创建新实例。 |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | 使用默认符号化器创建新实例。 |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | 使用默认符号化器创建新实例。 |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | 创建新实例。 |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | 创建新实例。 |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | 此 <c>VectorMapLayer</c> 表示的要素序列。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | 指定地图图层的扭曲选项。 |
| 不透明度 | double | r/w | 图层的不透明度。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | 用于渲染图层要素的符号化器。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | 从指定路径的 Styled Layer Descriptor 文件导入样式。 |
| [import_sld(path, options)](#import_sld_path_options_2) | 从指定路径的 Styled Layer Descriptor 文件导入样式。 |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | 从指定的 Styled Layer Descriptor 字符串导入样式。 |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

使用默认符号化器创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 特征序列。 |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

使用默认符号化器创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 特征序列。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染图层的符号化器。如果 <see langword="null" />，将使用默认符号化器。 |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

使用默认符号化器创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 特征序列。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染图层的符号化器。如果 <see langword="null" />，将使用默认符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用默认的 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 如果缺少源空间参考（layer\sequence），指定其值。默认使用 null。 |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

使用默认符号化器创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 矢量图层。 |
| keep_open | bool | <see langword="true" /> 在 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 对象释放后保持图层打开；否则，<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染图层的符号化器。如果 <see langword="null" />，将使用默认符号化器。 |
| keep_open | bool | <see langword="true" /> 在 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 对象释放后保持图层打开；否则，<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染图层的符号化器。如果 <see langword="null" />，将使用默认符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用默认的 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 如果缺少源空间参考（layer\sequence），指定其值。默认使用 null。 |
| keep_open | bool | <see langword="true" /> 在 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 对象释放后保持图层打开；否则，<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染图层的符号化器。如果 <see langword="null" />，将使用默认符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用默认的 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |
| keep_open | bool | <see langword="true" /> 在 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 对象释放后保持图层打开；否则，<see langword="false" />。 |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

从指定路径的 Styled Layer Descriptor 文件导入样式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | Styled Layer Descriptor 文件的路径。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 导入选项。 |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

从指定路径的 Styled Layer Descriptor 文件导入样式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Styled Layer Descriptor 文件的路径。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 导入选项。 |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

从指定的 Styled Layer Descriptor 字符串导入样式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sld | string | 样式图层描述符。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 导入选项。 |

