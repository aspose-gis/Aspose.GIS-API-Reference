---
title: WarpOptions.Height
second_title: Aspose.GIS for .NET API Reference
description: WarpOptions property. Specifies output raster height in pixels and columns. If the value is set to 0 the height is automatically computed. The default value is 0
type: docs
weight: 50
url: /net/aspose.gis.raster/warpoptions/height/
---
## WarpOptions.Height property

Specifies output raster height in pixels and columns. If the value is set to 0, the height is automatically computed. The default value is "0".

```csharp
public int Height { get; set; }
```

## Remarks

If the height is set to 0, the value will be taken from the original height or computed from [`CellHeight`](../cellheight/). Note that `Height` cannot be used with [`CellHeight`](../cellheight/).

### See Also

* class [WarpOptions](../)
* namespace [Aspose.Gis.Raster](../../warpoptions/)
* assembly [Aspose.GIS](../../../)


