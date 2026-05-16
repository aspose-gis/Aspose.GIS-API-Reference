---
title: "RasterDriver クラス"
type: docs
weight: 3410
url: /ja/python-net/aspose.gis/rasterdriver/
---

**Summary:** A driver for a specific raster based format.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.RasterDriver

**Inheritance:** Driver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| can_open_layers | bool | r | このドライバーがラスターレイヤーを開くことができるかどうかを示す値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [open_layer(path)](#open_layer_path_1) | そのレイヤーを読み取り用に開きます。 |
| [open_layer(path)](#open_layer_path_2) | そのレイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_3) | そのレイヤーを読み取り用に開きます。 |
| [open_layer(path, options)](#open_layer_path_options_4) | そのレイヤーを読み取り用に開きます。 |


### Method: open_layer(path) {#open_layer_path_1}


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
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) のインスタンスです。 |


### Method: open_layer(path) {#open_layer_path_2}


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
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) のインスタンスです。 |


### Method: open_layer(path, options) {#open_layer_path_options_3}


```
 open_layer(path, options) 
```

そのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |
| options | [RasterDriverOptions](/psd/python-net/aspose.gis/rasterdriveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) のインスタンスです。 |


### Method: open_layer(path, options) {#open_layer_path_options_4}


```
 open_layer(path, options) 
```

そのレイヤーを読み取り用に開きます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ファイルへのパス。 |
| options | [RasterDriverOptions](/psd/python-net/aspose.gis/rasterdriveroptions) | ドライバー固有のオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) のインスタンスです。 |


