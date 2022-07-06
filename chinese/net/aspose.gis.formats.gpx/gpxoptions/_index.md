---
title: GpxOptions
second_title: Aspose.GIS for .NET API 参考
description: GPX 格式的驱动程序特定选项
type: docs
weight: 320
url: /zh/net/aspose.gis.formats.gpx/gpxoptions/
---
## GpxOptions class

GPX 格式的驱动程序特定选项。

```csharp
public class GpxOptions : DriverOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GpxOptions](gpxoptions)() | 创建新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | 确定是否关闭每个几何图形中未闭合的LinearRing。默认为`false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | 确定是否在每个几何段的中间添加一个新点。默认为`false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | 确定是否删除每个几何图形中的近点。默认为`false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | 确定[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints)的距离。默认为`0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | 用于线性化曲线几何形状的公差。 |
| [MAttribute](../../aspose.gis.formats.gpx/gpxoptions/mattribute) { get; set; } | 确定哪个 GPX 属性将导出为航点、路线点和跟踪点的“M”坐标。 行为与[`ZAttribute`](./zattribute)相同，默认为`null`。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 M 坐标 当几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |
| [NestedAttributeSeparator](../../aspose.gis.formats.gpx/gpxoptions/nestedattributeseparator) { get; } | 用于分隔嵌套属性名称及其索引的字符串。默认为双下划线“__”。 |
| [ReadNestedAttributes](../../aspose.gis.formats.gpx/gpxoptions/readnestedattributes) { get; set; } | 确定 GPX 点（例如“trkpt”和“rtept”）是否包含内部属性以及是否应读取。默认为`false`。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | 确定是否删除位于每个几何图形中同一段上的点。默认为`false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | 确定[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments)的距离。默认为`0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | 确定在将几何图形添加到图层时是否应对其进行验证。 如果设置为`true`，[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)会为每个 调用几何体添加到图层时，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)is`false`），[`GisException`](../../aspose.gis/gisexception)被抛出。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认为`false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 X 和 Y 坐标 当几何图形添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |
| [ZAttribute](../../aspose.gis.formats.gpx/gpxoptions/zattribute) { get; set; } | 确定哪个 GPX 属性将导出为航点、路线点和跟踪点的“Z”坐标。 如果`null`- 没有属性将导出为“Z”坐标。 默认为“ele”。 可能的值是可以表示为双精度的所有 GPX XML 属性的名称（例如“speed”、“magvar”、“geoidheight”等） |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 Z 坐标 当几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |

### 也可以看看

* class [DriverOptions](../../aspose.gis/driveroptions)
* 命名空间 [Aspose.Gis.Formats.Gpx](../../aspose.gis.formats.gpx)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->