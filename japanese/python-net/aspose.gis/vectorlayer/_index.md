---
title: "VectorLayer Class"
type: docs
weight: 4060
url: /ja/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | この[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)のフィーチャのカスタム属性コレクションを取得します。 |
| カウント | int | r | このレイヤーのフィーチャ数を取得します。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | このレイヤーをインスタンス化した[VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)を取得します。 |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | レイヤーのジオメトリのタイプを取得します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | このフィーチャーシーケンスの空間参照系を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(feature)](#add_feature_1) | レイヤーに新しいフィーチャーを追加します（[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) がサポートしている場合）。 |
| [add(feature, style)](#add_feature_style_2) | 指定されたスタイルで新しいフィーチャーをレイヤーに追加します（[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) がサポートしている場合）。 |
| [as_in_memory()](#as_in_memory__3) | InMemory 形式でレイヤーのクローンを作成します。 |
| [construct_feature()](#construct_feature__4) | このレイヤーの属性コレクションと一致する属性を持つ新しいフィーチャーを作成します（ただしレイヤーには追加しません）。<br/>            フィーチャーのデータ設定が完了したら、[VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) を使用してフィーチャーをレイヤーに追加してください。 |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | レイヤーを別の形式に変換します。 |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | レイヤーを別の形式に変換します。 |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | レイヤーを別の形式に変換します。 |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | レイヤーを別の形式に変換します。 |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | 他の [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の属性をこのレイヤーにコピーします。 |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | 他の [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の属性をこのレイヤーにコピーします。 |
| [create(path, driver)](#create_path_driver_11) | レイヤーを作成し、新しいフィーチャーの追加のために開きます。 |
| [create(path, driver)](#create_path_driver_12) | レイヤーを作成し、新しいフィーチャーの追加のために開きます。 |
| [create(path, driver, options)](#create_path_driver_options_13) | レイヤーを作成し、新しいフィーチャーの追加のために開きます。 |
| [create(path, driver, options)](#create_path_driver_options_14) | レイヤーを作成し、新しいフィーチャーの追加のために開きます。 |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | レイヤーを作成し、追加書き込みのために開きます。 |
| [get_extent()](#get_extent__19) | このレイヤーの空間範囲を取得します。 |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | ジオメトリでレイヤーを現在のレイヤーと交差させます。 |
| [join(layer, options)](#join_layer_options_21) | レイヤーを現在のレイヤーに結合します。 |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | ジオメトリでレイヤーを現在のレイヤーに結合します。 |
| [nearest_to(point)](#nearest_to_point_23) | 指定されたポイントに最も近いフィーチャーを取得します。 |
| [nearest_to(x, y)](#nearest_to_x_y_24) | 指定された座標に最も近いフィーチャーを取得します。 |
| [open(path, driver)](#open_path_driver_25) | レイヤーを読み取り用に開きます。 |
| [open(path, driver)](#open_path_driver_26) | レイヤーを読み取り用に開きます。 |
| [open(path, driver, options)](#open_path_driver_options_27) | レイヤーを読み取り用に開きます。 |
| [open(path, driver, options)](#open_path_driver_options_28) | レイヤーを読み取り用に開きます。 |
| [remove_at(index)](#remove_at_index_29) | 指定されたインデックスの [Feature](/psd/python-net/aspose.gis/feature/) を削除します。 |
| [replace_at(index, feature)](#replace_at_index_feature_30) | 指定されたインデックスの [Feature](/psd/python-net/aspose.gis/feature/) を置き換えます。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | フィーチャーシーケンスをレイヤーに保存します。 |
| [split_to()](#split_to__35) | ジオメトリタイプでフィーチャーを分割します。 |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | 属性インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。 |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | 属性インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。 |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | 空間インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) や Aspose.Gis.VectorLayer.NearestTo(float,float) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。 |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | 空間インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) や Aspose.Gis.VectorLayer.NearestTo(float,float) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。 |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | 属性値が指定された値と等しいフィーチャーを選択します。 |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | 属性値が指定された値より大きいフィーチャーを選択します。 |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | 属性値が指定された値以上のフィーチャーを選択します。 |
| [where_intersects(extent)](#where_intersects_extent_43) | 範囲に基づいてフィーチャをフィルタリングします。 |
| [where_intersects(geometry)](#where_intersects_geometry_44) | 提供されたジオメトリに基づいてフィーチャをフィルタリングします。 |
| [where_intersects(sequence)](#where_intersects_sequence_45) | 他のフィーチャシーケンス内のすべてのジオメトリの合成に基づいてフィーチャをフィルタリングします。 |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | 属性値が提供された値と等しくないフィーチャを選択します。 |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | 属性が null と等しくないフィーチャを選択します。 |
| [where_null(attribute_name)](#where_null_attribute_name_48) | 属性が null と等しいフィーチャを選択します。 |
| [where_set(attribute_name)](#where_set_attribute_name_49) | 属性が設定されているフィーチャを選択します。 |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | 属性値が提供された値より小さいフィーチャを選択します。 |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | 属性値が提供された値以下のフィーチャを選択します。 |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | 指定された属性が設定されていないフィーチャを選択します。 |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

レイヤーに新しいフィーチャーを追加します（[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) がサポートしている場合）。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 追加するフィーチャ。 |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

指定されたスタイルで新しいフィーチャーをレイヤーに追加します（[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) がサポートしている場合）。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 追加するフィーチャ。 |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | フィーチャのスタイル。欠落したスタイルを示すには <see langword="null" /> を使用します。 |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

InMemory 形式でレイヤーのクローンを作成します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | インメモリレイヤー。 |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

このレイヤーの属性コレクションと一致する属性を持つ新しいフィーチャーを作成します（ただしレイヤーには追加しません）。<br/>            フィーチャーのデータ設定が完了したら、[VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) を使用してフィーチャーをレイヤーに追加してください。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 新しいフィーチャ。 |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

レイヤーを別の形式に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_path | string | 変換されるレイヤーへのパス。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | ソースレイヤー用のフォーマットドライバー。 |
| destination_path | string | 変換の結果として作成されるレイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 宛先レイヤー用のフォーマットドライバー。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

レイヤーを別の形式に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 変換されるレイヤーへのパス。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | ソースレイヤー用のフォーマットドライバー。 |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 変換の結果として作成されるレイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 宛先レイヤー用のフォーマットドライバー。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

レイヤーを別の形式に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_path | string | 変換されるレイヤーへのパス。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | ソースレイヤー用のフォーマットドライバー。 |
| destination_path | string | 変換の結果として作成されるレイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 宛先レイヤー用のフォーマットドライバー。 |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 変換手順のオプション。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

レイヤーを別の形式に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 変換されるレイヤーへのパス。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | ソースレイヤー用のフォーマットドライバー。 |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 変換の結果として作成されるレイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 宛先レイヤー用のフォーマットドライバー。 |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 変換手順のオプション。 |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

他の [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の属性をこのレイヤーにコピーします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性をコピーするフィーチャシーケンス。 |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

他の [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) の属性をこのレイヤーにコピーします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性をコピーするフィーチャシーケンス。 |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | 属性を1つずつ処理するカスタム[IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/)のインスタンス。 |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

レイヤーを作成し、新しいフィーチャーの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み専用レイヤー。 |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

レイヤーを作成し、新しいフィーチャーの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み専用レイヤー。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

レイヤーを作成し、新しいフィーチャーの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み専用レイヤー。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

レイヤーを作成し、新しいフィーチャーの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み専用レイヤー。 |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

このレイヤーの空間範囲を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このレイヤーの空間範囲。 |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

ジオメトリでレイヤーを現在のレイヤーと交差させます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 交差させるレイヤー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 2つのレイヤーの交差結果としての新しいレイヤー。 |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

レイヤーを現在のレイヤーに結合します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 結合するレイヤー。 |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | 結合パラメータ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 2つのレイヤーを結合した結果としての新しいレイヤー。 |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

ジオメトリでレイヤーを現在のレイヤーに結合します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 結合するレイヤー。 |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | 結合パラメータ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 2つのレイヤーを結合した結果としての新しいレイヤー。 |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

指定されたポイントに最も近いフィーチャーを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 点。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 提供された点に最も近いフィーチャ。 |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

指定された座標に最も近いフィーチャーを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | 座標のX。 |
| y | double | 座標のY。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 提供された座標に最も近いフィーチャ。 |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り専用レイヤー。 |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り専用レイヤー。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り専用レイヤー。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り専用レイヤー。 |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

指定されたインデックスの [Feature](/psd/python-net/aspose.gis/feature/) を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | フィーチャのインデックス。 |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

指定されたインデックスの [Feature](/psd/python-net/aspose.gis/feature/) を置き換えます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | フィーチャのインデックス。 |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 設定するフィーチャ。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | string | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | string | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存手順のオプション。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存手順のオプション。 |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

ジオメトリタイプでフィーチャーを分割します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 同じジオメトリタイプを持つレイヤー。 |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

属性インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index_path | string | インデックスファイルへのパス。 |
| attribute_name | string | インデックスを構築する属性の名前。 |
| force_rebuild | bool | インデックスが既に存在していても再作成するかどうか。 |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

属性インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | インデックスファイルへのパス。 |
| attribute_name | string | インデックスを構築する属性の名前。 |
| force_rebuild | bool | インデックスが既に存在していても再作成するかどうか。 |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

空間インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) や Aspose.Gis.VectorLayer.NearestTo(float,float) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index_path | string | インデックスファイルへのパス。 |
| force_rebuild | bool | インデックスが既に存在していても再作成するかどうか。 |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

空間インデックスをロードして、Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) や Aspose.Gis.VectorLayer.NearestTo(float,float) のようなフィルタメソッドで属性値によるフィルタリングを高速化します。<br/>            インデックスが存在しない場合は最初に作成します。インデックスの再作成を強制するには <paramref name="forceRebuild" /> を使用してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | インデックスファイルへのパス。 |
| force_rebuild | bool | インデックスが既に存在していても再作成するかどうか。 |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

属性値が指定された値と等しいフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値と等しいフィーチャ。 |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

属性値が指定された値より大きいフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値より大きいフィーチャ。 |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

属性値が指定された値以上のフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値以上のフィーチャ。 |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

範囲に基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | フィルター範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 提供されたジオメトリと交差するフィーチャ。 |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

提供されたジオメトリに基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | ジオメトリをフィルタリング。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 提供されたジオメトリと交差するフィーチャ。 |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

他のフィーチャシーケンス内のすべてのジオメトリの合成に基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 他のフィーチャのシーケンス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 他のフィーチャシーケンス内のすべてのジオメトリのユニオンと交差するフィーチャ。 |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

属性値が提供された値と等しくないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値と等しくないフィーチャ。 |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

属性が null と等しくないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が null と等しくないフィーチャ。 |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

属性が null と等しいフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が null と等しいフィーチャ。 |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

属性が設定されているフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が設定されているフィーチャ。 |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

属性値が提供された値より小さいフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値より小さいフィーチャ。 |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

属性値が提供された値以下のフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値以下のフィーチャ。 |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

指定された属性が設定されていないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が未設定のフィーチャ。 |


