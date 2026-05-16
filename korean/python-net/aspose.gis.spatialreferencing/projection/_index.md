---
title: "Projection 클래스"
type: docs
weight: 170
url: /ko/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 각도 매개변수에 사용되는 단위. |
| epsg_code | int | r | 이 객체의 식별자가 EPSG 식별자인 경우 - 코드를 반환합니다. 그렇지 않으면 -1을 반환합니다. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 이 식별 가능한 객체의 식별자입니다. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 선형 매개변수에 사용되는 단위. |
| 이름 | string | r | 이 객체의 이름입니다. |
| parameters_names | System.Collections.Generic.IList<string> | r | 이 투영에 제공된 매개변수 이름들의 열거 가능한 컬렉션을 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | 이 투영의 지정된 이름을 가진 매개변수를 가져옵니다. |
| [is_equivalent(other)](#is_equivalent_other_2) | 두 투영이 동등한지 판단합니다. 동등한 투영은 (longitude, latitude)를 (x, y)와 동일한 방식으로 매핑합니다.<br/>            같은 방식으로. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | 이 투영의 지정된 이름을 가진 매개변수를 가져옵니다. 해당 매개변수가 없으면 <see langword="null" />를 반환합니다. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

이 투영의 지정된 이름을 가진 매개변수를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 매개변수의 이름입니다. |
