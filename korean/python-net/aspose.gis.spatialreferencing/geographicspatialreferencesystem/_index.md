---
title: "GeographicSpatialReferenceSystem 클래스"
type: docs
weight: 80
url: /ko/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 이 SRS에서 각도 차원에 사용되는 단위. |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | 이 SRS를 [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/)으로 변환하여 반환합니다.<br/>            변환이 가능한지 확인하려면 [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)를 사용하십시오. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | 이 SRS를 [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/)으로 변환하여 반환합니다.<br/>            변환이 가능한지 확인하려면 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)를 사용하십시오. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | 이 값을 반환합니다. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | 이 SRS를 [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) 로 변환한 결과를 반환합니다.<br/>            변환이 가능한지 확인하려면 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 를 사용하십시오. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | 이 SRS를 [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) 로 변환하여 반환합니다.<br/>            변환이 가능한지 확인하려면 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 를 사용하십시오. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | 이 SRS를 [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) 로 변환한 결과를 반환합니다.<br/>            변환이 가능한지 확인하려면 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 를 사용하십시오. |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | 이 SRS의 축 순서.<br/>            이 SRS가 유효하지 않으며 축 방향이 잘못된 경우, [GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/)이 반환됩니다. |
| dimensions_count | int | r | 이 SRS의 차원 수를 반환합니다. 지리 SRS의 경우 다음과 같습니다:<br/>            두 개 - 단일 지리 SRS인 경우.<br/>            세 개 - 복합 SRS인 경우, 이는 단일 2차원 지리 SRS와 수직 SRS로 구성되어 세 번째 차원을 추가합니다. |
| epsg_code | int | r | 이 객체의 식별자가 EPSG 식별자인 경우 - 코드를 반환합니다. 그렇지 않으면 -1을 반환합니다. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) 공간 좌표계. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert 방위 등면적 (EPSG:3035) 공간 좌표계. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert 등각 원추 (EPSG:3034) 공간 좌표계. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | 이 SRS의 지리적 기준점을 반환합니다. |
| has_geographic_datum | bool | r | 지리 SRS는 항상 기본 자오선을 가지므로 <see langword="true" />를 반환합니다. |
| has_prime_meridian | bool | r | 지리 SRS는 항상 기본 자오선을 가지므로 <see langword="true" />를 반환합니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 이 식별 가능한 객체의 식별자입니다. |
| is_compound | bool | r | 이 SRS가 복합인지 여부를 반환합니다 (두 개 SRS의 결합).<br/>            복합 SRS에서 다음 조합이 유효한 것으로 간주됩니다:<br/>            Geographic SRS + Vertical SRS인 경우, 복합 SRS의 유형은 [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) 가 됩니다.<br/>            Projected SRS + Vertical SRS인 경우, 복합 SRS의 유형은 [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) 가 됩니다.<br/>            SRS 조합이 다르면, 복합 SRS의 유형은 [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) 가 됩니다. |
| is_single | bool | r | 이 SRS가 단일인지 여부를 반환합니다 (두 개 SRS의 결합이 아님). |
| is_valid | bool | r | 다음과 동일합니다 <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, 하지만 오류 메시지는 반환하지 않습니다. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) 공간 좌표계. |
| 이름 | string | r | 이 객체의 이름입니다. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) 공간 좌표계. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) 공간 좌표계. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | 이 SRS의 기본 자오선을 반환합니다. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/)을 반환합니다. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) 공간 참조 시스템. |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) 공간 참조 시스템. |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) 공간 참조 시스템. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | 복합 SRS를 생성합니다. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | 지정된 EPSG 코드 기반의 공간 참조 시스템을 생성합니다. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | WKT(Well-Known Text) 문자열을 기반으로 새로운 <c>SpatialReferenceSystem</c>을 생성합니다. |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | 사용자 정의 매개변수에서 지오센트릭 SRS를 생성합니다. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | 사용자 정의 매개변수에서 지리적 SRS를 생성합니다. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | 로컬 공간 참조 시스템을 생성합니다. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | 사용자 정의 매개변수에서 투영된 SRS를 생성합니다. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | 이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>으로 변환을 생성합니다. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | 수직 SRS를 생성합니다. |
| [export_to_wkt()](#export_to_wkt__10) | 이 SRS의 표현을 WKT 문자열로 반환합니다.<br/>            결과 WKT 문자열은 OGC 01-009 사양과 일치하며, 일반적으로 "WKT1"이라고 명명됩니다. |
| [get_axis(dimension)](#get_axis_dimension_11) | 차원을 설명하는 [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/)를 가져옵니다. |
| [get_unit(dimension)](#get_unit_dimension_12) | 차원의 [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/)을 가져옵니다. |
| [is_equivalent(other)](#is_equivalent_other_13) | 이 SRS가 다른 SRS와 동등한지 감지합니다. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | 두 SRS가 동등한지 판단합니다.<br/>            동등한 SRS의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 SRS의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)이 있습니다. |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | 지정된 EPSG 코드 기반의 공간 참조 시스템을 생성합니다. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | WKT(Well-Known Text) 문자열을 기반으로 새로운 <c>SpatialReferenceSystem</c>을 생성합니다. |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | 이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>으로 변환을 생성합니다. |
| [validate(error_message)](#validate_error_message_18) | 이 SRS가 유효한지 판단합니다. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

복합 SRS를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 새 SRS의 이름. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 새 SRS의 헤드 SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 새 SRS의 테일 SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | 새 복합 SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

지정된 EPSG 코드 기반의 공간 참조 시스템을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| epsg | int | 공간 참조 시스템의 EPSG 코드. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 지정된 EPSG 코드를 가진 새로운 공간 참조 시스템. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

WKT(Well-Known Text) 문자열을 기반으로 새로운 <c>SpatialReferenceSystem</c>을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkt | string | WKT 문자열. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 새 <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

사용자 정의 매개변수에서 지오센트릭 SRS를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | 생성에 사용할 매개변수. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | 새 지구 중심 SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

사용자 정의 매개변수에서 지리적 SRS를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | 생성에 사용할 매개변수. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | 새 지리적 SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

로컬 공간 참조 시스템을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 공간 참조 시스템의 이름. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | SRS에서 사용할 기준점. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS에서 사용할 단위. |
| 축들 | System.Collections.Generic.ICollection<Axis> | SRS에서 사용할 축들. 비어 있으면 안 됩니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | 새 로컬 공간 참조 시스템. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

사용자 정의 매개변수에서 투영된 SRS를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | 생성에 사용할 매개변수. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | 새 투영 SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>으로 변환을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 다른 <c>SpatialReferenceSystem</c>. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | 이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>로의 변환. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

수직 SRS를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | SRS의 이름. <see langword="null" />인 경우. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | SRS에서 사용할 기준점. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS에서 사용할 단위. <see langword="null" />인 경우, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)가 사용됩니다. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | SRS에서 사용할 "up" 또는 "down" 방향의 축. <see langword="null" />인 경우, up 방향의 축이 사용됩니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS에 첨부될 식별자. 식별자를 첨부해도 다른 SRS 매개변수는 변경되지 않습니다.<br/>            식별자와 SRS 매개변수의 일관성을 보장하는 것은 여러분에게 달려 있습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | 새 수직 SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

이 SRS의 표현을 WKT 문자열로 반환합니다.<br/>            결과 WKT 문자열은 OGC 01-009 사양과 일치하며, 일반적으로 "WKT1"이라고 명명됩니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 SRS의 WKT 표현. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

차원을 설명하는 [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/)를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 차원 | int | 차원의 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | 차원을 설명하는 축. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

차원의 [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/)을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 차원 | int | 차원의 수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 차원의 단위. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

이 SRS가 다른 SRS와 동등한지 감지합니다. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 다른 SRS. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | bool 값, 이 SRS가 다른 SRS와 동등한지 여부를 나타냅니다. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

두 SRS가 동등한지 판단합니다.<br/>            동등한 SRS의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 SRS의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)이 있습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 첫 번째 SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 두 번째 SRS. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | bool 값, 두 SRS가 동등한지 여부를 나타냅니다. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

지정된 EPSG 코드 기반의 공간 참조 시스템을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| epsg | int | 공간 참조 시스템의 EPSG 코드. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 이 메서드가 <see langword=\"true\" /> 를 반환하면 지정된 EPSG 코드가 있는 SRS를 포함합니다; 그렇지 않으면,<br/>            <see langword=\"null\" /> 를 포함합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 지정된 EPSG 코드가 알려져 있고 SRS가 생성된 경우; <see langword=\"false\" /> 그 외의 경우. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

WKT(Well-Known Text) 문자열을 기반으로 새로운 <c>SpatialReferenceSystem</c>을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| wkt | string | WKT 문자열. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 이 메서드가 <see langword=\"true\" /> 를 반환하면 WKT에서 생성된 SRS를 포함합니다; 그렇지 않으면,<br/>            <see langword=\"null\" /> 를 포함합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> SRS가 성공적으로 생성된 경우; <see langword=\"false\" /> 그 외의 경우. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>으로 변환을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 다른 <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | 이 메서드가 <see langword=\"true\" /> 를 반환하면 변환을 포함합니다; 그렇지 않으면 <see langword=\"null\" /> 를 포함합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 이 <c>SpatialReferenceSystem</c>에서 다른 <c>SpatialReferenceSystem</c>로의 변환. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

이 SRS가 유효한지 판단합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| error_message | 문자열 | 메서드가 <see langword=\"false\" /> 를 반환하면, 이는 무효성에 대한 설명입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> SRS가 유효한 경우, <see langword=\"false\" /> 그 외의 경우. |


