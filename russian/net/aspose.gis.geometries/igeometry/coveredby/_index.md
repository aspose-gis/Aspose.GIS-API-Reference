---
title: CoveredBy
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет покрывается ли эта геометрия указанной геометрией.
type: docs
weight: 140
url: /ru/net/aspose.gis.geometries/igeometry/coveredby/
---
## IGeometry.CoveredBy method

Определяет, покрывается ли эта геометрия указанной геометрией.

```csharp
public bool CoveredBy(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия. |

### Возвращаемое значение

`true`если эта геометрия "пространственно покрыта" другой геометрией.`false`иначе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент`нуль`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation)для преобразования геометрии в одну и ту же пространственную систему отсчета. |

### Примечания

Этот метод проверяет, покрывается ли одна геометрия другой с точки зрения матрицы пересечения DE-9IM.&lt; cr /&gt; Этот метод эквивалентен:

```csharp
other.Covers(this);
```

### Смотрите также

* method [SpatiallyContains](../spatiallycontains)
* method [Covers](../covers)
* interface [IGeometry](../../igeometry)
* пространство имен [Aspose.Gis.Geometries](../../igeometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->