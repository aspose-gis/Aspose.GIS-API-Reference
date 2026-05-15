---
title: "类 OsmXmlOptions"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.OsmXml.OsmXmlOptions 类。针对 OSM XML 格式的驱动特定选项"
type: docs
weight: 2270
url: /zh/net/aspose.gis.formats.osmxml/osmxmloptions/
---
## OsmXmlOptions class

OSM XML 格式的特定驱动程序选项。

```csharp
public class OsmXmlOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OsmXmlOptions](osmxmloptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ReportAllNodes](../../aspose.gis.formats.osmxml/osmxmloptions/reportallnodes/) { get; set; } | 将所有节点报告为要素，即使它们没有任何显著标签。 |
| [ReportAllWays](../../aspose.gis.formats.osmxml/osmxmloptions/reportallways/) { get; set; } | 将所有路径报告为要素，即使它们没有任何显著标签或没有任何节点。 |
| [ReportCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/reportcommonattributes/) { get; set; } | 报告常见的 OSM 属性：visible、version、changeset、timestamp、user 和 uid。常见属性将作为要素属性报告，带有 "osm_" 前缀，例如 osm_user、osm_timestamp 等。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否删除每个几何体中位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WriteCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/writecommonattributes/) { get; set; } | 写入常见的 OSM 属性：visible、version、changeset、timestamp、user 和 uid。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml/)
* assembly [Aspose.GIS](../../)


