---
title: GetAxis
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 200
url: /net/aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/
---
## SpatialReferenceSystem.GetAxis method

Get [`Axis`](../../axis) that describes dimension.

```csharp
public abstract Axis GetAxis(int dimension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dimension | Int32 | Number of dimension. |

## Return Value

Axis that describes dimension.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *dimension* is less then 0 or greater or equals to [`DimensionsCount`](../dimensionscount) |

### See Also

* class [Axis](../../axis)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->