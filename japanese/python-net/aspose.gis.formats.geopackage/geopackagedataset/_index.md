---
title: "GeoPackageDataset クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | このデータセットがベクターレイヤーを作成できるかどうかを示す値を取得します。 |
| can_remove_layers | bool | r | このデータセットがベクターレイヤーを削除できるかどうかを示す値を取得します。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | このデータセットをインスタンス化した [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) を取得します。 |
| layers_count | int | r | このデータセット内のレイヤー数を取得します。 |
| tile_layers_count | int | r | このデータセット内のタイルレイヤー数を取得します。 |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | このメソッドはまだ開発中です。 |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | このメソッドはまだ開発中です。 |
| [get_layer_name(index)](#get_layer_name_index_12) | 指定されたインデックスのレイヤー名を取得します。 |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | 指定されたインデックスのタイルレイヤー名を取得します。 |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | 現在のデータセットに特定の名前のレイヤーがあるか確認します。 |
| [open(path, driver)](#open_path_driver_15) | データセットを開きます。 |
| [open(path, driver)](#open_path_driver_16) | データセットを開きます。 |
| [open(path, driver, options)](#open_path_driver_options_17) | データセットを開きます。 |
| [open(path, driver, options)](#open_path_driver_options_18) | データセットを開きます。 |
| [open(path, options)](#open_path_options_19) | gpkg ファイルからデータセットを作成するためのファクトリメソッドです。 |
| [open_layer(name, options)](#open_layer_name_options_20) | 指定された名前のレイヤーを読み取り用に開きます。 |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | 指定されたインデックスのレイヤーを読み取り用に開きます。 |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | 指定されたインデックスのレイヤーを読み取り用に開きます。 |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | 指定された名前のタイルレイヤーを読み取り用に開きます。 |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | 指定されたインデックスのタイルレイヤーを読み取り用に開きます。 |
| [remove_layer(name)](#remove_layer_name_25) | 指定された名前のベクターレイヤーを削除します。 |
| [remove_layer_at(index)](#remove_layer_at_index_26) | 指定されたインデックスのベクターレイヤーを削除します。 |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | データセット内のレイヤーの名前を変更します |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | gpkg ファイルへのパス。 |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | gpkg ファイルの読み取りに関する特有の設定です。 |

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

このメソッドはまだ開発中です。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 編集するレイヤーの名前。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいジオメトリの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

このメソッドはまだ開発中です。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 編集するレイヤーのインデックス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | オープンオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新しいジオメトリの空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


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


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

指定されたインデックスのタイルレイヤー名を取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | レイヤーのインデックス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | レイヤーの名前。 |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


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


### Method: open(path, driver)  [static] {#open_path_driver_15}


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


### Method: open(path, driver)  [static] {#open_path_driver_16}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


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


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

gpkg ファイルからデータセットを作成するためのファクトリメソッドです。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | gpkg ファイルへのパス。 |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | gpkg ファイルの読み取りに関する特有の設定です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

指定されたインデックスのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 開くレイヤーのインデックス。 |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | オープンオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 読み取り用に開かれたレイヤーです。 |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

指定された名前のタイルレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 開くレイヤーの名前。 |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | オープンオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | タイルレイヤーが読み取り用に開かれました。 |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

指定されたインデックスのタイルレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 開くレイヤーのインデックス。 |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | オープンオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

指定された名前のベクターレイヤーを削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | レイヤーの名前 |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

指定されたインデックスのベクターレイヤーを削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | レイヤーのインデックス |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

データセット内のレイヤーの名前を変更します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| current_name | string | レイヤーの現在の名前 |
| new_name | string | レイヤーの新しい名前 |

