---
title: Rounding
second_title: Справочник по Aspose.GIS for .NET API
description: Возвращает модель точности округления. В соответствии с моделью точности округления значащим является только ограниченное количество цифр.
type: docs
weight: 20
url: /ru/net/aspose.gis/precisionmodel/rounding/
---
## PrecisionModel.Rounding method

Возвращает модель точности округления. В соответствии с моделью точности округления значащим является только ограниченное количество цифр.

```csharp
public static PrecisionModel Rounding(int significantDigits)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| significantDigits | Int32 | Количество значащих цифр. |

### Возвращаемое значение

Модель точности округления.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Количество значащих цифр меньше 0 или больше 15. |

### Примечания

При применении к координате используется следующий код для уменьшения точности:

```csharp
double rounded = Math.Round(value, significantDigits);
```

### Смотрите также

* class [PrecisionModel](../../precisionmodel)
* пространство имен [Aspose.Gis](../../precisionmodel)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->