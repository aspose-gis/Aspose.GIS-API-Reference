---
title: "Map 类"
type: docs
weight: 100
url: /zh/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Map()](#Map__1) | 创建 <c>Map</c> 类的新实例。 |
| [Map(width, height)](#Map_width_height_2) | 创建 <c>Map</c> 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | 地图的背景颜色。默认值为 。 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | 指定要渲染的地图边界。<br/>            如果设置为 <see langword="null" />，则在渲染期间计算范围，以包含所有图层中的所有几何体。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 地图的可视高度。 |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定要添加到范围的内边距。 |
| resolution | double | r/w | 用于渲染此地图并在 [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) 之间进行转换的分辨率。默认值为 96。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 地图的 [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/)。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 地图的可视宽度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | 创建一个带有默认 colorizer 的 [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) 并将其添加到地图。 |
| [add(layer, keep_open)](#add_layer_keep_open_5) | 创建一个带有默认 symbolizer 的 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 并将其添加到地图。图层按添加顺序渲染。 |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | 创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。 |
| [add(map_layer)](#add_map_layer_9) | 向地图添加图层。图层按照添加顺序渲染。 |
| [render(output_path, renderer)](#render_output_path_renderer_10) | 将地图渲染到文件中。 |
| [render(output_path, renderer)](#render_output_path_renderer_11) | 将地图渲染到文件中。 |


### Constructor: Map() {#Map__1}


```
 Map() 
```

创建 <c>Map</c> 类的新实例。

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

创建 <c>Map</c> 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 地图的宽度。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 地图的高度。 |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的要素序列。 |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的要素序列。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的要素序列。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

创建一个带有默认 colorizer 的 [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) 并将其添加到地图。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 用于由 [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 表示的矢量图层。 |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | 用于渲染的着色器。如果 <see langword="null" />，将使用默认着色器。 |
| keep_open | bool | 在 [Map](/psd/python-net/aspose.gis.rendering/map/) 对象释放后，<see langword="true" /> 表示保持栅格图层打开；<br/>            <see langword="false" /> 表示释放该图层。 |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

创建一个带有默认 symbolizer 的 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 并将其添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的矢量图层。 |
| keep_open | bool | 在 [Map](/psd/python-net/aspose.gis.rendering/map/) 对象释放后，<see langword="true" /> 表示保持矢量图层打开；<br/>            <see langword="false" /> 表示释放该图层。 |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |
| keep_open | bool | 在 [Map](/psd/python-net/aspose.gis.rendering/map/) 对象释放后，<see langword="true" /> 表示保持矢量图层打开；<br/>            <see langword="false" /> 表示释放该图层。 |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用默认的 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 如果缺少源空间参考（layer\sequence），指定其值。默认使用 null。 |
| keep_open | bool | 在 [Map](/psd/python-net/aspose.gis.rendering/map/) 对象释放后，<see langword="true" /> 表示保持图层打开；否则，<see langword="false" />。 |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

创建并将一个 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 添加到地图。图层按添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于由 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 表示的矢量图层。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 用于为图层中的要素标注的标注。如果 <see langword="null" />，将使用默认的 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)。 |
| keep_open | bool | 在 [Map](/psd/python-net/aspose.gis.rendering/map/) 对象释放后，<see langword="true" /> 表示保持图层打开；否则，<see langword="false" />。 |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

向地图添加图层。图层按照添加顺序渲染。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | 要添加的图层。 |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

将地图渲染到文件中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_path | string | 输出文件的路径。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 要使用的渲染器。 |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

将地图渲染到文件中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 输出文件的路径。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 要使用的渲染器。 |

