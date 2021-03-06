---
title: UseSpatialIndex
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 170
url: /net/aspose.gis/vectorlayer/usespatialindex/
---
## VectorLayer.UseSpatialIndex method (1 of 2)

Loads spatial index to speed up filtering by attributes value in filter methods like [`WhereIntersects`](../../featuressequence/whereintersects) and [`NearestTo`](../nearestto). If index does not exist creates it first. Use *forceRebuild* to force index recreation.

```csharp
public void UseSpatialIndex(string indexPath, bool forceRebuild = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| indexPath | String | Path to the index file. |
| forceRebuild | Boolean | Whether to recreate index even if it already exists. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Path is `null`. |
| IOException | An I/O error occurred. |
| InvalidOperationException | Spatial index is already loaded for this layer. |
| [GisException](../../gisexception) | File exists and it is not a spatial index file created by Aspose.GIS. |

### See Also

* class [VectorLayer](../../vectorlayer)
* namespace [Aspose.Gis](../../vectorlayer)
* assembly [Aspose.GIS](../../../)

---

## VectorLayer.UseSpatialIndex method (2 of 2)

Loads spatial index to speed up filtering by attributes value in filter methods like [`WhereIntersects`](../../featuressequence/whereintersects) and [`NearestTo`](../nearestto). If index does not exist creates it first. Use *forceRebuild* to force index recreation.

```csharp
public virtual void UseSpatialIndex(AbstractPath indexPath, bool forceRebuild = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| indexPath | AbstractPath | Path to the index file. |
| forceRebuild | Boolean | Whether to recreate index even if it already exists. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Path is `null`. |
| IOException | An I/O error occurred. |
| InvalidOperationException | Spatial index is already loaded for this layer. |
| [GisException](../../gisexception) | File exists and it is not a spatial index file created by Aspose.GIS. |

### See Also

* class [AbstractPath](../../abstractpath)
* class [VectorLayer](../../vectorlayer)
* namespace [Aspose.Gis](../../vectorlayer)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
