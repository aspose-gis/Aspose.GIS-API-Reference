---
title: "VectorMapLayer クラス"
type: docs
weight: 390
url: /ja/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | デフォルトのシンボライザーで新しいインスタンスを作成します。 |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | デフォルトのシンボライザーで新しいインスタンスを作成します。 |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | デフォルトのシンボライザーで新しいインスタンスを作成します。 |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | デフォルトのシンボライザーで新しいインスタンスを作成します。 |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | 新しいインスタンスを作成します。 |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | 新しいインスタンスを作成します。 |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | この<c>VectorMapLayer</c>で表されるフィーチャーシーケンスです。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | マップレイヤーのワープオプションを指定します。 |
| 不透明度 | double | 読み/書き | レイヤーの不透明度です。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | レイヤーのフィーチャーをレンダリングするために使用するシンボライザーです。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | 指定されたパスにある Styled Layer Descriptor ファイルからスタイルをインポートします。 |
| [import_sld(path, options)](#import_sld_path_options_2) | 指定されたパスにある Styled Layer Descriptor ファイルからスタイルをインポートします。 |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | 指定された Styled Layer Descriptor 文字列からスタイルをインポートします。 |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

デフォルトのシンボライザーで新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | フィーチャシーケンス。 |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

デフォルトのシンボライザーで新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | フィーチャシーケンス。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レイヤーをレンダリングするために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

デフォルトのシンボライザーで新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | フィーチャシーケンス。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レイヤーをレンダリングするために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、デフォルトの[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 欠落している場合、ソース空間参照（layer\sequence）の値を指定します。デフォルトで null が使用されます。 |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

デフォルトのシンボライザーで新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | ベクトルレイヤーです。 |
| keep_open | bool | <see langword="true" /> は、[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでない場合は、<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | ベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レイヤーをレンダリングするために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| keep_open | bool | <see langword="true" /> は、[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでない場合は、<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | ベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レイヤーをレンダリングするために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、デフォルトの[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 欠落している場合、ソース空間参照（layer\sequence）の値を指定します。デフォルトで null が使用されます。 |
| keep_open | bool | <see langword="true" /> は、[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでない場合は、<see langword="false" />。 |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | ベクトルレイヤーです。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レイヤーをレンダリングするために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | レイヤー内のフィーチャーにラベル付けするために使用するラベリングです。<see langword="null" /> の場合、デフォルトの[NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) が使用されます。 |
| keep_open | bool | <see langword="true" /> は、[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでない場合は、<see langword="false" />。 |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

指定されたパスにある Styled Layer Descriptor ファイルからスタイルをインポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | Styled Layer Descriptor ファイルへのパスです。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | インポートオプションです。 |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

指定されたパスにある Styled Layer Descriptor ファイルからスタイルをインポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Styled Layer Descriptor ファイルへのパスです。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | インポートオプションです。 |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

指定された Styled Layer Descriptor 文字列からスタイルをインポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| sld | string | Styled Layer Descriptor。 |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | インポートオプションです。 |

