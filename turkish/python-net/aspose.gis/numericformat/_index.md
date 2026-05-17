---
title: "NumericFormat Sınıfı"
type: docs
weight: 2870
url: /tr/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Sayısal bir değerin<br/>            dizeye dönüştürülüp aynı sayısal değere geri ayrıştırılmasını sağlamaya çalışır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Bir sayıyı bilimsel gösterim olmadan sabit noktalı metne dönüştürür. |
| [general(precision)](#general_precision_2) | Sayının türüne ve bir hassasiyet belirteci olup olmadığına bağlı olarak sabit noktalı veya bilimsel gösterimden daha kompakt olanına dönüştürür,<br/>            kullanılması önerilir. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Bir sayıyı bilimsel gösterim olmadan sabit noktalı metne dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| significant_digits | int | Significant digits sayısı. Kullanılabilir en yüksek hassasiyet "308". |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Yuvarlama Hassasiyeti Belirleyicisi. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Sayının türüne ve bir hassasiyet belirteci olup olmadığına bağlı olarak sabit noktalı veya bilimsel gösterimden daha kompakt olanına dönüştürür,<br/>            kullanılması önerilir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| precision | int | Hassasiyet, sonuç dizesinde görünebilecek en fazla anlamlı basamak sayısını tanımlar.<br/>            Hassasiyet sıfır ise, "15" değeri kullanılır. Kullanılabilir en yüksek hassasiyet "17". |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Genel Biçim Belirleyicisi. |


