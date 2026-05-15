---
title: "OsmXmlOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.osmxml/osmxmloptions/
---

**Summary:** Driver-specific options for OSM XML format.

**Module:** [aspose.gis.formats.osmxml](/psd/python-net/aspose.gis.formats.osmxml/)

**Full Name:** aspose.gis.formats.osmxml.OsmXmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [OsmXmlOptions()](#OsmXmlOptions__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 确定是否在每个几何体中关闭未闭合的 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)。默认值为 <see langword="false" />。 |
| create_midpoints | bool | r/w | 确定是否在几何体的每个线段中间添加新点。默认值为 <see langword="false" />。 |
| delete_near_points | bool | r/w | 确定是否删除每个几何体中的近点。默认值为 <see langword="false" />。 |
| delete_near_points_distance | double | r/w | 确定 [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| linearization_tolerance | double | r/w | 用于线性化曲线几何体的容差。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 M 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| report_all_nodes | bool | r/w | 将所有节点报告为要素，即使它们没有任何显著的标签。 |
| report_all_ways | bool | r/w | 将所有路径报告为要素，即使它们没有任何显著的标签或没有任何节点。 |
| report_common_attributes | bool | r/w | 报告常见的 OSM 属性：visible、version、changeset、timestamp、user 和 uid。<br/>            常见属性将作为要素属性报告，前缀为 "osm_"，例如 osm_user、osm_timestamp 等。 |
| simplify_segments | bool | r/w | 确定是否删除每个几何体中位于同一线段上的点。默认值为 <see langword="false" />。 |
| simplify_segments_distance | double | r/w | 确定 [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) 的距离。默认值为 <see langword="0" />。 |
| validate_geometries_on_write | bool | r/w | 确定在将几何体添加到图层时是否应进行验证。<br/>            如果设置为 <see langword="true" />，则在每个几何体添加到图层时调用 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)。如果验证失败（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) 为 <see langword="false" />），则抛出 [GisException](/psd/python-net/aspose.gis/gisexception/)。 |
| write_common_attributes | bool | r/w | 写入常见的 OSM 属性：visible、version、changeset、timestamp、user 和 uid。 |
| write_polygons_as_lines | bool | r/w | 确定是否允许将多边形或多多边形转换为线串。默认值为 <see langword="false" />。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 X 和 Y 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | 一个将在 Z 坐标上应用的 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)<br/>            当几何体被添加到 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 或从 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) 读取时。<br/>            默认值为 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)。 |


### Constructor: OsmXmlOptions() {#OsmXmlOptions__1}


```
 OsmXmlOptions() 
```

创建新实例。

