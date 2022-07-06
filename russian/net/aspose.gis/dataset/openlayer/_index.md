---
title: OpenLayer
second_title: Справочник по Aspose.GIS for .NET API
description: Открывает для чтения слой с указанным именем.
type: docs
weight: 110
url: /ru/net/aspose.gis/dataset/openlayer/
---
## Dataset.OpenLayer method

Открывает для чтения слой с указанным именем.

```csharp
public abstract VectorLayer OpenLayer(string name, DriverOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя открываемого слоя. |
| options | DriverOptions | Открыть опции. |

### Возвращаемое значение

Слой открыт для чтения.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Слой с указанным именем не существует;&lt;cr /&gt; Объект параметров имеет неправильный тип для этого набора данных. |
| ArgumentException | Объект Options имеет неверный тип для этого набора данных. |
| ArgumentNullException | Имя`null`. |
| [GisException](../../gisexception) | Ошибка чтения объекта из слоя. |
| IOException | Произошла ошибка ввода-вывода. |

### Смотрите также

* class [VectorLayer](../../vectorlayer)
* class [DriverOptions](../../driveroptions)
* class [Dataset](../../dataset)
* пространство имен [Aspose.Gis](../../dataset)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->