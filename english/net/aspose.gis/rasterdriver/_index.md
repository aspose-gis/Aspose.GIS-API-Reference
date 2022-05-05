---
title: RasterDriver
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 1320
url: /net/aspose.gis/rasterdriver/
---
## RasterDriver class

A driver for a specific raster based format.

```csharp
public abstract class RasterDriver : Driver
```

## Properties

| Name | Description |
| --- | --- |
| abstract [CanOpenLayers](canopenlayers) { get; } | Gets a value indicating whether this driver can open raster layers. |

## Methods

| Name | Description |
| --- | --- |
| [OpenLayer](openlayer)(AbstractPath) | Opens the layer for reading. |
| [OpenLayer](openlayer)(string) | Opens the layer for reading. |
| abstract [OpenLayer](openlayer)(AbstractPath, RasterDriverOptions) | Opens the layer for reading. |
| [OpenLayer](openlayer)(string, RasterDriverOptions) | Opens the layer for reading. |

### See Also

* class [Driver](../driver)
* namespace [Aspose.Gis](../../aspose.gis)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->