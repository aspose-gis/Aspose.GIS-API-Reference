---
title: "类 GeoJsonSeqOptions"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Formats.GeoJsonSeq.GeoJsonSeqOptions 类。针对 GeoJsonSeq 的驱动程序特定选项"
type: docs
weight: 1920
url: /zh/net/aspose.gis.formats.geojsonseq/geojsonseqoptions/
---
## GeoJsonSeqOptions class

GeoJsonSeq 的驱动程序特定选项。

```csharp
public class GeoJsonSeqOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GeoJsonSeqOptions](geojsonseqoptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArrayAsString](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/arrayasstring/) { get; set; } | 是否将 JSON 字符串、整数或实数数组暴露为字符串。 |
| [AttributesSkip](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/attributesskip/) { get; set; } | 控制属性的翻译：是 - 跳过所有属性 |
| [AutoId](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/autoid/) { get; set; } | 自动生成 ID |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DateAsString](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/dateasstring/) { get; set; } | 是否将 JSon 日期/时间/日期时间 以字符串形式公开。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [GeometryAsCollection](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/geometryascollection/) { get; set; } | 控制几何体的转换：是 - 使用 GeometryCollection 类型包装几何体 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [NestedPropertiesSeparator](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/nestedpropertiesseparator/) { get; set; } | 获取或设置用于分隔嵌套属性组件的字符串。默认是 "_"。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否在每个几何体中删除位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [WriteUnsetAttribute](../../aspose.gis.formats.geojsonseq/geojsonseqoptions/writeunsetattribute/) { get; set; } | 是否通过添加 'null' 值来写入未设置的属性 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.GeoJsonSeq](../../aspose.gis.formats.geojsonseq/)
* assembly [Aspose.GIS](../../)


