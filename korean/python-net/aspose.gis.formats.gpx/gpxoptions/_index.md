---
title: "GpxOptions 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.formats.gpx/gpxoptions/
---

**Summary:** Driver-specific options for GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GpxOptions()](#GpxOptions__1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 각 기하학에서 닫히지 않은 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)을 닫을지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| create_midpoints | bool | r/w | 각 기하학 세그먼트의 중간에 새로운 점을 추가할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points | bool | r/w | 각 기하학에서 인접한 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| linearization_tolerance | double | r/w | 곡선 지오메트리를 선형화하는 데 사용할 허용오차입니다. |
| m_attribute | string | r/w | 어떤 GPX 속성이 웨이포인트, 라우트 포인트 및 트랙 포인트의 'M' 좌표로 내보내질지를 결정합니다.<br/>            동작은 [GpxOptions.z_attribute](/psd/python-net/aspose.gis.formats.gpx/gpxoptions/)와 동일하며, 기본값은 <see langword=\"null\" />입니다. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| nested_attribute_separator | string | r | 중첩 속성 이름과 해당 인덱스를 구분하는 문자열입니다. 기본값은 이중 밑줄 \"__\"입니다. |
| read_nested_attributes | bool | r/w | GPX 포인트('trkpt' 및 'rtept' 등)에 내부 속성이 포함되어 있는지 및 이를 읽어야 하는지를 결정합니다. 기본값은 <see langword=\"false\" />입니다. |
| simplify_segments | bool | r/w | 각 지오메트리에서 동일한 세그먼트에 있는 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| validate_geometries_on_write | bool | r/w | 지오메트리가 레이어에 추가될 때 검증해야 하는지 여부를 결정합니다.<br/>            <see langword="true" /> 로 설정하면, 레이어에 추가될 때마다 각 지오메트리에 대해 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 호출됩니다. 검증이 실패하면 ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/)이 발생합니다. |
| write_polygons_as_lines | bool | r/w | 폴리곤 또는 멀티폴리곤을 라인스트링으로 변환하는 것이 허용되는지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X 및 Y 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| z_attribute | string | r/w | 웨이포인트, 라우트 포인트 및 트랙 포인트의 'Z' 좌표로 내보내질 GPX 속성을 결정합니다.<br/>            <see langword=\"null\" />인 경우 - 'Z' 좌표로 내보낼 속성이 없습니다.<br/>            기본값은 \"ele\"입니다.<br/>            가능한 값은 double로 표현될 수 있는 모든 GPX XML 속성의 이름이며(예: \"speed\", \"magvar\", \"geoidheight\" 등). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |


### Constructor: GpxOptions() {#GpxOptions__1}


```
 GpxOptions() 
```

새 인스턴스를 생성합니다.

