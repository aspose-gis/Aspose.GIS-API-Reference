---
title: "RasterDriver 类"
type: docs
weight: 3410
url: /zh/python-net/aspose.gis/rasterdriver/
---

**Summary:** A driver for a specific raster based format.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.RasterDriver

**Inheritance:** Driver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| can_open_layers | bool | r | 获取一个值，指示此驱动程序是否可以打开栅格图层。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [open_layer(path)](#open_layer_path_1) | 打开该图层进行读取。 |
| [open_layer(path)](#open_layer_path_2) | 打开该图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_3) | 打开该图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_4) | 打开该图层进行读取。 |


### Method: open_layer(path) {#open_layer_path_1}


```
 open_layer(path) 
```

打开该图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 一个 [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 实例。 |


### Method: open_layer(path) {#open_layer_path_2}


```
 open_layer(path) 
```

打开该图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 一个 [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_3}


```
 open_layer(path, options) 
```

打开该图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [RasterDriverOptions](/psd/python-net/aspose.gis/rasterdriveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 一个 [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_4}


```
 open_layer(path, options) 
```

打开该图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [RasterDriverOptions](/psd/python-net/aspose.gis/rasterdriveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 一个 [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 实例。 |


