---
title: "GpxOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.gpx/gpxoptions/
---

**Summary:** Driver-specific options for GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GpxOptions()](#GpxOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| delete_near_points | bool | r/w | 确定是否删除每个几何体中的近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_attribute | string | r/w | 确定哪个 GPX 属性将被导出为路径点、路线点和轨迹点的 'M' 坐标。<br/>            行为与 [GpxOptions.z_attribute](/psd/python-net/aspose.gis.formats.gpx/gpxoptions/) 相同，默认值为 <see langword=\"null\" />。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| nested_attribute_separator | string | r | 用于分隔嵌套属性名称及其索引的字符串。默认值为双下划线 \"__\"。 |
| read_nested_attributes | bool | r/w | 确定 GPX 点（如 'trkpt' 和 'rtept'）是否包含内部属性以及是否应读取。默认值为 <see langword=\"false\" />。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword="false" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword="true" />，则在每个几何体添加到图层时调用 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)。如果验证失败（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) 为 <see langword="false" />），则抛出 [GisException](/psd/python-net/aspose.gis/gisexception/)。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword="false" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_attribute | string | r/w | 确定哪个 GPX 属性将被导出为路径点、路线点和轨迹点的 'Z' 坐标。<br/>            如果 <see langword=\"null\" /> - 则不会有属性导出为 'Z' 坐标。<br/>            默认值为 \"ele\"。<br/>            可取值为所有可以表示为 double 的 GPX XML 属性名称（例如 \"speed\"、\"magvar\"、\"geoidheight\" 等）。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: GpxOptions() {#GpxOptions__1}


```
 GpxOptions() 
```

创建新实例。

