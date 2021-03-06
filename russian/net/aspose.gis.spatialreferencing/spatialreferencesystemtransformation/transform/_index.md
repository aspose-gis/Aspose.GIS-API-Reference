---
title: Transform
second_title: Справочник по Aspose.GIS for .NET API
description: Преобразует геометрию из исходной системы пространственной привязки в целевую систему пространственной привязки.
type: docs
weight: 40
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/transform/
---
## SpatialReferenceSystemTransformation.Transform method

Преобразует геометрию из исходной системы пространственной привязки в целевую систему пространственной привязки.

```csharp
public Geometry Transform(IGeometry geometry)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| geometry | IGeometry | Геометрия для преобразования. |

### Возвращаемое значение

Новая геометрия в целевой системе пространственной привязки.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Геометрия`null`. |
| ArgumentException | Geometries[`SpatialReferenceSystem`](../../../aspose.gis.geometries/igeometry/spatialreferencesystem)is not`null`и не эквивалентен [`Source`](../source) |
| [TransformationException](../../transformationexception) | Преобразование не выполнено. |

### Смотрите также

* class [Geometry](../../../aspose.gis.geometries/geometry)
* interface [IGeometry](../../../aspose.gis.geometries/igeometry)
* class [SpatialReferenceSystemTransformation](../../spatialreferencesystemtransformation)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystemtransformation)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
