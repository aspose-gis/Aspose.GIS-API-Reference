---
title: Map.Extent
second_title: Aspose.GIS for .NET API Reference
description: Map property. Specifies bounds of map to render. If set to null extent is calculated during rendering to include all geometries in all layers
type: docs
weight: 40
url: /net/aspose.gis.rendering/map/extent/
---
## Map.Extent property

Specifies bounds of map to render. If set to `null`, extent is calculated during rendering to include all geometries in all layers.

```csharp
public Extent Extent { get; set; }
```

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | [`IsValid`](../../../aspose.gis/extent/isvalid/) is `false`.[`Width`](../../../aspose.gis/extent/width/) is less or equal to zero.[`Height`](../../../aspose.gis/extent/height/) is less or equal to zero.[`SpatialReferenceSystem`](../../../aspose.gis/extent/spatialreferencesystem/) is `null`. |

## Remarks

If spatial reference system of the extent is not equal to spatial reference system of the map, extent is being transformed to the target spatial reference system during rendering.

### See Also

* class [Extent](../../../aspose.gis/extent/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


