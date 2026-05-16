---
title: "CsvOptions 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 각 기하학에서 닫히지 않은 [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/)을 닫을지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| column_m | string | r/w | M 좌표 값을 포함하는 열의 이름을 가져오거나 설정합니다.<br/>            기본값은 <see langword=\"null\" />. |
| column_wkt | string | r/w | 지오메트리를 나타내는 Well-Known Text를 포함하는 열의 이름을 가져오거나 설정합니다.<br/>            기본값은 <see langword=\"null\" />. |
| column_x | string | r/w | X 좌표 값을 포함하는 열의 이름을 가져오거나 설정합니다.<br/>            기본값은 <see langword=\"null\" />. |
| column_y | string | r/w | Y 좌표 값을 포함하는 열의 이름을 가져오거나 설정합니다.<br/>            기본값은 <see langword=\"null\" />. |
| column_z | string | r/w | Z 좌표 값을 포함하는 열의 이름을 가져오거나 설정합니다.<br/>            기본값은 <see langword=\"null\" />. |
| create_midpoints | bool | r/w | 각 기하학 세그먼트의 중간에 새로운 점을 추가할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points | bool | r/w | 각 기하학에서 인접한 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| delimiter | char | r/w | 값을 구분하기 위해 구분자로 사용되는 문자를 가져오거나 설정합니다.<br/>            기본값은 ','. |
| double_quote_escape | char | r/w | 큰따옴표를 이스케이프하기 위해 사용되는 문자를 가져오거나 설정합니다.<br/>            기본값은 '\"'. |
| has_attribute_names | bool | r/w | 속성 이름이 포함된 헤더 행이 존재하는지 결정합니다.<br/>            기본값은 <see langword=\"true\" />. |
| linearization_tolerance | double | r/w | 곡선 지오메트리를 선형화하는 데 사용할 허용오차입니다. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| simplify_segments | bool | r/w | 각 지오메트리에서 동일한 세그먼트에 있는 점을 삭제할지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/)에 대한 거리를 결정합니다. 기본값은 <see langword="0" />입니다. |
| start_line_number | int | r/w | 데이터를 읽을 때 첫 번째가 될 행 번호(0부터 시작)를 가져오거나 설정합니다.<br/>            기본값은 0입니다. |
| validate_geometries_on_write | bool | r/w | 지오메트리가 레이어에 추가될 때 검증해야 하는지 여부를 결정합니다.<br/>            <see langword="true" /> 로 설정하면, 레이어에 추가될 때마다 각 지오메트리에 대해 [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 호출됩니다. 검증이 실패하면 ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/)이 <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/)이 발생합니다. |
| write_polygons_as_lines | bool | r/w | 폴리곤 또는 멀티폴리곤을 라인스트링으로 변환하는 것이 허용되는지 여부를 결정합니다. 기본값은 <see langword="false" />입니다. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X 및 Y 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z 좌표에 적용되는 [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)입니다.<br/>            지오메트리가 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에 추가되거나 해당 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)에서 읽어올 때 적용됩니다.<br/>            기본값은 [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/)입니다. |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

새 인스턴스를 생성합니다.

