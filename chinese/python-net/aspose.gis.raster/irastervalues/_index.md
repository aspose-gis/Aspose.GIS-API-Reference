---
title: "IRasterValues 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | 将指定波段数据转换为 <see langword=\"bool\" /> 值。 |
| [as_byte(band_index)](#as_byte_band_index_2) | 将指定波段数据转换为 <see langword=\"byte\" /> 值。 |
| [as_double(band_index)](#as_double_band_index_3) | 将指定波段数据转换为 <see langword=\"double\" /> 值。 |
| [as_float(band_index)](#as_float_band_index_4) | 将指定波段数据转换为 <see langword=\"float\" /> 值。 |
| [as_integer(band_index)](#as_integer_band_index_5) | 将指定波段数据转换为 <see langword=\"int\" /> 值。 |
| [as_long(band_index)](#as_long_band_index_6) | 将指定波段数据转换为 <see langword=\"long\" /> 值。 |
| [as_short(band_index)](#as_short_band_index_7) | 将指定波段数据转换为 <see langword=\"short\" /> 值。 |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | 检查该值在指定波段中是否表示背景或 'no data'。 |
| [get_data_type(band_index)](#get_data_type_band_index_9) | 获取值的类型。 |
| [is_null(band_index)](#is_null_band_index_10) | 检查在指定波段中是否设置了栅格值。 |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

将指定波段数据转换为 <see langword=\"bool\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 转换后的值。 |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

将指定波段数据转换为 <see langword=\"byte\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 转换后的值。 |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

将指定波段数据转换为 <see langword=\"double\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 转换后的值。 |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

将指定波段数据转换为 <see langword=\"float\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 浮点数 | 转换后的值。 |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

将指定波段数据转换为 <see langword=\"int\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 整数 | 转换后的值。 |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

将指定波段数据转换为 <see langword=\"long\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 长整数 | 转换后的值。 |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

将指定波段数据转换为 <see langword=\"short\" /> 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| short | 转换后的值。 |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

检查该值在指定波段中是否表示背景或 'no data'。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果表示背景或 'no data'，返回 'true'。 |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

获取值的类型。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | 值的类型。 |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

检查在指定波段中是否设置了栅格值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | 整数 | 波段的索引。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果不存在，返回 'false'。 |


