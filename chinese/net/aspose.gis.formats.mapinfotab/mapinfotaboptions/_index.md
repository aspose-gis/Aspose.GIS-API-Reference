---
title: "Class MapInfoTabOptions"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.MapInfoTab.MapInfoTabOptions 类。MapInfo Tab 格式的驱动特定选项"
type: docs
weight: 2250
url: /zh/net/aspose.gis.formats.mapinfotab/mapinfotaboptions/
---
## MapInfoTabOptions class

针对 MapInfo Tab 格式的驱动程序特定选项。

```csharp
public class MapInfoTabOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MapInfoTabOptions](mapinfotaboptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BlockSize](../../aspose.gis.formats.mapinfotab/mapinfotaboptions/blocksize/) { get; set; } | ‘*.map’ 文件的块大小（512 的倍数）。默认 16384。有效值范围：512 到 32256。 |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [IsIgnoreWrongData](../../aspose.gis.formats.mapinfotab/mapinfotaboptions/isignorewrongdata/) { get; set; } | 确定在处理错误数据时是抛出异常还是设置默认值 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否删除每个几何体中位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [TextStringAttribute](../../aspose.gis.formats.mapinfotab/mapinfotaboptions/textstringattribute/) { get; set; } | 指定表示 'Text' 图形对象文本的属性名称。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.MapInfoTab](../../aspose.gis.formats.mapinfotab/)
* assembly [Aspose.GIS](../../)


