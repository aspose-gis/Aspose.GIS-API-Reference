---
title: IGeometry.Union
second_title: Справочник по Aspose.GIS for .NET API
description: IGeometry метод. Объединяет эту геометрию и указанную геометрию.
type: docs
weight: 370
url: /ru/net/aspose.gis.geometries/igeometry/union/
---
## IGeometry.Union method

Объединяет эту геометрию и указанную геометрию.

```csharp
public IGeometry Union(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия, с которой можно объединиться. |

### Возвращаемое значение

Геометрия, представляющая объединение этой геометрии и аргумента. Результирующая геометрия содержит набор точек, присутствующих в этой геометрии или в аргументе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *other* является`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) для преобразования геометрии в одну и ту же систему отсчета пространственного . |

### Смотрите также

* interface [IGeometry](../)
* пространство имен [Aspose.Gis.Geometries](../../igeometry/)
* сборка [Aspose.GIS](../../../)


