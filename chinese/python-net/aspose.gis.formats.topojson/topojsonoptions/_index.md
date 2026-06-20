---
title: "TopoJsonOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.topojson/topojsonoptions/
---

**Summary:** Driver-specific options for TopoJSON format.

**Module:** [aspose.gis.formats.topojson](/psd/python-net/aspose.gis.formats.topojson/)

**Full Name:** aspose.gis.formats.topojson.TopoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TopoJsonOptions()](#TopoJsonOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| default_object_name | string | r/w | 默认情况下放置要素的对象名称。 |
| delete_near_points | bool | r/w | 确定是否在每个几何体中删除相近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points] 的距离。默认值为 <see langword=\"0\" />。 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| nested_properties_separator | string | r/w | 获取或设置用于分隔嵌套属性组件的字符串。<br/>            默认是 \"_\"。 |
| object_name_attribute | string | r/w | 反映包含要素的对象名称的属性名称。 |
| quantization_number | Nullable<int> | r/w | 指定用于量化坐标并在输出 TopoJSON 中对弧进行差分编码的量化数字。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword=\"false\" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments] 的距离。默认值为 <see langword=\"0\" />。 |
| transform | [TopoJsonTransform](/psd/python-net/aspose.gis.formats.topojson/topojsontransform) | r/w | 指定用于量化坐标并在输出 TopoJSON 中对弧进行差分编码的变换对象。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword=\"true\" />，则在每个几何体添加到图层时调用 [Geometry.is_valid]。如果验证失败（[Geometry.is_valid] 为 <see langword=\"false\" />），则抛出 [GisException]。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword=\"false\" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: TopoJsonOptions() {#TopoJsonOptions__1}


```
 TopoJsonOptions() 
```

创建新实例。

