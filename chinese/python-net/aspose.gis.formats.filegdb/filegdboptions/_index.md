---
title: "FileGdbOptions 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | 用于新图层的坐标精度网格。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| delete_near_points | bool | r/w | 确定是否在每个几何体中删除相近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points] 的距离。默认值为 <see langword=\"0\" />。 |
| ensure_valid_coordinates_range | bool | r/w | 坐标是否应在有效范围内。 |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | 图层的期望几何类型。如果设置了此选项，则仅允许添加此类型的几何体。 |
| geometry_field_name | string | r/w | 几何字段的名称。 |
| has_m | bool | r/w | 图层的几何体是否可以具有 'm' 坐标。默认值为 true。 |
| has_z | bool | r/w | 图层的几何体是否可以具有 'z' 坐标。默认值为 true。 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| m_tolerance | Nullable<double> | r/w | M 捕捉容差。 |
| object_id_field_name | string | r/w | 对象 ID 字段的名称。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword=\"false\" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments] 的距离。默认值为 <see langword=\"0\" />。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword=\"true\" />，则在每个几何体添加到图层时调用 [Geometry.is_valid]。如果验证失败（[Geometry.is_valid] 为 <see langword=\"false\" />），则抛出 [GisException]。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword=\"false\" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| xy_tolerance | Nullable<double> | r/w | X 和 Y 捕捉容差。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_tolerance | Nullable<double> | r/w | Z 捕捉容差。 |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

创建新实例。

