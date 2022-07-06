---
title: CreateFromWkt
second_title: Справочник по Aspose.GIS for .NET API
description: Создает новую SpatialReferenceSystem на основе строки WKT общеизвестный текст.
type: docs
weight: 20
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/
---
## SpatialReferenceSystem.CreateFromWkt method

Создает новую` SpatialReferenceSystem` на основе строки WKT (общеизвестный текст).

```csharp
public static SpatialReferenceSystem CreateFromWkt(string wkt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| wkt | String | Строка WKT. |

### Возвращаемое значение

Новый` SpatialReferenceSystem` .

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент:`null`. |
| FormatException | Иерархия значений wkt, их порядок или типы неверны. |
| NotSupportedException | Корневой элемент WKT не поддерживается (например, FITTED_CS). |

### Смотрите также

* method [TryCreateFromWkt](../trycreatefromwkt)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->