---
title: "GdalOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.gdal/gdaloptions/
---

**Summary:** Driver-specific options for GDAL format.

**Module:** [aspose.gis.formats.gdal](/psd/python-net/aspose.gis.formats.gdal/)

**Full Name:** aspose.gis.formats.gdal.GdalOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdalOptions(temp_directory)](#GdalOptions_temp_directory_1) | 创建一个新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| delete_near_points | bool | r/w | 确定是否在每个几何体中删除相近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points] 的距离。默认值为 <see langword=\"0\" />。 |
| file_name | string | r/w | 要启动的应用程序名称 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| path_to_temp_file | string | r | 临时文件的路径。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword=\"false\" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments] 的距离。默认值为 <see langword=\"0\" />。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword=\"true\" />，则在每个几何体添加到图层时调用 [Geometry.is_valid]。如果验证失败（[Geometry.is_valid] 为 <see langword=\"false\" />），则抛出 [GisException]。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword=\"false\" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: GdalOptions(temp_directory) {#GdalOptions_temp_directory_1}


```
 GdalOptions(temp_directory) 
```

创建一个新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| temp_directory | string | 临时文件的路径。默认情况下为用户的临时文件夹。 |

