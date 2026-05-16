---
title: "Map クラス"
type: docs
weight: 100
url: /ja/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Map()](#Map__1) | 新しい <c>Map</c> クラスのインスタンスを作成します。 |
| [Map(width, height)](#Map_width_height_2) | 新しい <c>Map</c> クラスのインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | 読み/書き | マップの背景色です。デフォルトは . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | 描画するマップの境界を指定します。<br/>            <see langword="null" /> に設定された場合、すべてのレイヤーのすべてのジオメトリを含むように、レンダリング中に範囲が計算されます。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | マップの視覚的高さです。 |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 範囲に追加するパディングを指定します。 |
| resolution | double | r/w | このマップを描画し、[Measurement](/psd/python-net/aspose.gis.rendering/measurement/) 間の変換に使用する解像度です。デフォルトは 96 です。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | マップの [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/)。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | マップの視覚的幅です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | デフォルトのカラーライザーを使用した [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) を作成し、マップに追加します。 |
| [add(layer, keep_open)](#add_layer_keep_open_5) | デフォルトのシンボライザーを使用した [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) を作成し、マップに追加します。レイヤーは追加順にレンダリングされます。 |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。 |
| [add(map_layer)](#add_map_layer_9) | マップにレイヤーを追加します。レイヤーは追加順にレンダリングされます。 |
| [render(output_path, renderer)](#render_output_path_renderer_10) | マップをファイルにレンダリングします。 |
| [render(output_path, renderer)](#render_output_path_renderer_11) | マップをファイルにレンダリングします。 |


### Constructor: Map() {#Map__1}


```
 Map() 
```

新しい <c>Map</c> クラスのインスタンスを作成します。

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

新しい <c>Map</c> クラスのインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | マップの幅。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | マップの高さ。 |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるフィーチャーシーケンスです。 |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるフィーチャーシーケンスです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるフィーチャーシーケンスです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

デフォルトのカラーライザーを使用した [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) を作成し、マップに追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) によって表されるベクトルレイヤーです。 |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | レンダリングに使用するカラーライザーです。<see langword="null" /> の場合、デフォルトのカラーライザーが使用されます。 |
| keep_open | bool | <see langword="true" /> を指定すると、[Map](/psd/python-net/aspose.gis.rendering/map/) オブジェクトが破棄された後もラスターレイヤーを開いたままにします;<br/>            <see langword="false" /> を指定すると、レイヤーを破棄します。 |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

デフォルトのシンボライザーを使用した [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) を作成し、マップに追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるベクトルレイヤーです。 |
| keep_open | bool | <see langword="true" /> を指定すると、[Map](/psd/python-net/aspose.gis.rendering/map/) オブジェクトが破棄された後もベクトルレイヤーを開いたままにします;<br/>            <see langword="false" /> を指定すると、レイヤーを破棄します。 |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| keep_open | bool | <see langword="true" /> を指定すると、[Map](/psd/python-net/aspose.gis.rendering/map/) オブジェクトが破棄された後もベクトルレイヤーを開いたままにします;<br/>            <see langword="false" /> を指定すると、レイヤーを破棄します。 |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、デフォルトの[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 欠落している場合、ソース空間参照（layer\sequence）の値を指定します。デフォルトで null が使用されます。 |
| keep_open | bool | <see langword="true" /> を指定すると、[Map](/psd/python-net/aspose.gis.rendering/map/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでなければ、<see langword="false" />。 |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) をマップに作成して追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) によって表されるベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、デフォルトの[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |
| keep_open | bool | <see langword="true" /> を指定すると、[Map](/psd/python-net/aspose.gis.rendering/map/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでなければ、<see langword="false" />。 |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

マップにレイヤーを追加します。レイヤーは追加順にレンダリングされます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | 追加されるレイヤーです。 |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

マップをファイルにレンダリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| output_path | string | 出力ファイルへのパス。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 使用するレンダラー。 |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

マップをファイルにレンダリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力ファイルへのパス。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 使用するレンダラー。 |

