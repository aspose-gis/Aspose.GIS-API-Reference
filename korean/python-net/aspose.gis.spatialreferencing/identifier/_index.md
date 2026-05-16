---
title: "Identifier 클래스"
type: docs
weight: 110
url: /ko/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | 권한 이름으로, [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/)을 제공한 것입니다. |
| authority_unique_identifier | string | r | 객체를 [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) 내에서 고유하게 표현하는 방법. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | 코드 <paramref name="epsgCode" />를 가진 EPSG 식별자를 나타내는 새 Identifier를 생성합니다. |
| [get_epsg_code()](#get_epsg_code__2) | 이 객체가 유효한 EPSG 식별자를 나타내는 경우(예: 권한 이름이 "EPSG"이고 권한 고유 식별자가 정수인 경우)-<br/>            해당 값을 반환합니다. 그렇지 않으면 -1을 반환합니다. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

코드 <paramref name="epsgCode" />를 가진 EPSG 식별자를 나타내는 새 Identifier를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| epsg_code | int | Epsg 코드. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 새 식별자와 [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" 및 [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" />.<br/>            <paramref name="epsgCode" />가 0보다 작으면 - <see langword="null" />를 반환; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

이 객체가 유효한 EPSG 식별자를 나타내는 경우(예: 권한 이름이 "EPSG"이고 권한 고유 식별자가 정수인 경우)-<br/>            해당 값을 반환합니다. 그렇지 않으면 -1을 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| int | 이 객체가 나타내는 EPSG 식별자. 이 객체가 EPSG 식별자를 나타내지 않으면 -1을 반환. |


