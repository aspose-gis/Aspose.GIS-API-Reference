---
title: GeoGenerator.ProducePoints
second_title: Aspose.GIS for .NET API Reference
description: GeoGenerator method. Creates an array of points belonging to the specified area
type: docs
weight: 20
url: /net/aspose.gis.geotools/geogenerator/producepoints/
---
## GeoGenerator.ProducePoints method

Creates an array of points belonging to the specified area.

```csharp
public static IEnumerable<IGeometry> ProducePoints(Extent rect, PointGeneratorOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Extent | Specified area (see [`Extent`](../../../aspose.gis/extent/)). |
| options | PointGeneratorOptions | Point creation options (see [`PointGeneratorOptions`](../../pointgeneratoroptions/)). |

### Return Value

Array of points (see enumeration of [`IGeometry`](../../../aspose.gis.geometries/igeometry/)).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Number of points must be grater then one. |
| NullReferenceException | Extent must have a value (not be NULL). |

### See Also

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../../../aspose.gis/extent/)
* class [PointGeneratorOptions](../../pointgeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


