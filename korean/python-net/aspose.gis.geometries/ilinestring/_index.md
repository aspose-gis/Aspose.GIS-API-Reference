---
title: "ILineString 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.gis.geometries/ilinestring/
---

**Summary:** A multi-vertex curve with linear interpolation between points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.ILineString

**Inheritance:** ICurve, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | 이 [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/)의 위상 차원을 가져옵니다.<br/>            차원을 알 수 없는 경우(예: 빈 GEOMETRYCOLLECTION) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/)가 반환됩니다. |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | 곡선의 끝점 복사본을 반환합니다. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | 지오메트리의 유형을 가져옵니다. |
| has_curve_geometry | bool | r | 이 지오메트리가 곡선(선형이 아닌) 지오메트리를 포함하고 있는지 여부를 나타내는 값을 가져옵니다. |
| has_m | bool | r | 이 인스턴스에 M 좌표가 있는지 여부를 나타내는 값을 가져옵니다. |
| has_z | bool | r | 이 인스턴스에 Z 좌표가 있는지 여부를 나타내는 값을 가져옵니다. |
| is_closed | bool | r | 곡선이 닫혔는지 여부를 나타내는 값을 가져옵니다.<br/>            곡선은 시작 점이 끝 점과 같으면 닫힌 것입니다. |
| is_empty | bool | r | 이 인스턴스가 비어 있는지 여부를 나타내는 값을 가져옵니다(빈 포인트 집합을 나타냅니다). |
| is_simple | bool | r | SFA 관점에서 이 인스턴스가 단순한지 여부를 나타내는 값을 가져옵니다. |
| is_valid | bool | r | 이 인스턴스가 유효한지 여부를 나타내는 값을 가져옵니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 이 인스턴스의 SpatialReferenceSystem을 가져옵니다.<br/>            SpatialReferenceSystem을 알 수 없는 경우 이 속성은 <see langword="null" />일 수 있습니다. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | 곡선의 시작점 복사본을 반환합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | 이 지오메트리를 Well-Known Binary 표현으로 변환합니다. |
| [as_binary(variant)](#as_binary_variant_2) | 이 지오메트리를 Well-Known Binary 표현으로 변환합니다. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | 이 지오메트리를 이미지 표현으로 내보냅니다. |
| [as_text()](#as_text__6) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [as_text(variant)](#as_text_variant_7) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [as_text(variant, format)](#as_text_variant_format_8) | 이 지오메트리를 Well-Known Text 표현으로 변환합니다. |
| [clone()](#clone__9) | 이 인스턴스를 복제합니다. |
| [covered_by(other)](#covered_by_other_10) | 지정된 지오메트리에 의해 이 지오메트리가 포함되는지 여부를 판단합니다. |
| [covers(other)](#covers_other_11) | 이 지오메트리가 지정된 지오메트리를 포함하는지 여부를 판단합니다. |
| [crosses(other)](#crosses_other_12) | 이 기하와 지정된 기하가 교차하는지 확인합니다. |
| [difference(other)](#difference_other_13) | 이 기하에서 지정된 기하를 빼냅니다. |
| [disjoint(other)](#disjoint_other_14) | 이 기하가 지정된 기하와 분리되어 있는지 확인합니다. |
| [get_area()](#get_area__15) | 이 기하의 면적을 계산합니다. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | 이 기하 주변에 버퍼 영역을 계산합니다. |
| [get_centroid()](#get_centroid__17) | 이 기하의 중심점을 계산합니다. |
| [get_convex_hull()](#get_convex_hull__18) | 이 기하의 볼록 껍질을 계산합니다. |
| [get_distance_to(other)](#get_distance_to_other_19) | 이 기하와 지정된 기하 사이의 최소 거리를 계산합니다. |
| [get_extent()](#get_extent__20) | 이 기하의 경계 범위를 계산하고 반환합니다. |
| [get_length()](#get_length__21) | 이 기하의 길이를 계산합니다. |
| [intersection(other)](#intersection_other_22) | 이 기하와 지정된 기하 사이의 교차점을 구축합니다. |
| [intersects(extent)](#intersects_extent_23) | 이 기하가 지정된 범위와 교차하는지 확인합니다. |
| [intersects(other)](#intersects_other_24) | 이 기하와 지정된 기하가 교차하는지 확인합니다. |
| [overlaps(other)](#overlaps_other_25) | 이 기하가 지정된 기하와 겹치는지 확인합니다. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_26) | 이 기하와 지정된 기하의 DE-9IM 교차 매트릭스가 제공된 패턴과 일치하는지 확인합니다. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__27) | 이 기하를 선으로 표현한 다각형을 가져옵니다. |
| [spatially_contains(other)](#spatially_contains_other_28) | 이 기하가 지정된 기하를 공간적으로 포함하는지 확인합니다. |
| [spatially_equals(other)](#spatially_equals_other_29) | 이 기하가 지정된 기하와 공간적으로 같은지 확인합니다. |
| [sym_difference(other)](#sym_difference_other_30) | 이 기하와 지정된 기하 사이의 대칭 차집합을 만듭니다. |
| [to_editable()](#to_editable__31) | 이 기하의 편집 가능한 복사본을 가져옵니다. |
| [to_linear_geometry()](#to_linear_geometry__32) | 기본 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_33) | 지정된 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다. |
| [touches(other)](#touches_other_34) | 이 기하와 지정된 기하가 접하는지 판단합니다. |
| [union(other)](#union_other_35) | 이 기하와 지정된 기하를 합칩니다. |
| [union(other)](#union_other_36) | 이 기하와 지정된 기하를 합칩니다. |
| [within(extent)](#within_extent_37) | 이 기하가 지정된 범위 내에 있는지 판단합니다. |
| [within(other)](#within_other_38) | 이 기하가 지정된 기하 내에 있는지 판단합니다. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

이 지오메트리를 Well-Known Binary 표현으로 변환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| byte | 이 기하의 Well-Known Binary 표현입니다. |


### Method: as_binary(variant) {#as_binary_variant_2}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


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


### Method: as_text() {#as_text__6}


```
 as_text() 
```

이 지오메트리를 Well-Known Text 표현으로 변환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 기하의 Well-Known Text 표현입니다. |


### Method: as_text(variant) {#as_text_variant_7}


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


### Method: as_text(variant, format) {#as_text_variant_format_8}


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


### Method: clone() {#clone__9}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | 이 인스턴스의 복제본 |


### Method: covered_by(other) {#covered_by_other_10}


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


### Method: covers(other) {#covers_other_11}


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


### Method: crosses(other) {#crosses_other_12}


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


### Method: difference(other) {#difference_other_13}


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


### Method: disjoint(other) {#disjoint_other_14}


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


### Method: get_area() {#get_area__15}


```
 get_area() 
```

이 기하의 면적을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 이 기하학의 면적.<br/>            이 기하학이 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)인 경우, 이 기하학 요소들의 면적 합계. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


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


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

이 기하의 중심점을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | 이 기하학의 중심점. 이 기하학이 비어 있으면 빈 점이 반환됩니다.<br/>            중심점은 이 기하학 내에서 가장 높은 차원의 기하학들의 중심점과 동일합니다.<br/>            (예: 점과 선이 모두 포함된 경우, 선만이 중심점에 기여합니다). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

이 기하의 볼록 껍질을 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 이 기하학의 볼록 껍질을 나타내는 기하학.<br/>            이 기하학에 점이 없으면 결과는 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)입니다.<br/>            이 기하학에 점이 하나만 있으면 결과는 그 점입니다.<br/>            이 기하학에 점이 두 개만 있으면 결과는 해당 점들을 가진 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)입니다.<br/>            이 기하학에 점이 세 개 이상 있으면 결과는 모든 점을 둘러싼 볼록 껍질을 나타내는 [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/)입니다. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


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


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

이 기하의 경계 범위를 계산하고 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 기하학의 경계 범위. |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

이 기하의 길이를 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 이 기하학의 길이.<br/>            이것이 [Polygon](/psd/python-net/aspose.gis.geometries/polygon/)인 경우 둘레.<br/>            이 기하학이 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)인 경우 요소들의 길이 합계. |


### Method: intersection(other) {#intersection_other_22}


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


### Method: intersects(extent) {#intersects_extent_23}


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


### Method: intersects(other) {#intersects_other_24}


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


### Method: overlaps(other) {#overlaps_other_25}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_26}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__27}


```
 replace_polygons_by_lines() 
```

이 기하를 선으로 표현한 다각형을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 다각형 기하가 없는 기하입니다. 다음 변환이 적용됩니다:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)은 선형화됩니다<br/>            ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) 로 변환됨)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)은 [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 결합됩니다</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_28}


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


### Method: spatially_equals(other) {#spatially_equals_other_29}


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


### Method: sym_difference(other) {#sym_difference_other_30}


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


### Method: to_editable() {#to_editable__31}


```
 to_editable() 
```

이 기하의 편집 가능한 복사본을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring) | 이 기하의 편집 가능한 복사본. |


### Method: to_linear_geometry() {#to_linear_geometry__32}


```
 to_linear_geometry() 
```

기본 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | 곡선 지오메트리가 없는 지오메트리입니다. 이는 <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float)와 동일하며,<br/>            기본 <c>tolerance</c>를 사용합니다. 기본 <c>tolerance</c>는 이 지오메트리의 [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)에 의해 정의됩니다:<br/>            <ul><br/>            <li> 투영된 SRS의 경우 허용오차는 0.001 미터(SRS 단위)입니다 </li><br/>            <li> 지리적 SRS의 경우 허용오차는 <c>1e-5</c>도(SRS 단위)입니다 </li><br/>            <li> 알 수 없는 SRS의 경우 허용오차는 <c>1e-5</c>입니다 </li><br/>            </ul><br/>            적용되는 변환에 대한 자세한 내용은 <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) 사양을 참조하십시오. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_33}


```
 to_linear_geometry(tolerance) 
```

지정된 <c>tolerance</c>를 사용하여 이 기하의 근사 또는 동등한 비곡선 버전을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| tolerance | double | 사용할 <c>tolerance</c>입니다. 결과는 <c>tolerance</c>보다 작은 거리 안에 곡선 지오메트리로부터 보장됩니다,<br/>            단, 지오메트리를 선형화하는 데 필요한 점 수가 현재 사분면당 최대값인 10000점을 초과하지 않는 경우에만. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | 곡선 지오메트리가 없는 지오메트리입니다. 다음 변환이 적용됩니다:<br/>            <ul><br/>            <li> [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)는 선형화됩니다<br/>            (지정된 <paramref name="tolerance" />와 함께 [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 변환) </li><br/>            <li> [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)는 <c>LineString</c>으로 결합됩니다 </li><br/>            <li> [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)는 [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 변환됩니다 </li><br/>            <li> [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)는 [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 변환됩니다 </li><br/>            <li> [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/)는 [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)으로 변환됩니다 </li><br/>            </ul><br/>            결과적으로, 출력 지오메트리의 [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/)는 <see langword="false" />입니다. |


### Method: touches(other) {#touches_other_34}


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


### Method: union(other) {#union_other_35}


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


### Method: union(other) {#union_other_36}


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


### Method: within(extent) {#within_extent_37}


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


### Method: within(other) {#within_other_38}


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


