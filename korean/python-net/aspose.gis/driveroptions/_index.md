---
title: "DriverOptions 클래스"
type: docs
weight: 630
url: /ko/python-net/aspose.gis/driveroptions/
---

**Summary:** Options for a [Driver](/psd/python-net/aspose.gis/driver/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 각 기하학에서 닫히지 않은 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)을 닫을지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| create_midpoints | bool | r/w | 각 기하학 세그먼트의 중간에 새로운 점을 추가할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points | bool | r/w | 각 기하학에서 인접한 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| linearization_tolerance | double | r/w | 곡선 지오메트리를 선형화하는 데 사용할 허용오차입니다. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| simplify_segments | bool | r/w | 각 지오메트리에서 동일한 세그먼트에 있는 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| validate_geometries_on_write | bool | r/w | 지오메트리가 레이어에 추가될 때 검증해야 하는지 여부를 결정합니다.<br/>            <see langword="true" /> 로 설정하면, 레이어에 추가될 때마다 각 지오메트리에 대해 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 호출됩니다. 검증이 실패하면 ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/)이 발생합니다. |
| write_polygons_as_lines | bool | r/w | 폴리곤 또는 멀티폴리곤을 라인스트링으로 변환하는 것이 허용되는지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X 및 Y 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |


