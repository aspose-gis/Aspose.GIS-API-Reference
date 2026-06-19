---
title: "FileGdbCoordinatePrecisionGrid.XYScale"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileGdbCoordinatePrecisionGrid 属性。获取或设置 X 和 Y 坐标的比例。如果设置为 null，则使用默认值"
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xyscale/
---
## FileGdbCoordinatePrecisionGrid.XYScale property

获取或设置 X 和 Y 坐标的比例。如果设置为 `null`，默认值将被使用。

```csharp
public double? XYScale { get; set; }
```

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 参数不是正数。 |

## 备注

默认值为 `1e9`，适用于具有地理 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) 的 [`VectorLayer`](../../../aspose.gis/vectorlayer/)，以及 `XYScale = 1 / XYTolerance * 10`，适用于具有投影 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) 的 [`VectorLayer`](../../../aspose.gis/vectorlayer/)。

### 另见

* class [FileGdbCoordinatePrecisionGrid](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbcoordinateprecisiongrid/)
* assembly [Aspose.GIS](../../../)


