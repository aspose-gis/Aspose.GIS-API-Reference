---
title: "KmlLayer 类"
type: docs
weight: 140
url: /zh/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | 获取此 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 中特征的自定义属性集合。 |
| 计数 | 整数 | r | 获取此图层中的特征数量。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 获取实例化此图层的 [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/)。 |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | 获取要素列表。 |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | 获取图层几何的类型。 |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | 来自 GroundOverlay 节点的 KmlGroundOverlayInfo 列表 |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | 来自 NetworkLink 节点的 KmlNetworkLinkInfo 列表 |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | 来自 Region 节点的 KmlRegionInfo 列表 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 获取此图层的空间参考系统。对于 KML，始终为 WGS84。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | 向图层添加新要素，如果由 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的 [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) 支持。 |
| [add(feature, style)](#add_feature_style_2) | 向图层添加具有指定样式的新要素，如果由 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的 [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) 支持。 |
| [as_in_memory()](#as_in_memory__3) | 创建一个以 InMemory 格式的图层克隆。 |
| [construct_feature()](#construct_feature__4) | 创建（但不添加到图层）一个属性与此图层属性集合匹配的新要素。<br/>            完成要素数据设置后，使用 [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) 将要素添加到图层。 |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | 将图层转换为其他格式。 |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | 将图层转换为其他格式。 |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | 将图层转换为其他格式。 |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | 将图层转换为其他格式。 |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | 复制其他 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的属性到此图层。 |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | 复制其他 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的属性到此图层。 |
| [create(path, driver)](#create_path_driver_11) | 创建图层并打开以添加新要素。 |
| [create(path, driver)](#create_path_driver_12) | 创建图层并打开以添加新要素。 |
| [create(path, driver, options)](#create_path_driver_options_13) | 创建图层并打开以添加新要素。 |
| [create(path, driver, options)](#create_path_driver_options_14) | 创建图层并打开以添加新要素。 |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | 创建图层并以追加方式打开它。 |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | 创建图层并以追加方式打开它。 |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | 创建图层并以追加方式打开它。 |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | 创建图层并以追加方式打开它。 |
| [get_extent()](#get_extent__19) | 获取此图层的空间范围。 |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | 通过几何将一个图层与当前图层相交。 |
| [join(layer, options)](#join_layer_options_21) | 将一个图层加入当前图层。 |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | 通过几何将一个图层加入当前图层。 |
| [nearest_to(point)](#nearest_to_point_23) | 获取离提供的点最近的要素。 |
| [nearest_to(x, y)](#nearest_to_x_y_24) | 获取离提供的坐标最近的要素。 |
| [open(path, driver)](#open_path_driver_25) | 以读取方式打开图层。 |
| [open(path, driver)](#open_path_driver_26) | 以读取方式打开图层。 |
| [open(path, driver, options)](#open_path_driver_options_27) | 以读取方式打开图层。 |
| [open(path, driver, options)](#open_path_driver_options_28) | 以读取方式打开图层。 |
| [remove_at(index)](#remove_at_index_29) | 删除指定索引处的 [Feature](/psd/python-net/aspose.gis/feature/)。 |
| [replace_at(index, feature)](#replace_at_index_feature_30) | 替换指定索引处的 [Feature](/psd/python-net/aspose.gis/feature/)。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | 将要素序列保存到图层。 |
| [split_to()](#split_to__35) | 按几何类型拆分要素。 |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | 加载属性索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。 |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | 加载属性索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。 |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | 加载空间索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            和 Aspose.Gis.VectorLayer.NearestTo(float,float)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。 |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | 加载空间索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            和 Aspose.Gis.VectorLayer.NearestTo(float,float)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。 |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | 选择属性值等于提供值的要素。 |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | 选择属性值大于提供值的要素。 |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | 选择属性值大于或等于提供值的要素。 |
| [where_intersects(extent)](#where_intersects_extent_43) | 根据范围过滤要素。 |
| [where_intersects(geometry)](#where_intersects_geometry_44) | 根据提供的几何形状过滤要素。 |
| [where_intersects(sequence)](#where_intersects_sequence_45) | 根据其他要素序列中所有几何形状的并集过滤要素。 |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | 选择属性值不等于提供值的要素。 |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | 选择属性不等于 null 的要素。 |
| [where_null(attribute_name)](#where_null_attribute_name_48) | 选择属性等于 null 的要素。 |
| [where_set(attribute_name)](#where_set_attribute_name_49) | 选择已设置属性的要素。 |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | 选择属性值小于提供值的要素。 |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | 选择属性值小于或等于提供值的要素。 |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | 选择未设置指定属性的要素。 |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

向图层添加新要素，如果由 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的 [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) 支持。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 要添加的要素。 |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

向图层添加具有指定样式的新要素，如果由 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的 [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) 支持。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 要添加的要素。 |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | 要素样式。使用 <see langword=\"null\" /> 表示缺少样式。 |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

创建一个以 InMemory 格式的图层克隆。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 内存层。 |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

创建（但不添加到图层）一个属性与此图层属性集合匹配的新要素。<br/>            完成要素数据设置后，使用 [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) 将要素添加到图层。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 新要素。 |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

将图层转换为其他格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_path | string | 将被转换的图层路径。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 源图层的格式驱动程序。 |
| destination_path | string | 转换后将创建的图层路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 目标图层的格式驱动程序。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

将图层转换为其他格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 将被转换的图层路径。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 源图层的格式驱动程序。 |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 转换后将创建的图层路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 目标图层的格式驱动程序。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

将图层转换为其他格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_path | string | 将被转换的图层路径。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 源图层的格式驱动程序。 |
| destination_path | string | 转换后将创建的图层路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 目标图层的格式驱动程序。 |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 转换过程的选项。 |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

将图层转换为其他格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 将被转换的图层路径。 |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 源图层的格式驱动程序。 |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 转换后将创建的图层路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 目标图层的格式驱动程序。 |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 转换过程的选项。 |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

复制其他 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的属性到此图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 用于复制属性的要素序列。 |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

复制其他 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 的属性到此图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 用于复制属性的要素序列。 |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | 自定义 [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) 的实例，将逐个处理属性。 |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

创建图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只写层。 |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

创建图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只写层。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

创建图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只写层。 |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

创建图层并打开以添加新要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只写层。 |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

创建图层并以追加方式打开它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 一个 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 实例。 |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

获取此图层的空间范围。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此图层的空间范围。 |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

通过几何将一个图层与当前图层相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于相交的图层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 两个图层相交的结果生成的新图层。 |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

将一个图层加入当前图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于连接的图层。 |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | 连接参数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 两个图层连接的结果生成的新图层。 |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

通过几何将一个图层加入当前图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 用于连接的图层。 |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | 连接参数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 两个图层连接的结果生成的新图层。 |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

获取离提供的点最近的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 该点。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 提供的点最近的要素。 |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

获取离提供的坐标最近的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double | 坐标的 X。 |
| y | double | 坐标的 Y。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 提供的坐标最近的要素。 |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

以读取方式打开图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只读图层。 |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

以读取方式打开图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只读图层。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

以读取方式打开图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只读图层。 |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

以读取方式打开图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 要使用的驱动程序。 |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 驱动程序特定的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 只读图层。 |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

删除指定索引处的 [Feature](/psd/python-net/aspose.gis/feature/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | 整数 | 要素的索引。 |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

替换指定索引处的 [Feature](/psd/python-net/aspose.gis/feature/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | 整数 | 要素的索引。 |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 要设置的要素。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | string | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | string | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存过程的选项。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存过程的选项。 |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

按几何类型拆分要素。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 具有相同几何类型的图层。 |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

加载属性索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index_path | string | 索引文件的路径。 |
| attribute_name | string | 用于构建索引的属性名称。 |
| force_rebuild | bool | 即使索引已存在，是否重新创建索引。 |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

加载属性索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 索引文件的路径。 |
| attribute_name | string | 用于构建索引的属性名称。 |
| force_rebuild | bool | 即使索引已存在，是否重新创建索引。 |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

加载空间索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            和 Aspose.Gis.VectorLayer.NearestTo(float,float)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index_path | string | 索引文件的路径。 |
| force_rebuild | bool | 即使索引已存在，是否重新创建索引。 |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

加载空间索引以加速在过滤方法（如 Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            和 Aspose.Gis.VectorLayer.NearestTo(float,float)）中按属性值进行过滤。<br/>            如果索引不存在，则先创建。使用 <paramref name=\"forceRebuild\" /> 强制重新创建索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 索引文件的路径。 |
| force_rebuild | bool | 即使索引已存在，是否重新创建索引。 |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

选择属性值等于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值等于提供值的要素。 |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

选择属性值大于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值大于提供值的要素。 |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

选择属性值大于或等于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值大于或等于提供值的要素。 |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

根据范围过滤要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 过滤范围。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 与提供的几何相交的要素。 |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

根据提供的几何形状过滤要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 过滤几何。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 与提供的几何相交的要素。 |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

根据其他要素序列中所有几何形状的并集过滤要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 其他要素序列。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 与其他要素序列中所有几何的并集相交的要素。 |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

选择属性值不等于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值不等于提供的值的要素。 |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

选择属性不等于 null 的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值不等于 null 的要素。 |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

选择属性等于 null 的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值等于 null 的要素。 |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

选择已设置属性的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值已设置的要素。 |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

选择属性值小于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值小于提供的值的要素。 |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

选择属性值小于或等于提供值的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |
| value | object | 用于比较的值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值小于或等于提供的值的要素。 |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

选择未设置指定属性的要素。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 用于过滤的属性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性值未设置的要素。 |


