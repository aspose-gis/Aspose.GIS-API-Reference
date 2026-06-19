---
title: "类 DatabaseDriverOptions"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.DatabaseDriverOptions 类。DatabaseDriver 的选项"
type: docs
weight: 1420
url: /zh/net/aspose.gis/databasedriveroptions/
---
## DatabaseDriverOptions class

针对 [`DatabaseDriver`](../databasedriver/) 的选项。

```csharp
public abstract class DatabaseDriverOptions : DriverOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 当几何对象添加到 [`VectorLayer`](../vectorlayer/) 或从 [`VectorLayer`](../vectorlayer/) 读取时，将应用于 M 坐标的 [`PrecisionModel`](../precisionmodel/)。默认值为 [`Exact`](../precisionmodel/exact/)。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否在每个几何体中删除位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [SpatialReferenceSystemMode](../../aspose.gis/databasedriveroptions/spatialreferencesystemmode/) { get; set; } | 确定在将未知几何体的数据库 SRS 添加到图层时应如何处理。默认值为 ThrowException。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何对象添加到图层时是否应进行验证。如果设置为 `true`，在几何对象添加到图层时会调用 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)。如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 当几何对象添加到 [`VectorLayer`](../vectorlayer/) 或从 [`VectorLayer`](../vectorlayer/) 读取时，将应用于 X 和 Y 坐标的 [`PrecisionModel`](../precisionmodel/)。默认值为 [`Exact`](../precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 当几何对象添加到 [`VectorLayer`](../vectorlayer/) 或从 [`VectorLayer`](../vectorlayer/) 读取时，将应用于 Z 坐标的 [`PrecisionModel`](../precisionmodel/)。默认值为 [`Exact`](../precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../driveroptions/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


