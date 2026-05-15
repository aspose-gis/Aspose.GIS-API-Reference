---
title: "类 CsvOptions"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.Csv.CsvOptions 类。针对 CSV 格式的驱动程序特定选项"
type: docs
weight: 1700
url: /zh/net/aspose.gis.formats.csv/csvoptions/
---
## CsvOptions class

针对 CSV 格式的驱动程序特定选项。

```csharp
public class CsvOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CsvOptions](csvoptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [ColumnM](../../aspose.gis.formats.csv/csvoptions/columnm/) { get; set; } | 获取或设置包含 M 坐标值的列名。默认值为 `null`。 |
| [ColumnWkt](../../aspose.gis.formats.csv/csvoptions/columnwkt/) { get; set; } | 获取或设置用于表示几何体的 Well-Known Text 所在列的名称。默认值为 `null`。 |
| [ColumnX](../../aspose.gis.formats.csv/csvoptions/columnx/) { get; set; } | 获取或设置包含 X 坐标值的列名。默认值为 `null`。 |
| [ColumnY](../../aspose.gis.formats.csv/csvoptions/columny/) { get; set; } | 获取或设置包含 Y 坐标值的列名。默认值为 `null`。 |
| [ColumnZ](../../aspose.gis.formats.csv/csvoptions/columnz/) { get; set; } | 获取或设置包含 Z 坐标值的列名。默认值为 `null`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [Delimiter](../../aspose.gis.formats.csv/csvoptions/delimiter/) { get; set; } | 获取或设置用于分隔值的分隔符字符。默认值为 ','。 |
| [DoubleQuoteEscape](../../aspose.gis.formats.csv/csvoptions/doublequoteescape/) { get; set; } | 获取或设置用于转义双引号的字符。默认值为 '\"'。 |
| [HasAttributeNames](../../aspose.gis.formats.csv/csvoptions/hasattributenames/) { get; set; } | 确定是否存在包含属性名称的标题行。默认值为 `true`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否删除每个几何体中位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [StartLineNumber](../../aspose.gis.formats.csv/csvoptions/startlinenumber/) { get; set; } | 获取或设置读取数据时第一行的零基行号。默认值为 0。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Csv](../../aspose.gis.formats.csv/)
* assembly [Aspose.GIS](../../)


