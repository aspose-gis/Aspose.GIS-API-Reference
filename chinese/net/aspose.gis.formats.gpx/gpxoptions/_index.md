---
title: "类 GpxOptions"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.Gpx.GpxOptions 类。针对 GPX 格式的驱动特定选项"
type: docs
weight: 1980
url: /zh/net/aspose.gis.formats.gpx/gpxoptions/
---
## GpxOptions class

GPX 格式的特定驱动程序选项。

```csharp
public class GpxOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GpxOptions](gpxoptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MAttribute](../../aspose.gis.formats.gpx/gpxoptions/mattribute/) { get; set; } | 确定哪个 GPX 属性将导出为航点、路线点和轨迹点的 'M' 坐标。行为与 [`ZAttribute`](./zattribute/) 相同，默认值为 `null`。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [NestedAttributeSeparator](../../aspose.gis.formats.gpx/gpxoptions/nestedattributeseparator/) { get; } | 用于分隔嵌套属性名称及其索引的字符串。默认值为双下划线 "__"。 |
| [ReadNestedAttributes](../../aspose.gis.formats.gpx/gpxoptions/readnestedattributes/) { get; set; } | 确定 GPX 点（如 'trkpt' 和 'rtept'）是否包含内部属性以及是否应读取。默认值为 `false`。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否删除每个几何体中位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZAttribute](../../aspose.gis.formats.gpx/gpxoptions/zattribute/) { get; set; } | 确定哪个 GPX 属性将导出为航点、路线点和轨迹点的 'Z' 坐标。如果为 `null`，则不会有属性导出为 'Z' 坐标。默认值为 "ele"。可能的取值是所有可以表示为 double 的 GPX XML 属性名称（例如 "speed"、"magvar"、"geoidheight" 等）。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Gpx](../../aspose.gis.formats.gpx/)
* assembly [Aspose.GIS](../../)


