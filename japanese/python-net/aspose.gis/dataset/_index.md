---
title: "データセット クラス"
type: docs
weight: 590
url: /ja/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | このデータセットがベクターレイヤーを作成できるかどうかを示す値を取得します。 |
| can_remove_layers | bool | r | このデータセットがベクターレイヤーを削除できるかどうかを示す値を取得します。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | このデータセットをインスタンス化した [Dataset.driver](/psd/python-net/aspose.gis/dataset/) を取得します。 |
| layers_count | int | r | このデータセット内のレイヤー数を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | データセットを作成します。 |
| [create(path, driver)](#create_path_driver_2) | データセットを作成します。 |
| [create(path, driver, options)](#create_path_driver_options_3) | データセットを作成します。 |
| [create(path, driver, options)](#create_path_driver_options_4) | データセットを作成します。 |
| [create_layer()](#create_layer__5) | 新しいベクターレイヤーを作成し、追加用に開きます。 |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | 指定された名前で新しいベクターレイヤーを作成し、追加用に開きます。 |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | 指定された名前で新しいベクターレイヤーを作成し、追加用に開きます。 |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | 新しいベクターレイヤーを作成し、追加用に開きます。 |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | 新しいベクターレイヤーを作成し、追加用に開きます。 |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | 指定された名前のレイヤーを編集用に開きます。 |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | 指定された名前のレイヤーを編集用に開きます。 |
| [get_layer_name(index)](#get_layer_name_index_12) | 指定されたインデックスのレイヤー名を取得します。 |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | 現在のデータセットに特定の名前のレイヤーがあるか確認します。 |
| [open(path, driver)](#open_path_driver_14) | データセットを開きます。 |
| [open(path, driver)](#open_path_driver_15) | データセットを開きます。 |
| [open(path, driver, options)](#open_path_driver_options_16) | データセットを開きます。 |
| [open(path, driver, options)](#open_path_driver_options_17) | データセットを開きます。 |
| [open_layer(name, options)](#open_layer_name_options_18) | 指定された名前のレイヤーを読み取り用に開きます。 |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | 指定されたインデックスのレイヤーを読み取り用に開きます。 |
| [remove_layer(name)](#remove_layer_name_20) | 指定された名前のベクターレイヤーを削除します。 |
| [remove_layer_at(index)](#remove_layer_at_index_21) | 指定されたインデックスのベクターレイヤーを削除します。 |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | データセット内のレイヤーの名前を変更します |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

新しいベクターレイヤーを作成し、追加用に開きます。

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み用に開かれた[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)です。 |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

指定された名前で新しいベクターレイヤーを作成し、追加用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | レイヤーの名前。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいレイヤーの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み用に開かれた[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)です。 |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

指定された名前で新しいベクターレイヤーを作成し、追加用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | レイヤーの名前。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいレイヤーの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み用に開かれた[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)です。 |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

新しいベクターレイヤーを作成し、追加用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいレイヤーの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み用に開かれた[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)です。 |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

新しいベクターレイヤーを作成し、追加用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいレイヤーの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 書き込み用に開かれた[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)です。 |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

指定された名前のレイヤーを編集用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 編集するレイヤーの名前。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいジオメトリの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 編集用に開かれたレイヤーです。 |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

指定された名前のレイヤーを編集用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 編集するレイヤーのインデックス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいジオメトリの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 編集用に開かれたレイヤーです。 |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

指定されたインデックスのレイヤー名を取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | レイヤーのインデックス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | レイヤーの名前。 |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

現在のデータセットに特定の名前のレイヤーがあるか確認します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | レイヤーの名前 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" />, データセットにこの名前のレイヤーがある場合; それ以外の場合は <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 使用するドライバー。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

指定された名前のレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 開くレイヤーの名前。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り用に開かれたレイヤーです。 |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

指定されたインデックスのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 開くレイヤーのインデックス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り用に開かれたレイヤーです。 |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

指定された名前のベクターレイヤーを削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | レイヤーの名前 |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

指定されたインデックスのベクターレイヤーを削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | レイヤーのインデックス |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

データセット内のレイヤーの名前を変更します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| current_name | string | レイヤーの現在の名前 |
| new_name | string | レイヤーの新しい名前 |

