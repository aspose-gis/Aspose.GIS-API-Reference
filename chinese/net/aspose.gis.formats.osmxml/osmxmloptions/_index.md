---
title: OsmXmlOptions
second_title: Aspose.GIS for .NET API 参考
description: OSM XML 格式的驱动程序特定选项
type: docs
weight: 560
url: /zh/net/aspose.gis.formats.osmxml/osmxmloptions/
---
## OsmXmlOptions class

OSM XML 格式的驱动程序特定选项。

```csharp
public class OsmXmlOptions : DriverOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [OsmXmlOptions](osmxmloptions)() | 创建新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | 确定是否关闭每个几何图形中未闭合的LinearRing。默认为`false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | 确定是否在每个几何段的中间添加一个新点。默认为`false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | 确定是否删除每个几何图形中的近点。默认为`false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | 确定[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints)的距离。默认为`0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | 用于线性化曲线几何形状的公差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 M 坐标 当几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |
| [ReportAllNodes](../../aspose.gis.formats.osmxml/osmxmloptions/reportallnodes) { get; set; } | 将所有节点报告为特征，即使它们没有任何重要标签。 |
| [ReportAllWays](../../aspose.gis.formats.osmxml/osmxmloptions/reportallways) { get; set; } | 将所有方式报告为特征，即使它们没有任何重要标签或没有任何节点。 |
| [ReportCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/reportcommonattributes) { get; set; } | 报告常见的 OSM 属性:可见、版本、变更集、时间戳、用户和 uid。 通用属性将被报告为带有“osm_”前缀的特征属性，例如osm_user、osm_timestamp等。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | 确定是否删除位于每个几何图形中同一段上的点。默认为`false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | 确定[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments)的距离。默认为`0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | 确定在将几何图形添加到图层时是否应对其进行验证。 如果设置为`true`，[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)会为每个 调用几何体添加到图层时，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)is`false`），[`GisException`](../../aspose.gis/gisexception)被抛出。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认为`false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 X 和 Y 坐标 当几何图形添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)将应用于 Z 坐标 当几何添加到[`VectorLayer`](../../aspose.gis/vectorlayer)或从[`VectorLayer`](../../aspose.gis/vectorlayer)读取它们时。 默认值为[`Exact`](../../aspose.gis/precisionmodel/exact)。 |

### 也可以看看

* class [DriverOptions](../../aspose.gis/driveroptions)
* 命名空间 [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->