---
title: Flat
second_title: Справочник по Aspose.GIS for .NET API
description: Преобразует число в текст с фиксированной точкой без научного представления.
type: docs
weight: 20
url: /ru/net/aspose.gis/numericformat/flat/
---
## NumericFormat.Flat method

Преобразует число в текст с фиксированной точкой без научного представления.

```csharp
public static NumericFormat Flat(int significantDigits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| significantDigits | Int32 | Количество значащих цифр. Максимально доступная точность равна "308" |

### Возвращаемое значение

Спецификатор точности округления.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Количество значащих цифр меньше 0 или больше 308. |

### Примечания

Внутренний код генерирует числовые строки для WKT через:координату.ToString("0.##. .", CultureInfo.InvariantCulture) решение.

### Смотрите также

* class [NumericFormat](../../numericformat)
* пространство имен [Aspose.Gis](../../numericformat)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->