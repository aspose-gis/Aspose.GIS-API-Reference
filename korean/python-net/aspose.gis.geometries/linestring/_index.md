---
title: "LineString 클래스"
type: docs
weight: 230
url: /ko/python-net/aspose.gis.geometries/linestring/
---

**Summary:** A multi-vertex line.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.LineString

**Inheritance:** IGeometry, ICurve, ILineString, Curve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LineString()](#LineString__1) | 새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다. |
| [LineString(collection)](#LineString_collection_2) | 새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다. |
| [LineString(other)](#LineString_other_3) | 새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | 이 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/)에 대한 좌표 차원의 수를 가져옵니다. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | 이 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/)의 위상 차원을 가져옵니다. |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | 곡선의 끝점 복사본을 반환합니다. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | 지오메트리의 유형을 가져옵니다. |
| has_curve_geometry | bool | r | 이 지오메트리가 곡선(선형이 아닌) 지오메트리를 포함하고 있는지 여부를 나타내는 값을 가져옵니다. |
| has_m | bool | r/w | 이 인스턴스에 M 좌표가 있는지 여부를 나타내는 값을 가져옵니다. |
| has_z | bool | r/w | 이 인스턴스에 Z 좌표가 있는지 여부를 나타내는 값을 가져옵니다. |
| is_closed | bool | r | 곡선이 닫혔는지 여부를 나타내는 값을 가져옵니다.<br/>            시작점이 끝점과 같으면 곡선이 닫힌 것입니다. |
| is_empty | bool | r | 이 인스턴스가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| is_simple | bool | r | SFA 관점에서 이 인스턴스가 단순한지 여부를 나타내는 값을 가져옵니다. |
| is_valid | bool | r | 이 인스턴스가 유효한지 여부를 나타내는 값을 가져옵니다. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | null 지오메트리 인스턴스를 가져옵니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 이 인스턴스의 SpatialReferenceSystem을 가져옵니다.<br/>            SpatialReferenceSystem이 설정되지 않은 경우 이 속성은 <see langword=\"null\" />일 수 있습니다.<br/>            새 SpatialReferenceSystem을 할당해도 좌표 변환은 수행되지 않으며, 참조만 변경됩니다. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | 곡선의 시작점 복사본을 반환합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | 선의 끝에 점을 추가합니다. |
| [add_point(x, y)](#add_point_x_y_2) | 선의 끝에 점을 추가합니다. |
| [add_point(x, y, z)](#add_point_x_y_z_3) | 선의 끝에 점을 추가합니다. |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | 선의 끝에 점을 추가합니다. |
| [as_binary()](#as_binary__5) | 이 지오메트리를 Well-Known Binary 표현으로 변환합니다. |
| [as_binary(variant)](#as_binary_variant_6) | 이 지오메트리를 Well-Known Binary 표현으로 변환합니다. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_text()](#as_text__10) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [as_text(variant)](#as_text_variant_11) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [as_text(variant, format)](#as_text_variant_format_12) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [clone()](#clone__13) | 이 인스턴스를 복제합니다. |
| [covered_by(other)](#covered_by_other_14) | 지정된 지오메트리에 의해 이 지오메트리가 포함되는지 여부를 판단합니다. |
| [covers(other)](#covers_other_15) | 이 지오메트리가 지정된 지오메트리를 포함하는지 여부를 판단합니다. |
| [crosses(other)](#crosses_other_16) | 이 기하와 지정된 기하가 교차하는지 확인합니다. |
| [difference(other)](#difference_other_17) | 이 기하에서 지정된 기하를 빼냅니다. |
| [disjoint(other)](#disjoint_other_18) | 이 기하가 지정된 기하와 분리되어 있는지 확인합니다. |
| [from_binary(wkb)](#from_binary_wkb_19) | Well-Known Binary 표현에서 기하를 생성합니다. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | Well-Known Binary 표현에서 기하를 생성합니다. |
| [from_text(wkt)](#from_text_wkt_21) | Well-Known Text 표현에서 기하를 생성합니다. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | Well-Known Text 표현에서 기하를 생성합니다. |
| [get_area()](#get_area__23) | 이 기하의 면적을 계산합니다. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | 이 기하 주변에 버퍼 영역을 계산합니다. |
| [get_centroid()](#get_centroid__25) | 이 기하의 중심점을 계산합니다. |
| [get_convex_hull()](#get_convex_hull__26) | 이 기하의 볼록 껍질을 계산합니다. |
| [get_distance_to(other)](#get_distance_to_other_27) | 이 기하와 지정된 기하 사이의 최소 거리를 계산합니다. |
| [get_extent()](#get_extent__28) | 이 기하의 경계 범위를 계산하고 반환합니다. |
| [get_length()](#get_length__29) | 이 기하의 길이를 계산합니다. |
| [intersection(other)](#intersection_other_30) | 이 기하와 지정된 기하 사이의 교차점을 구축합니다. |
| [intersects(extent)](#intersects_extent_31) | 이 기하가 지정된 범위와 교차하는지 확인합니다. |
| [intersects(other)](#intersects_other_32) | 이 기하와 지정된 기하가 교차하는지 확인합니다. |
| [overlaps(other)](#overlaps_other_33) | 이 기하가 지정된 기하와 겹치는지 확인합니다. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_34) | 이 기하와 지정된 기하의 DE-9IM 교차 매트릭스가 제공된 패턴과 일치하는지 확인합니다. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | 이 기하를 선으로 표현한 다각형을 가져옵니다. |
| reverse() | 이 [LineString](/psd/python-net/aspose.gis.geometries/linestring/)의 점 순서를 반전시킵니다. |
| [round_m(digits)](#round_m_digits_36) | M 좌표를 지정된 소수 자릿수로 반올림합니다. |
| [round_xy(digits)](#round_xy_digits_37) | X 및 Y 좌표를 지정된 소수 자릿수로 반올림합니다. |
| [round_z(digits)](#round_z_digits_38) | Z 좌표를 지정된 소수 자릿수로 반올림합니다. |
| set_empty() | 이 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/)를 비웁니다. |
| [spatially_contains(other)](#spatially_contains_other_39) | 이 기하가 지정된 기하를 공간적으로 포함하는지 확인합니다. |
| [spatially_equals(other)](#spatially_equals_other_40) | 이 기하가 지정된 기하와 공간적으로 같은지 확인합니다. |
| [sym_difference(other)](#sym_difference_other_41) | 이 기하와 지정된 기하 사이의 대칭 차집합을 만듭니다. |
| [to_editable()](#to_editable__42) | 이 기하의 편집 가능한 복사본을 가져옵니다. |
| [to_linear_geometry()](#to_linear_geometry__43) | 기본 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | 지정된 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다. |
| [to_svg(extent)](#to_svg_extent_45) | 이 기하를 Svg 표현으로 변환합니다. |
| [touches(other)](#touches_other_46) | 이 기하와 지정된 기하가 접하는지 판단합니다. |
| [union(other)](#union_other_47) | 이 기하와 지정된 기하를 합칩니다. |
| [union(other)](#union_other_48) | 이 기하와 지정된 기하를 합칩니다. |
| [within(extent)](#within_extent_49) | 이 기하가 지정된 범위 내에 있는지 판단합니다. |
| [within(other)](#within_other_50) | 이 기하가 지정된 기하 내에 있는지 판단합니다. |


### Constructor: LineString() {#LineString__1}


```
 LineString() 
```

새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다.

### Constructor: LineString(collection) {#LineString_collection_2}


```
 LineString(collection) 
```

새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 컬렉션 | System.Collections.Generic.IEnumerable<IPoint> | 점들의 컬렉션입니다. |

### Constructor: LineString(other) {#LineString_other_3}


```
 LineString(other) 
```

새로운 [LineString](/psd/python-net/aspose.gis.geometries/linestring/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | 데이터를 복사할 다른 선입니다. |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

선의 끝에 점을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | 추가할 점입니다. |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

선의 끝에 점을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | X 좌표값입니다. |
| y | double | Y 좌표값입니다. |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

선의 끝에 점을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | X 좌표값입니다. |
| y | double | Y 좌표값입니다. |
| z | double | Z 좌표값입니다. |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

선의 끝에 점을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | X 좌표값입니다. |
| y | double | Y 좌표값입니다. |
| z | double | Z 좌표값입니다. |
| m | double | M 좌표값입니다. |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

이 지오메트리를 Well-Known Binary 표현으로 변환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| byte | 이 기하의 Well-Known Binary 표현입니다. |


### Method: as_binary(variant) {#as_binary_variant_6}


```
 as_binary(variant) 
```

이 지오메트리를 Well-Known Binary 표현으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | 사용할 Well-Known Binary 변형입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| byte | 이 기하의 Well-Known Binary 표현입니다. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

이 지오메트리를 이미지 표현으로 내보냅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 출력 이미지의 경로입니다. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 너비입니다. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 높이입니다. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 사용할 렌더러입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

이 지오메트리를 이미지 표현으로 내보냅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output_path | string | 출력 이미지의 경로입니다. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 너비입니다. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 높이입니다. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 사용할 렌더러입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


```
 as_image(width, height, renderer, symbolizer) 
```

이 지오메트리를 이미지 표현으로 내보냅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 너비입니다. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 지도 높이입니다. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 사용할 렌더러입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| _io.BufferedRandom | 스트림 형태의 이미지 |


### Method: as_text() {#as_text__10}


```
 as_text() 
```

이 지오메트리를 Well-Known Text 표현으로 변환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 기하의 Well-Known Text 표현입니다. |


### Method: as_text(variant) {#as_text_variant_11}


```
 as_text(variant) 
```

이 지오메트리를 Well-Known Text 표현으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 사용할 Well-Known Text 변형입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 기하의 Well-Known Text 표현입니다. |


### Method: as_text(variant, format) {#as_text_variant_format_12}


```
 as_text(variant, format) 
```

이 지오메트리를 Well-Known Text 표현으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 사용할 Well-Known Text 변형입니다. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 문자열로 변환하기 위한 좌표 형식입니다. [NumericFormat](/psd/python-net/aspose.gis/numericformat/)을 참고하세요. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 기하의 Well-Known Text 표현입니다. |


### Method: clone() {#clone__13}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | 이 인스턴스의 복제본 |


### Method: covered_by(other) {#covered_by_other_14}


```
 covered_by(other) 
```

지정된 지오메트리에 의해 이 지오메트리가 포함되는지 여부를 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 이 기하가 다른 기하에 \"spatially covered by\"인 경우. <see langword=\"false\" /> 그렇지 않으면. |


### Method: covers(other) {#covers_other_15}


```
 covers(other) 
```

이 지오메트리가 지정된 지오메트리를 포함하는지 여부를 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 이 기하가 다른 기하를 \"spatially covers\"하는 경우. <see langword=\"false\" /> 그렇지 않으면. |


### Method: crosses(other) {#crosses_other_16}


```
 crosses(other) 
```

이 기하와 지정된 기하가 교차하는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 이 기하가 다른 기하와 \"spatially crosses\"하는 경우. <see langword=\"false\" /> 그렇지 않으면. |


### Method: difference(other) {#difference_other_17}


```
 difference(other) 
```

이 기하에서 지정된 기하를 빼냅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 빼기 위한 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하학과 인수의 차이를 나타내는 기하학. 결과 기하학은<br/>            이 기하학에 존재하지만 인수에는 존재하지 않는 점 집합을 포함합니다. |


### Method: disjoint(other) {#disjoint_other_18}


```
 disjoint(other) 
```

이 기하가 지정된 기하와 분리되어 있는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 이 기하학이 다른 기하학과 \"공간적으로 분리\"된 경우. <see langword=\"false\" /> 그 외의 경우. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


```
 from_binary(wkb) 
```

Well-Known Binary 표현에서 기하를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkb | byte | 기하학의 Well-Known Binary 표현. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 인수에 의해 표현된 기하학. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


```
 from_binary(wkb, spatial_reference_system) 
```

Well-Known Binary 표현에서 기하를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkb | byte | 기하학의 Well-Known Binary 표현. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 기하학에 할당될 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 인수에 의해 표현된 기하학. |


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


```
 from_text(wkt) 
```

Well-Known Text 표현에서 기하를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkt | string | 기하학의 Well-Known Text 표현. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 인수에 의해 표현된 기하학. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


```
 from_text(wkt, spatial_reference_system) 
```

Well-Known Text 표현에서 기하를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkt | string | 기하학의 Well-Known Text 표현. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 기하학에 할당될 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 인수에 의해 표현된 기하학. |


### Method: get_area() {#get_area__23}


```
 get_area() 
```

이 기하의 면적을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 이 기하학의 면적.<br/>            이 기하학이 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)인 경우, 이 기하학 요소들의 면적 합계. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


```
 get_buffer(distance, quadrant_segments) 
```

이 기하 주변에 버퍼 영역을 계산합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 거리 | double | 버퍼 영역 너비(Spatial Reference 단위). |
| quadrant_segments | int | 곡률 90도를 근사하는 데 사용되는 세그먼트 수.<br/>            이 수가 클수록 곡선 근사가 더 정확해집니다.<br/>            기본값은 30입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하학으로부터 지정된 거리 내에 있는 모든 점을 나타내는 기하학.<br/>            결과 유형은 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/), 또는 [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) 중 하나입니다. |


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

이 기하의 중심점을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | 이 기하학의 중심점. 이 기하학이 비어 있으면 빈 점이 반환됩니다.<br/>            중심점은 이 기하학 내에서 가장 높은 차원의 기하학들의 중심점과 동일합니다.<br/>            (예: 점과 선이 모두 포함된 경우, 선만이 중심점에 기여합니다). |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

이 기하의 볼록 껍질을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하학의 볼록 껍질을 나타내는 기하학.<br/>            이 기하학에 점이 없으면 결과는 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)입니다.<br/>            이 기하학에 점이 하나만 있으면 결과는 그 점입니다.<br/>            이 기하학에 점이 두 개만 있으면 결과는 해당 점들을 가진 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)입니다.<br/>            이 기하학에 점이 세 개 이상 있으면 결과는 모든 점을 둘러싼 볼록 껍질을 나타내는 [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/)입니다. |


### Method: get_distance_to(other) {#get_distance_to_other_27}


```
 get_distance_to(other) 
```

이 기하와 지정된 기하 사이의 최소 거리를 계산합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 거리를 찾을 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 두 지오메트리가 모두 [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/)가 아닌 경우 - 지오메트리들 간 가장 가까운 점 사이의 거리입니다.<br/>            하나 이상의 지오메트리가 비어 있는 경우 -1이 반환됩니다. |


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

이 기하의 경계 범위를 계산하고 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 기하학의 경계 범위. |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

이 기하의 길이를 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 이 기하학의 길이.<br/>            이것이 [Polygon](/psd/python-net/aspose.gis.geometries/polygon/)인 경우 둘레.<br/>            이 기하학이 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)인 경우 요소들의 길이 합계. |


### Method: intersection(other) {#intersection_other_30}


```
 intersection(other) 
```

이 기하와 지정된 기하 사이의 교차점을 구축합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 교차를 계산할 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하학과 인수의 교차점을 나타내는 기하학. 결과 기하학은<br/>            이 기하학과 인수 모두에 존재하는 점 집합을 포함합니다. |


### Method: intersects(extent) {#intersects_extent_31}


```
 intersects(extent) 
```

이 기하가 지정된 범위와 교차하는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 범위. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 범위와 교차하면; <see langword="false" /> 그렇지 않으면. |


### Method: intersects(other) {#intersects_other_32}


```
 intersects(other) 
```

이 기하와 지정된 기하가 교차하는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 다른 기하와 \"공간적으로 교차\"할 경우. <see langword="false" /> 그렇지 않으면. |


### Method: overlaps(other) {#overlaps_other_33}


```
 overlaps(other) 
```

이 기하가 지정된 기하와 겹치는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 다른 기하와 \"공간적으로 겹침\"인 경우. <see langword="false" /> 그렇지 않으면. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_34}


```
 relate(other, intersection_pattern_matrix) 
```

이 기하와 지정된 기하의 DE-9IM 교차 매트릭스가 제공된 패턴과 일치하는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |
| intersection_pattern_matrix | string | 일치시킬 패턴입니다.<br/>            문자열 길이는 9와 같아야 합니다.<br/>            문자열의 각 문자는 교차의 예상 차원을 나타냅니다:<br/>            <ul><br/>            <li>문자 0 - 기하들의 내부 사이.</li><br/>            <li>문자 1 - 이 기하의 내부와 다른 기하의 경계 사이.</li><br/>            <li>문자 2 - 이 기하의 내부와 다른 기하의 외부 사이.</li><br/>            <li>문자 3 - 이 기하의 경계와 다른 기하의 내부 사이.</li><br/>            <li>문자 4 - 기하들의 경계 사이.</li><br/>            <li>문자 5 - 이 기하의 경계와 다른 기하의 외부 사이.</li><br/>            <li>문자 6 - 이 기하의 외부와 다른 기하의 내부 사이.</li><br/>            <li>문자 7 - 이 기하의 외부와 다른 기하의 경계 사이.</li><br/>            <li>문자 8 - 기하들의 외부 사이.</li><br/>            </ul><br/>            가능한 각 문자 값은:<br/>            <ul><br/>            <li>* - 모든 값;</li><br/>            <li>F - 교차 없음;</li><br/>            <li>T - 모든 교차;</li><br/>            <li>0 - 점 교차 (예: 공유된 점);</li><br/>            <li>1 - 선 교차 (예: 공유된 선분);</li><br/>            <li>2 - 면 교차 (예: 공유된 다각형 부분);</li><br/>            </ul><br/>            예를 들어, 교차 패턴 \"F0*******\"은 기하들의 내부 사이에 교차가 없어야 하며, 기하들의 경계 사이 교차는 점이어야 함을 의미합니다.<br/>            교차 매트릭스 패턴에 대한 자세한 내용은 OpenGIS Simple Features Specification을 참조하십시오. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 교차 매트릭스가 패턴과 일치하면; <see langword="false" /> 그렇지 않으면. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

이 기하를 선으로 표현한 다각형을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 다각형 기하가 없는 기하입니다. 다음 변환이 적용됩니다:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)은 선형화됩니다<br/>            ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) 로 변환됨)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)은 [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 결합됩니다</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

M 좌표를 지정된 소수 자릿수로 반올림합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 숫자 | int | 소수 자릿수의 개수. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

X 및 Y 좌표를 지정된 소수 자릿수로 반올림합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 숫자 | int | 소수 자릿수의 개수. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Z 좌표를 지정된 소수 자릿수로 반올림합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 숫자 | int | 소수 자릿수의 개수. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

이 기하가 지정된 기하를 공간적으로 포함하는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 다른 기하를 \"공간적으로 포함\"하는 경우. <see langword="false" /> 그렇지 않으면. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

이 기하가 지정된 기하와 공간적으로 같은지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 지정된 기하와 \"공간적으로 동일\"한 경우. <see langword="false" /> 그렇지 않으면. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

이 기하와 지정된 기하 사이의 대칭 차집합을 만듭니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 대칭 차이를 계산할 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하와 인수의 대칭 차이를 나타내는 기하입니다. 결과 기하에는<br/>            한쪽 기하에만 존재하고 양쪽 모두에 존재하지 않는 점 집합이 포함됩니다. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

이 기하의 편집 가능한 복사본을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring) | 이 기하의 편집 가능한 복사본. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

기본 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | 이 곡선에 근사하거나 동등한 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)입니다.<br/>            이는 <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float)와 기본 <c>tolerance</c>를 사용한 경우와 동일합니다.<br/>            기본 <c>tolerance</c> 값은 이 기하학의 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)에 따라 달라집니다:<br/>            <ul><br/>            <li> 투영된 SRS의 경우 허용오차는 0.001 미터(SRS 단위)입니다 </li><br/>            <li> 지리적 SRS의 경우 허용오차는 <c>1e-5</c>도(SRS 단위)입니다 </li><br/>            <li> 알 수 없는 SRS의 경우 허용오차는 <c>1e-5</c>입니다 </li><br/>            </ul><br/>            적용된 변환에 대한 자세한 내용은 <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) 사양을 참조하십시오. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

지정된 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| tolerance | double | 사용할 <c>tolerance</c>. 결과는 <c>tolerance</c>보다 작은 거리로 곡선 기하에서 보장됩니다<br/>             단, 기하를 선형화하는 데 필요한 점 수가 사분면당 최대값을 초과하면(현재 10000점) 제외합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | 이 곡선에 근사하거나 동등한 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) :<br/>             <ul><br/>             이 객체가 자체가 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)인 경우 결과는 이 객체와 동등합니다<br/>             이 객체가 [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/)인 경우 결과는 지정된 <paramref name="tolerance" /> 로 선형화된 원형 문자열입니다<br/>             이 객체가 [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/)인 경우 - 모든 곡선이 선형화된 후 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) 로 결합됩니다<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

이 기하를 Svg 표현으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 이 기하를 Svg로 변환하기 위한 범위 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | Svg 표현. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

이 기하와 지정된 기하가 접하는지 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 다른 기하와 \"공간적으로 접촉\"하는 경우. <see langword="false" /> 그렇지 않으면. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

이 기하와 지정된 기하를 합칩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 합칠 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하와 인수의 합집합을 나타내는 기하입니다. 결과 기하에는<br/>            이 기하에 있거나 인수에 있는 점 집합이 포함됩니다. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

이 기하와 지정된 기하를 합칩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | 합칠 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하와 인수의 합집합을 나타내는 기하입니다. 결과 기하에는<br/>            이 기하에 있거나 인수에 있는 점 집합이 포함됩니다. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

이 기하가 지정된 범위 내에 있는지 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 범위. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 범위 내에 있는 경우; <see langword="false" /> 그렇지 않으면. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

이 기하가 지정된 기하 내에 있는지 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 기하. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 이 기하가 다른 기하 \"공간적으로 내부에 있음\"인 경우. <see langword="false" /> 그렇지 않으면. |


