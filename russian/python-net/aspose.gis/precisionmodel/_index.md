---
title: "Класс PrecisionModel"
type: docs
weight: 3200
url: /ru/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Возвращает точную модель точности.<br/>            Согласно точной модели точности все цифры в значении типа double являются значимыми. |
| is_exact | bool | r | Получает значение, указывающее, является ли эта модель точности точной. |
| is_rounding | bool | r | Получает значение, указывающее, использует ли эта модель точности округление. |
| significant_digits | int | r | Получает количество значимых цифр в модели точности, если она использует округление. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Возвращает модель точности с округлением.<br/>            Согласно модели точности с округлением только ограниченное количество цифр является значимым. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Возвращает модель точности с округлением.<br/>            Согласно модели точности с округлением только ограниченное количество цифр является значимым.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| significant_digits | int | Количество значимых цифр. |

**Returns**

| Тип | Описание |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Модель точности с округлением. |


