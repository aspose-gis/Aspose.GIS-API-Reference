---
title: GeographicDatum
second_title: Справочник по Aspose.GIS for .NET API
description: Создает новый экземпляр.
type: docs
weight: 10
url: /ru/net/aspose.gis.spatialreferencing/geographicdatum/geographicdatum/
---
## GeographicDatum constructor

Создает новый экземпляр.

```csharp
public GeographicDatum(string name, Ellipsoid ellipsoid, 
    BursaWolfParameters toWgs84Parameters = null, Identifier identifier = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя этого элемента данных. |
| эллипсоид | Ellipsoid | Эллипсоид этой системы отсчета. Не может быть нулевым. |
| toWgs84Parameters | BursaWolfParameters | Параметры, которые могут быть заданы формуле bursa wolf для преобразования координат в этой системе координат в координаты системы WGS84. Если этот датум близок к WGS84 и преобразование не требуется, передайте параметры bursa wolf со всеми значениями, установленными на 0. Если значение null, ToWgs84 будет установлено на[`IsNull`](../../bursawolfparameters/isnull)параметры. |
| identifier | Identifier | Идентификатор этого элемента данных. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | ellipsoidравно null. |

### Смотрите также

* class [Ellipsoid](../../ellipsoid)
* class [BursaWolfParameters](../../bursawolfparameters)
* class [Identifier](../../identifier)
* class [GeographicDatum](../../geographicdatum)
* пространство имен [Aspose.Gis.SpatialReferencing](../../geographicdatum)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->