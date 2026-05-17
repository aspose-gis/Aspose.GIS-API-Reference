---
title: "PrecisionModel Sınıfı"
type: docs
weight: 3200
url: /tr/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Tam bir hassasiyet modeli döndürür.<br/>            Tam hassasiyet modeline göre, bir double değerindeki tüm basamaklar anlamlıdır. |
| is_exact | bool | r | Bu hassasiyet modelinin tam olup olmadığını gösteren bir değer alır. |
| is_rounding | bool | r | Bu hassasiyet modelinin yuvarlama yapıp yapmadığını gösteren bir değer alır. |
| significant_digits | int | r | Yuvarlama yapıyorsa, bir hassasiyet modelindeki anlamlı basamak sayısını alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Yuvarlama hassasiyet modeli döndürür.<br/>            Yuvarlama hassasiyet modeline göre yalnızca sınırlı sayıda basamak anlamlıdır. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Yuvarlama hassasiyet modeli döndürür.<br/>            Yuvarlama hassasiyet modeline göre yalnızca sınırlı sayıda basamak anlamlıdır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| significant_digits | int | Anlamlı basamak sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Yuvarlama Hassasiyet modeli. |


