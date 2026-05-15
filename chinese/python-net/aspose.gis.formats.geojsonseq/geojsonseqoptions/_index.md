---
title: "GeoJsonSeqOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.geojsonseq/geojsonseqoptions/
---

**Summary:** Driver-specific options for GeoJsonSeq.

**Module:** [aspose.gis.formats.geojsonseq](/psd/python-net/aspose.gis.formats.geojsonseq/)

**Full Name:** aspose.gis.formats.geojsonseq.GeoJsonSeqOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GeoJsonSeqOptions()](#GeoJsonSeqOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | 是否将 JSON 字符串、整数或实数数组公开为字符串。 |
| attributes_skip | bool | r/w | 控制属性的翻译：yes - 跳过所有属性 |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | 自动生成 ID |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| date_as_string | bool | r/w | 是否将 JSON 日期/时间/日期时间公开为字符串。 |
| delete_near_points | bool | r/w | 确定是否删除每个几何体中的近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| geometry_as_collection | bool | r/w | 控制几何体的转换：是 - 将几何体包装为 GeometryCollection 类型 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| nested_properties_separator | string | r/w | 获取或设置用于分隔嵌套属性组件的字符串。<br/>            默认是 "_"。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword="false" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword="true" />，则在每个几何体添加到图层时调用 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)。如果验证失败（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) 为 <see langword="false" />），则抛出 [GisException](/psd/python-net/aspose.gis/gisexception/)。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword="false" />。 |
| write_unset_attribute | bool | r/w | 是否通过添加 'null' 值来写入未设置的属性 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: GeoJsonSeqOptions() {#GeoJsonSeqOptions__1}


```
 GeoJsonSeqOptions() 
```

创建新实例。

