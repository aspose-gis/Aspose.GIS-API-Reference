---
title: "NumericFormat クラス"
type: docs
weight: 2870
url: /ja/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | 数値を文字列に変換し、同じ数値に再解析できるように変換と保証を試みます。<br/>             |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | 数値を指数表記なしの固定小数点テキストに変換します。 |
| [general(precision)](#general_precision_2) | 数値の種類と精度指定子の有無に応じて、固定小数点表記または指数表記のいずれか、よりコンパクトな形式に変換します。<br/>            使用が推奨されます。 |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

数値を指数表記なしの固定小数点テキストに変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| significant_digits | int | 有効数字の数。利用可能な最大精度は "308" です |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 丸め精度指定子です。 |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

数値の種類と精度指定子の有無に応じて、固定小数点表記または指数表記のいずれか、よりコンパクトな形式に変換します。<br/>            使用が推奨されます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| precision | int | 精度は、結果文字列に表示できる最大有効数字数を定義します。<br/>            精度が0の場合、値 "15" が使用されます。利用可能な最大精度は "17" です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 一般フォーマット指定子です。 |


