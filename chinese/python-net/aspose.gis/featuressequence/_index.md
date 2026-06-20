---
title: "FeaturesSequence 类"
type: docs
weight: 870
url: /zh/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | 获取此 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 中特征的自定义属性集合。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 获取此要素序列的空间参考系统。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | 获取此图层的空间范围。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | 将要素序列保存到图层。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | 将要素序列保存到图层。 |
| [split_to()](#split_to__6) | 按几何类型拆分要素。 |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | 选择属性值等于提供值的要素。 |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | 选择属性值大于提供值的要素。 |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | 选择属性值大于或等于提供值的要素。 |
| [where_intersects(extent)](#where_intersects_extent_10) | 根据范围过滤要素。 |
| [where_intersects(geometry)](#where_intersects_geometry_11) | 根据提供的几何形状过滤要素。 |
| [where_intersects(sequence)](#where_intersects_sequence_12) | 根据其他要素序列中所有几何形状的并集过滤要素。 |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | 选择属性值不等于提供值的要素。 |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | 选择属性不等于 null 的要素。 |
| [where_null(attribute_name)](#where_null_attribute_name_15) | 选择属性等于 null 的要素。 |
| [where_set(attribute_name)](#where_set_attribute_name_16) | 选择已设置属性的要素。 |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | 选择属性值小于提供值的要素。 |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | 选择属性值小于或等于提供值的要素。 |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | 选择未设置指定属性的要素。 |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

获取此图层的空间范围。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此图层的空间范围。 |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | string | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

将要素序列保存到图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 输出图层的路径。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 输出图层的格式驱动程序。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


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

### Method: split_to() {#split_to__6}


```
 split_to() 
```

按几何类型拆分要素。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 具有相同几何类型的图层。 |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


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


### Method: where_intersects(extent) {#where_intersects_extent_10}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


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


