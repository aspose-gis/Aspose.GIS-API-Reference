---
title: "DynamicFeature 类"
type: docs
weight: 650
url: /zh/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | 获取或设置要素的几何形状。<br/>            不能为 <see langword=\"null\" />，请使用 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) 来表示缺失的几何形状。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | 从另一个要素复制属性值。 |
| [get_as_node()](#get_as_node__2) | 获取特征作为节点。这对于自定义数据可能有帮助 |
| [get_value(attribute_name)](#get_value_attribute_name_3) | 获取属性的值。 |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | 获取属性的值，如果该值未设置或为 <c>null</c>，则返回 [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/)。 |
| [get_values(values, default_value)](#get_values_values_default_value_5) | 返回所有属性的值数组。 |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | 返回所有属性的值数组。 |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | 返回所有属性的值数组。<br/>            考虑使用 Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) 方法以避免额外的内存分配。 |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | 以列表形式获取属性序列的值。 |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | 确定指定属性是否已显式设置为 <c>null</c> 值。 |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | 检查此特性中属性值是否已设置。 |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | 设置属性的新值。 |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | 将属性的值设置为 <c>null</c>。 |
| [set_values(values)](#set_values_values_13) | 为所有属性设置新值。<br/>            还可以考虑使用 [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) 方法在一次调用中简化设置值的过程。 |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | 从此特性中移除属性值。 |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

从另一个要素复制属性值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | 要从中复制值的特性。 |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

获取特征作为节点。这对于自定义数据可能有帮助

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | 指向特征的 NodeLink |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

获取属性的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| object | 属性的值。 |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

获取属性的值，如果该值未设置或为 <c>null</c>，则返回 [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |
| default_value | object | 如果属性值缺失时返回的值。默认值为 <see langword=\"null\" />。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| object | 属性的值。 |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

返回所有属性的值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| values | object | 用于复制属性值的数组。 |
| default_value | object | 如果属性值缺失（未设置）时返回的值。默认值为 <see langword=\"null\" />。<br/>            考虑使用 '.Value' 来区分 'unset' 和 '<see langword=\"null\" />' 值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 已复制的属性数量。 |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

返回所有属性的值数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| values_count | int | 值的计数。 |
| default_value | object | 如果属性值缺失（未设置）时返回的值。默认值为 <see langword=\"null\" />。<br/>            考虑使用 '.Value' 来区分 'unset' 和 '<see langword=\"null\" />' 值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| object | 已复制的属性数量。 |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

返回所有属性的值数组。<br/>            考虑使用 Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) 方法以避免额外的内存分配。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| default_value | object | 如果属性值缺失（未设置）时返回的值。默认值为 <see langword=\"null\" />。<br/>            考虑使用 '.Value' 来区分 'unset' 和 '<see langword=\"null\" />' 值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| object | 用于复制属性值的新数组。 |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

以列表形式获取属性序列的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |
| separator | string | 用于分隔属性名称和序列索引值的字符串。 |
| 计数 | int | 返回的值计数（缺失的值填充为 null） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| object | 属性值的列表，其名称因序列索引值而不同。 |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

确定指定属性是否已显式设置为 <c>null</c> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果属性值为 <c>null</c>；否则为 <see langword=\"false\" />。 |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

检查此特性中属性值是否已设置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果已设置指定属性的值；否则为 <see langword=\"false\" />。 |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

设置属性的新值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |
| value | object | 属性的值。 |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

将属性的值设置为 <c>null</c>。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

为所有属性设置新值。<br/>            还可以考虑使用 [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) 方法在一次调用中简化设置值的过程。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| values | object | 新值的数组。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 已设置属性值的数量。 |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

从此特性中移除属性值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute_name | string | 属性的名称。 |

