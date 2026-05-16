---
title: "GeographicDatum 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | 타원체, 이 기준점에서 지구를 근사하는 데 사용됩니다. |
| epsg_code | int | r | 이 객체의 식별자가 EPSG 식별자인 경우 - 코드를 반환합니다. 그렇지 않으면 -1을 반환합니다. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 기준점. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 이 식별 가능한 객체의 식별자입니다. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 기준점. |
| 이름 | string | r | 이 객체의 이름입니다. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 기준점. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | 이 기준점의 좌표를 WGS84 기준점의 좌표로 변환하는 데 사용할 수 있는 BursaWolfParamters. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 기준점. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 기준점. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | 두 기준점이 동등한지 결정합니다.<br/>            동등한 기준점의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 기준점의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | 두 기준점이 동등한지 결정합니다.<br/>            동등한 기준점의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 기준점의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 이 기준점의 이름. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 이 기준점의 타원체. null일 수 없습니다. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | 이 기준점의 좌표를 WGS84 기준점의 좌표로 변환하기 위해 bursa wolf 공식에 제공할 수 있는 매개변수.<br/>            이 기준점이 WGS84에 가깝고 변환이 필요 없을 경우, 모든 값을 0으로 설정한 bursa wolf 매개변수를 전달하십시오.<br/>            null인 경우, ToWgs84는 [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) 매개변수로 설정됩니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 이 기준점의 식별자. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

두 기준점이 동등한지 결정합니다.<br/>            동등한 기준점의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 기준점의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 첫 번째 기준점. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 두 번째 기준점. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 두 기준점이 동등한지 여부를 나타내는 bool 값. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

두 기준점이 동등한지 결정합니다.<br/>            동등한 기준점의 동일한 좌표는 지구상의 같은 위치와 일치합니다.<br/>            동등한 기준점의 일부 매개변수는 다를 수 있으며, 예를 들어 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 다른 기준점. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 두 기준점이 동등한지 여부를 나타내는 bool 값. |


