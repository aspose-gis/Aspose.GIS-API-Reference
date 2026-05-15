---
title: "类 GmlOptions"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.Gml.GmlOptions 类。GML 格式的驱动特定选项"
type: docs
weight: 1960
url: /zh/net/aspose.gis.formats.gml/gmloptions/
---
## GmlOptions class

GML 格式的驱动程序特定选项。

```csharp
public class GmlOptions : DriverOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GmlOptions](gmloptions/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 确定是否在每个几何体中关闭未闭合的 LinearRing。默认值为 `false`。 |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | 确定是否在几何体的每个线段中间添加新点。默认值为 `false`。 |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 确定是否在每个几何体中删除相近点。默认值为 `false`。 |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | 确定 [`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) 的距离。默认值为 `0`。 |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 用于线性化曲线几何体的容差。 |
| [LoadSchemasFromInternet](../../aspose.gis.formats.gml/gmloptions/loadschemasfrominternet/) { get; set; } | 确定是否允许 Aspose.GIS 从互联网加载 XML 模式。如果设置为 `false`，则不会加载以非 'file://' 开头的绝对 URI 的模式。默认值为 `false`。 |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 M 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [NestedPropertiesSeparator](../../aspose.gis.formats.gml/gmloptions/nestedpropertiesseparator/) { get; set; } | 获取或设置用于分隔嵌套属性组件的字符串。默认是 "_"。 |
| [RestoreSchema](../../aspose.gis.formats.gml/gmloptions/restoreschema/) { get; set; } | 确定是否允许 Aspose.GIS 在缺少或无法加载 XML 模式的 Gml 文件中解析属性。如果设置为 `true`，Aspose.GIS 读取器不需要 XML 模式的存在。默认值为 `false`。 |
| [SchemaLocation](../../aspose.gis.formats.gml/gmloptions/schemalocation/) { get; set; } | 以空格分隔的 URI 对列表。每对中的第一个 URI 是命名空间的 URI，第二个 URI 是该命名空间的 XML 模式路径。如果设置为 `null`，[`GmlDriver`](../gmldriver/) 将尝试从文档根元素读取 schemaLocation。默认值为 `null`。 |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 确定是否删除每个几何体中位于同一线段上的点。默认值为 `false`。 |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | 确定 [`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) 的距离。默认值为 `0`。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | 确定在将几何体添加到图层时是否应进行验证。如果设置为 `true`，则在几何体添加到图层时会调用每个几何体的 [`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)，如果验证失败（[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则抛出 [`GisException`](../../aspose.gis/gisexception/)。 |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | 确定是否允许将多边形或多多边形转换为线串。默认值为 `false`。 |
| [XmlResolver](../../aspose.gis.formats.gml/gmloptions/xmlresolver/) { get; set; } | 用于解析外部资源的 [`XmlResolver`](./xmlresolver/)。默认是 XmlUrlResolver。 |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 X 和 Y 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | 一个将在几何体添加到 [`VectorLayer`](../../aspose.gis/vectorlayer/) 或从 [`VectorLayer`](../../aspose.gis/vectorlayer/) 读取时应用于 Z 坐标的 [`PrecisionModel`](../../aspose.gis/precisionmodel/)。默认值为 [`Exact`](../../aspose.gis/precisionmodel/exact/)。 |

### 另见

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namespace [Aspose.Gis.Formats.Gml](../../aspose.gis.formats.gml/)
* assembly [Aspose.GIS](../../)


