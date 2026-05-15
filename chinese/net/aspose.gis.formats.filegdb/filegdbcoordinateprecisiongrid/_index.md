---
title: "类 FileGdbCoordinatePrecisionGrid"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.FileGdb.FileGdbCoordinatePrecisionGrid 类。FileGDB 图层中的坐标精度网格"
type: docs
weight: 1840
url: /zh/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---
## FileGdbCoordinatePrecisionGrid class

FileGDB 图层内的坐标精度网格。

```csharp
public sealed class FileGdbCoordinatePrecisionGrid
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileGdbCoordinatePrecisionGrid](filegdbcoordinateprecisiongrid/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [MOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/morigin/) { get; set; } | 获取或设置 M 坐标的原点。如果设置为 `null`，则使用默认值。 |
| [MScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/mscale/) { get; set; } | 获取或设置 M 坐标的比例。如果设置为 `null`，则使用默认值。 |
| [XOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xorigin/) { get; set; } | 获取或设置 X 坐标的原点。如果设置为 `null`，则使用默认值。 |
| [XYScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xyscale/) { get; set; } | 获取或设置 X 和 Y 坐标的比例。如果设置为 `null`，则使用默认值。 |
| [YOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/yorigin/) { get; set; } | 获取或设置 Y 坐标的原点。如果设置为 `null`，则使用默认值。 |
| [ZOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/zorigin/) { get; set; } | 获取或设置 Z 坐标的原点。如果设置为 `null`，则使用默认值。 |
| [ZScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/zscale/) { get; set; } | 获取或设置 Z 坐标的比例。如果设置为 `null`，则使用默认值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFromRectangle](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/createfromrectangle/)(IPoint, IPoint) | 创建新的 `FileGdbCoordinatePrecisionGrid`，使矩形内的所有值都可表示。 |

## 备注

坐标精度网格定义了 FileGDB 图层中坐标的有效域和分辨率。原点定义了空间中坐标精度网格的路径。比例定义了分辨率（比例越大，写入的值越精确）。精度网格指定坐标值的有效范围：

```csharp
XMin = XOrigin
YMin = YOrigin
ZMin = ZOrigin
MMin = MOrigin
XMax = XOrigin + 9e+15 / XYScale
YMax = YOrigin + 9e+15 / XYScale
ZMax = ZOrigin + 9e+15 / ZScale
MMax = MOrigin + 9e+15 / MScale
```

每个 [`VectorLayer`](../../aspose.gis/vectorlayer/) 中的坐标必须在此范围内。超出范围的坐标可能导致后续读取错误，并会被 ArcGIS 错误处理。如果您未指定任何属性（保持为 `null`），将使用默认值。默认值取决于 [`VectorLayer`](../../aspose.gis/vectorlayer/) 的 [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/)。对于地理 [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) 的默认值如下：

```csharp
XOrigin = -400
YOrigin = -400
ZOrigin = -1e5
MOrigin = -1e5
XYScale = 1e9
ZScale  = 1 / ZTolerance * 10
MScale  = 1 / MTolerance * 10
```

对于投影的 [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) 默认值如下：

```csharp
XOrigin = -2147483647
YOrigin = -2147483647
ZOrigin = -1e5
MOrigin = -1e5
XYScale = 1 / XYTolerance * 10
ZScale  = 1 / ZTolerance  * 10
MScale  = 1 / MTolerance  * 10
```

其中 `XYTolerance`、`ZTolerance` 和 `MTolerance` 的值来自 [`FileGdbOptions`](../filegdboptions/)。

### 另见

* namespace [Aspose.Gis.Formats.FileGdb](../../aspose.gis.formats.filegdb/)
* assembly [Aspose.GIS](../../)


