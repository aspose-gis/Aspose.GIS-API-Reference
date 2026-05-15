---
title: "数据集类"
type: docs
weight: 590
url: /zh/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | 获取一个值，指示此数据集是否可以创建矢量图层。 |
| can_remove_layers | bool | r | 获取一个值，指示此数据集是否可以移除矢量图层。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 获取实例化此数据集的 [Dataset.driver](/psd/python-net/aspose.gis/dataset/)。 |
| layers_count | int | r | 获取此数据集中的图层数量。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | 创建一个数据集。 |
| [create(path, driver)](#create_path_driver_2) | 创建一个数据集。 |
| [create(path, driver, options)](#create_path_driver_options_3) | 创建一个数据集。 |
| [create(path, driver, options)](#create_path_driver_options_4) | 创建一个数据集。 |
| [create_layer()](#create_layer__5) | 创建一个新的矢量图层并将其打开以追加。 |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | 使用指定名称创建一个新的矢量图层并将其打开以追加。 |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | 使用指定名称创建一个新的矢量图层并将其打开以追加。 |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | 创建一个新的矢量图层并将其打开以追加。 |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | 创建一个新的矢量图层并将其打开以追加。 |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | 打开具有指定名称的图层以进行编辑。 |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | 打开具有指定名称的图层以进行编辑。 |
| [get_layer_name(index)](#get_layer_name_index_12) | 获取指定索引处图层的名称。 |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | 检查当前数据集是否具有具有特定名称的图层 |
| [open(path, driver)](#open_path_driver_14) | 打开数据集。 |
| [open(path, driver)](#open_path_driver_15) | 打开数据集。 |
| [open(path, driver, options)](#open_path_driver_options_16) | 打开数据集。 |
| [open(path, driver, options)](#open_path_driver_options_17) | 打开数据集。 |
| [open_layer(name, options)](#open_layer_name_options_18) | 打开具有指定名称的图层以进行读取。 |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | 打开指定索引处的图层以进行读取。 |
| [remove_layer(name)](#remove_layer_name_20) | 移除具有指定名称的矢量图层。 |
| [remove_layer_at(index)](#remove_layer_at_index_21) | 移除指定索引处的矢量图层。 |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | 重命名数据集中的图层 |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

创建一个数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

创建一个新的矢量图层并将其打开以追加。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个已打开用于写入的 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)。 |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

使用指定名称创建一个新的矢量图层并将其打开以追加。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 图层的名称。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新图层的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个已打开用于写入的 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)。 |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

使用指定名称创建一个新的矢量图层并将其打开以追加。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 图层的名称。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新图层的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个已打开用于写入的 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)。 |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

创建一个新的矢量图层并将其打开以追加。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新图层的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个已打开用于写入的 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)。 |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

创建一个新的矢量图层并将其打开以追加。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新图层的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个已打开用于写入的 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)。 |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

打开具有指定名称的图层以进行编辑。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 要编辑的图层名称。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新几何体的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 已打开用于编辑的图层。 |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

打开具有指定名称的图层以进行编辑。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 要编辑的图层索引。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 新几何体的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 已打开用于编辑的图层。 |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

获取指定索引处图层的名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 图层的索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 图层的名称。 |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

检查当前数据集是否具有具有特定名称的图层

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 图层名称 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" />, 如果数据集具有此名称的图层；否则，<see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

打开数据集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 数据集的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 一个 [Dataset](/psd/python-net/aspose.gis/dataset/) 的实例。 |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

打开具有指定名称的图层以进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 要打开的图层名称。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 已打开用于读取的图层。 |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

打开指定索引处的图层以进行读取。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 要打开的图层索引。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 打开选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 已打开用于读取的图层。 |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

移除具有指定名称的矢量图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 图层名称 |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

移除指定索引处的矢量图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 图层索引 |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

重命名数据集中的图层

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| current_name | string | 图层的当前名称 |
| new_name | string | 图层的新名称 |

