---
title: SymDifference
second_title: Справочник по Aspose.GIS for .NET API
description: Создает симметричную разность между этой геометрией и указанной геометрией.
type: docs
weight: 380
url: /ru/net/aspose.gis.geometries/geometry/symdifference/
---
## Geometry.SymDifference method

Создает симметричную разность между этой геометрией и указанной геометрией.

```csharp
public IGeometry SymDifference(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия для вычисления симметричной разности. |

### Возвращаемое значение

Геометрия, представляющая симметричную разность этой геометрии и аргумента. Результирующая геометрия содержит набор точек, которые присутствуют в одной из геометрий, но отсутствуют в обеих.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *other*is`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem)геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation)для преобразования геометрии в одну и ту же пространственную систему отсчета. |

### Смотрите также

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* пространство имен [Aspose.Gis.Geometries](../../geometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
