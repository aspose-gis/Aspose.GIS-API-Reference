---
title: "PrecisionModel クラス"
type: docs
weight: 3200
url: /ja/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | 正確な精度モデルを返します。<br/>            正確な精度モデルでは、double 値のすべての桁が有効です。 |
| is_exact | bool | r | この精度モデルが正確かどうかを示す値を取得します。 |
| is_rounding | bool | r | この精度モデルが丸めかどうかを示す値を取得します。 |
| significant_digits | int | r | 丸めの場合、精度モデルの有効桁数を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | 丸め精度モデルを返します。<br/>            丸め精度モデルでは、限られた桁数のみが有効です。 |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

丸め精度モデルを返します。<br/>            丸め精度モデルでは、限られた桁数のみが有効です。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| significant_digits | int | 有効桁数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | 丸め精度モデル。 |


