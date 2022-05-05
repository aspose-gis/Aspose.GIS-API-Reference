---
title: ReplacePolygonsByLines
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 190
url: /net/aspose.gis.geometries/geometrycollection/replacepolygonsbylines/
---
## GeometryCollection.ReplacePolygonsByLines method

Gets polygons represented as lines of this geometry.

```csharp
public IGeometryCollection ReplacePolygonsByLines()
```

## Return Value

A geometry, that has no polygon geometries. The following transformation are applied: Polygons are linearized (transformed into LineStrings)MultiPolygons are joined into MultiLineStrings

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException |  |

### See Also

* interface [IGeometryCollection](../../igeometrycollection)
* class [GeometryCollection](../../geometrycollection)
* namespace [Aspose.Gis.Geometries](../../geometrycollection)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->