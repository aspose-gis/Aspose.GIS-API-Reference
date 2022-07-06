---
title: ProducePolygons
second_title: Справочник по Aspose.GIS for .NET API
description: Создает новый перечислитель IPolygon с заданным количеством случайных элементов все они находятся в заданном экстенте.
type: docs
weight: 30
url: /ru/net/aspose.gis.geotools/geogenerator/producepolygons/
---
## GeoGenerator.ProducePolygons method

Создает новый перечислитель IPolygon с заданным количеством случайных элементов, все они находятся в заданном экстенте.

```csharp
public static IEnumerable<IPolygon> ProducePolygons(Extent rect, PolygonGeneratorOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | Extent | Заданная область (см.[`Extent`](../../../aspose.gis/extent) ) |
| options | PolygonGeneratorOptions | Параметры создания полигона (см.[`PolygonGeneratorOptions`](../../polygongeneratoroptions) ) |

### Возвращаемое значение

Массив полигонов (см. перечисление[`IPolygon`](../../../aspose.gis.geometries/ipolygon) )

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Количество полигонов должно быть больше единицы. |
| NullReferenceException | Extent должен иметь значение (не быть NULL) |
| ArgumentException | Минимальная и максимальная длина должны быть не равны и больше 0 |
| ArgumentException | Максимальная длина должна быть больше минимальной |

### Смотрите также

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon)
* class [Extent](../../../aspose.gis/extent)
* class [PolygonGeneratorOptions](../../polygongeneratoroptions)
* class [GeoGenerator](../../geogenerator)
* пространство имен [Aspose.Gis.GeoTools](../../geogenerator)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->