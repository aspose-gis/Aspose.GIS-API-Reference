---
title: "NumericFormat 类"
type: docs
weight: 2870
url: /zh/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | 转换并尝试确保被转换为<br/>            字符串的数值能够解析回相同的数值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | 将数字转换为固定小数点文本，不使用科学计数法。 |
| [general(precision)](#general_precision_2) | 根据数字类型以及是否存在精度说明符，将数字转换为固定小数点或科学计数法中更紧凑的形式。推荐使用。 |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

将数字转换为固定小数点文本，不使用科学计数法。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| significant_digits | int | 有效数字的位数。最大可用精度为 "308" |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 四舍五入精度说明符。 |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

根据数字类型以及是否存在精度说明符，将数字转换为固定小数点或科学计数法中更紧凑的形式。推荐使用。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| precision | int | 精度定义了结果字符串中可能出现的最大有效数字位数。<br/>            如果精度为零，则使用值 "15"。最大可用精度为 "17"。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 通用格式说明符。 |


