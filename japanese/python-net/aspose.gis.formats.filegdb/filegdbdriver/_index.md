---
title: "FileGdbDriver クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | このドライバーがデータセットを作成できるかどうかを示す値を取得します。 |
| can_create_layers | bool | r | このドライバーがベクターレイヤーを作成できるかどうかを示す値を取得します。 |
| can_open_datasets | bool | r | このドライバーがデータセットを開くことができるかどうかを示す値を取得します。 |
| can_open_layers | bool | r | このドライバーがベクターレイヤーを開くことができるかどうかを示す値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | データセットを作成します。 |
| [create_dataset(path)](#create_dataset_path_2) | データセットを作成します。 |
| [create_dataset(path, options)](#create_dataset_path_options_3) | データセットを作成します。 |
| [create_dataset(path, options)](#create_dataset_path_options_4) | データセットを作成します。 |
| [create_dataset(path, options)](#create_dataset_path_options_5) | データセットを作成します。 |
| [create_dataset(path, options)](#create_dataset_path_options_6) | データセットを作成します。 |
| [create_layer(path)](#create_layer_path_7) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create_layer(path)](#create_layer_path_8) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create_layer(path, options)](#create_layer_path_options_9) | レイヤーを作成し、新しいフィーチャの追加のために開きます。 |
| [create_layer(path, options)](#create_layer_path_options_10) | レイヤーを作成し、新しいフィーチャの追加のために開きます。 |
| [create_layer(path, options)](#create_layer_path_options_11) | レイヤーを作成し、新しいフィーチャの追加のために開きます。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | レイヤーを作成し、追加書き込み用に開きます。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | レイヤーを作成し、追加書き込み用に開きます。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | レイヤーを作成し、追加書き込み用に開きます。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | レイヤーを作成し、追加書き込み用に開きます。 |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | レイヤーを作成し、追加書き込みのために開きます。 |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | レイヤーを作成し、追加書き込みのために開きます。 |
| [edit_layer(path, options)](#edit_layer_path_options_18) | レイヤーを編集用に開きます。 |
| [edit_layer(path, options)](#edit_layer_path_options_19) | レイヤーを編集用に開きます。 |
| [open_dataset(path)](#open_dataset_path_20) | データセットを開きます。 |
| [open_dataset(path)](#open_dataset_path_21) | データセットを開きます。 |
| [open_dataset(path, options)](#open_dataset_path_options_22) | データセットを開きます。 |
| [open_dataset(path, options)](#open_dataset_path_options_23) | データセットを開きます。 |
| [open_dataset(path, options)](#open_dataset_path_options_24) | データセットを開きます。 |
| [open_dataset(path, options)](#open_dataset_path_options_25) | データセットを開きます。 |
| [open_layer(path)](#open_layer_path_26) | そのレイヤーを読み取り用に開きます。 |
| [open_layer(path)](#open_layer_path_27) | そのレイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_28) | レイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_29) | レイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_30) | レイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_31) | レイヤーを読み取り用に開きます。 |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | 指定された空間参照系がドライバーでサポートされているかどうかを判定します。 |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


```
 create_dataset(path, options) 
```

データセットを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: create_layer(path) {#create_layer_path_7}


```
 create_layer(path) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path) {#create_layer_path_8}


```
 create_layer(path) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

レイヤーを作成し、新しいフィーチャの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

レイヤーを作成し、新しいフィーチャの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

レイヤーを作成し、新しいフィーチャの追加のために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込み用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込み用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込み用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


```
 create_layer(path, options, spatial_reference_system) 
```

レイヤーを作成し、追加書き込み用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


```
 create_layer(path, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


```
 create_layer(path, spatial_reference_system) 
```

レイヤーを作成し、追加書き込みのために開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


```
 edit_layer(path, options) 
```

レイヤーを編集用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


```
 edit_layer(path, options) 
```

レイヤーを編集用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_dataset(path) {#open_dataset_path_21}


```
 open_dataset(path) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


```
 open_dataset(path, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | データセットへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


```
 open_dataset(path, options) 
```

データセットを開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | データセットへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | [Dataset](/psd/python-net/aspose.gis/dataset/) のインスタンス。 |


### Method: open_layer(path) {#open_layer_path_26}


```
 open_layer(path) 
```

そのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_layer(path) {#open_layer_path_27}


```
 open_layer(path) 
```

そのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_layer(path, options) {#open_layer_path_options_29}


```
 open_layer(path, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: open_layer(path, options) {#open_layer_path_options_31}


```
 open_layer(path, options) 
```

レイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) のインスタンス。 |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

指定された空間参照系がドライバーでサポートされているかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 指定された空間参照系がドライバーでサポートされているかどうかを示すブール値。 |


