---
title: "OsmXmlDriver 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.formats.osmxml/osmxmldriver/
---

**Summary:** A driver for the OSM XML format.

**Module:** [aspose.gis.formats.osmxml](/psd/python-net/aspose.gis.formats.osmxml/)

**Full Name:** aspose.gis.formats.osmxml.OsmXmlDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | 获取一个值，指示此驱动程序是否可以创建数据集。 |
| can_create_layers | bool | r | 获取一个值，指示此驱动程序是否可以创建矢量图层。 |
| can_open_datasets | bool | r | 获取一个值，指示此驱动程序是否可以打开数据集。 |
| can_open_layers | bool | r | 获取一个值，指示此驱动程序是否可以打开矢量图层。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | 创建一个数据集。 |
| [create_dataset(path)](#create_dataset_path_2) | 创建一个数据集。 |
| [create_dataset(path, options)](#create_dataset_path_options_3) | 创建一个数据集。 |
| [create_dataset(path, options)](#create_dataset_path_options_4) | 创建一个数据集。 |
| [create_layer(path)](#create_layer_path_5) | 创建图层并以追加方式打开它。 |
| [create_layer(path)](#create_layer_path_6) | 创建图层并以追加方式打开它。 |
| [create_layer(path, options)](#create_layer_path_options_7) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options)](#create_layer_path_options_8) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options)](#create_layer_path_options_9) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | 创建一个图层并打开以添加新要素。 |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | 创建图层并以追加方式打开它。 |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | 创建图层并以追加方式打开它。 |
| [edit_layer(path, options)](#edit_layer_path_options_16) | 打开一个图层以进行编辑。 |
| [edit_layer(path, options)](#edit_layer_path_options_17) | 打开一个图层以进行编辑。 |
| [open_dataset(path)](#open_dataset_path_18) | 打开数据集。 |
| [open_dataset(path)](#open_dataset_path_19) | 打开数据集。 |
| [open_dataset(path, options)](#open_dataset_path_options_20) | 打开数据集。 |
| [open_dataset(path, options)](#open_dataset_path_options_21) | 打开数据集。 |
| [open_layer(path)](#open_layer_path_22) | 打开该图层进行读取。 |
| [open_layer(path)](#open_layer_path_23) | 打开该图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_24) | 打开一个图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_25) | 打开一个图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_26) | 打开一个图层进行读取。 |
| [open_layer(path, options)](#open_layer_path_options_27) | 打开一个图层进行读取。 |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | 确定指定的空间参考系统是否受驱动程序支持。 |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

创建一个图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

打开一个图层以进行编辑。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

打开一个图层以进行编辑。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 实例。 |


### Method: open_layer(path) {#open_layer_path_22}


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
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_layer(path) {#open_layer_path_23}


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
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

打开一个图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

打开一个图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

打开一个图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

打开一个图层进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

确定指定的空间参考系统是否受驱动程序支持。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 布尔值，指示指定的空间参考系统是否受驱动程序支持。 |


