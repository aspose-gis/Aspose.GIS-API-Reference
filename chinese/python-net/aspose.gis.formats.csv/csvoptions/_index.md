---
title: "CsvOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| column_m | string | r/w | 获取或设置包含 M 坐标值的列名。<br/>            默认值为 <see langword=\"null\" />。 |
| column_wkt | string | r/w | 获取或设置包含用于表示几何的 Well-Known Text 的列名。<br/>            默认值为 <see langword=\"null\" />。 |
| column_x | string | r/w | 获取或设置包含 X 坐标值的列名。<br/>            默认值为 <see langword=\"null\" />。 |
| column_y | string | r/w | 获取或设置包含 Y 坐标值的列名。<br/>            默认值为 <see langword=\"null\" />。 |
| column_z | string | r/w | 获取或设置包含 Z 坐标值的列名。<br/>            默认值为 <see langword=\"null\" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| delete_near_points | bool | r/w | 确定是否在每个几何体中删除相近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points] 的距离。默认值为 <see langword=\"0\" />。 |
| 分隔符 | 字符 | r/w | 获取或设置用于分隔值的分隔符字符。<br/>            默认值为 ','. |
| double_quote_escape | 字符 | r/w | 获取或设置用于转义双引号的字符。<br/>            默认值为 '\"'。 |
| has_attribute_names | bool | r/w | 确定是否存在包含属性名称的标题行。<br/>            默认值为 <see langword=\"true\" />。 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword=\"false\" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments] 的距离。默认值为 <see langword=\"0\" />。 |
| start_line_number | 整数 | r/w | 获取或设置一个基于零的行号，该行将在读取数据时首先出现。<br/>            默认值为 0。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword=\"true\" />，则在每个几何体添加到图层时调用 [Geometry.is_valid]。如果验证失败（[Geometry.is_valid] 为 <see langword=\"false\" />），则抛出 [GisException]。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword=\"false\" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

创建新实例。

