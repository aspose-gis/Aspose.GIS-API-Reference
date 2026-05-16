---
title: "타원체 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | 새 타원체를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy 타원체. |
| epsg_code | int | r | 이 객체의 식별자가 EPSG 식별자인 경우 - 코드를 반환합니다. 그렇지 않으면 -1을 반환합니다. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980 타원체. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 이 식별 가능한 객체의 식별자입니다. |
| inverse_flattening | double | r | 타원체의 역편평화. 구인 경우 0. |
| is_sphere | bool | r | 이 타원체가 구인지 감지합니다. |
| is_valid | bool | r | 타원체가 유효한지 감지합니다: 반장축이 0보다 크고 역편평화가 양수이거나 0과 같습니다. |
| 이름 | string | r | 이 객체의 이름입니다. |
| semi_major_axis | double | r | 타원체의 반장축. |
| semi_minor_axis | double | r | 타원체의 반단축. 구인 경우 반장축과 같습니다. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72 타원체. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84 타원체. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | 두 타원체가 동등한지 판단합니다.<br/>            ellipsoid A가 ellipsoid B와 동등하면, 두 타원체는 동일한 반장축과 역편평화를 가집니다. |
| [is_equivalent(other)](#is_equivalent_other_2) | 두 타원체가 동등한지 판단합니다.<br/>            ellipsoid A가 ellipsoid B와 동등하면, 두 타원체는 동일한 반장축과 역편평화를 가집니다. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

새 타원체를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 타원체의 이름. |
| semi_major_axis | double | 타원체의 반장축. |
| inverse_flattening | double | 타원체의 역편평화. 구형을 만들려면 0이어야 합니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 타원체의 식별자. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

두 타원체가 동등한지 판단합니다.<br/>            ellipsoid A가 ellipsoid B와 동등하면, 두 타원체는 동일한 반장축과 역편평화를 가집니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 첫 번째 타원체. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 두 번째 타원체. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 두 타원체가 동등한지 나타내는 bool 값. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

두 타원체가 동등한지 판단합니다.<br/>            ellipsoid A가 ellipsoid B와 동등하면, 두 타원체는 동일한 반장축과 역편평화를 가집니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 다른 타원체. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 두 타원체가 동등한지 나타내는 bool 값. |


