---
title: ReplacePolygonsByLines
second_title: Справочник по Aspose.GIS for .NET API
description: Получает многоугольники представленные в виде линий этой геометрии.
type: docs
weight: 40
url: /ru/net/aspose.gis.geometries/igeometrycollection/replacepolygonsbylines/
---
## IGeometryCollection.ReplacePolygonsByLines method

Получает многоугольники, представленные в виде линий этой геометрии.

```csharp
public IGeometryCollection ReplacePolygonsByLines()
```

### Возвращаемое значение

Геометрия, не имеющая полигональной геометрии. Применяются следующие преобразования: &lt;ul&gt;&lt;li&gt;Polygonлинеаризованы (преобразованы вLineStrings)&lt;/li&gt;&lt;li&gt;MultiPolygons являются присоединился кMultiLineStrings&lt;/li&gt;&lt;/ul&gt;

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException |  |

### Смотрите также

* interface [IGeometryCollection](../../igeometrycollection)
* пространство имен [Aspose.Gis.Geometries](../../igeometrycollection)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->