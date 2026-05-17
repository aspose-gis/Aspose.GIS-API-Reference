---
title: "Класс NumericFormat"
type: docs
weight: 2870
url: /ru/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Преобразует и пытается обеспечить, чтобы числовое значение, преобразованное в<br/>            строку, было разобрано обратно в то же числовое значение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Преобразует число в текст фиксированной запятой без научной нотации. |
| [general(precision)](#general_precision_2) | Преобразует число в более компактный вариант либо фиксированной запятой, либо научной нотации,<br/>            в зависимости от типа числа и наличия спецификатора точности. Рекомендуется использовать. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Преобразует число в текст фиксированной запятой без научной нотации.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| significant_digits | int | Количество значимых цифр. Максимальная доступная точность — "308" |

**Returns**

| Тип | Описание |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Спецификатор точности округления. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Преобразует число в более компактный вариант либо фиксированной запятой, либо научной нотации,<br/>            в зависимости от типа числа и наличия спецификатора точности. Рекомендуется использовать.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| precision | int | Точность определяет максимальное количество значимых цифр, которые могут появиться в результирующей строке.<br/>            Если точность равна нулю, используется значение "15". Максимальная доступная точность — "17". |

**Returns**

| Тип | Описание |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Общий спецификатор формата. |


