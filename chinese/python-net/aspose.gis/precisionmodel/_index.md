---
title: "PrecisionModel 类"
type: docs
weight: 3200
url: /zh/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | 返回一个精确的精度模型。<br/>根据精确精度模型，double 值中的所有数字都是有效的。 |
| is_exact | bool | r | 获取一个值，指示此精度模型是否精确。 |
| is_rounding | bool | r | 获取一个值，指示此精度模型是否进行四舍五入。 |
| significant_digits | int | r | 获取在四舍五入的精度模型中的有效数字位数。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | 返回一个四舍五入精度模型。<br/>根据四舍五入精度模型，只有有限数量的数字是有效的。 |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

返回一个四舍五入精度模型。<br/>根据四舍五入精度模型，只有有限数量的数字是有效的。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| significant_digits | int | 有效数字的位数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | 四舍五入精度模型。 |


