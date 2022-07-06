---
title: GetValues
second_title: Справочник по Aspose.GIS for .NET API
description: Возвращает значения для всех атрибутов в массиве.
type: docs
weight: 50
url: /ru/net/aspose.gis/feature/getvalues/
---
## Feature.GetValues method

Возвращает значения для всех атрибутов в массиве.

```csharp
public int GetValues(object[] values, object defaultValue = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| values | Object[] | Массив, в который копируются значения атрибутов. |
| defaultValue | Object | Возвращаемое значение, если значение атрибута отсутствует (не установлено). Значение по умолчанию:`null`. Рассмотрите возможность использования 'DBNull.Value' для разделения значений 'unset' и '`null`'. |

### Возвращаемое значение

Скопировано несколько атрибутов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент:`null`. |
| InvalidOperationException | Атрибут не заблокирован. |

### Примечания

Атрибуты значений объекта копируются в массив значений, который передается в качестве параметра. Для атрибутов с неустановленным значением возвращается указанный параметр 'unsetValue'. &lt;br /&gt; Длина массива значений не обязательно должна совпадать с количеством атрибутов в признаке. Если длина массива больше количества атрибутов, все значения атрибутов копируются в массив; если меньше, в массив копируется только длина массива число значений атрибута, начиная со значения атрибута с порядковым номером 0.

### Смотрите также

* class [Feature](../../feature)
* пространство имен [Aspose.Gis](../../feature)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->