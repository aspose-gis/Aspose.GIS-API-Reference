---
title: "ProjectedSpatialReferenceSystemParameters 클래스"
type: docs
weight: 160
url: /ko/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | 축의 순서입니다. 기본값은 [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/)입니다. |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | 기본 지리적 SRS(투영이 적용되는 SRS).<br/>            유효한 SRS를 만들기 위해 이 속성을 <see langword="null" />이 아닌 값으로 반드시 설정해야 합니다,<br/>            이 속성에는 기본값이 없습니다. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 이 SRS에서 사용할 단위입니다. 기본값은 [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)입니다. |
| 이름 | string | r/w | 투영된 SRS의 이름입니다. 기본값은 "Unnamed"입니다. |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | 투영 방법의 식별자입니다. 기본값이 없으며, 이 매개변수를 <see langword="null" />이 아닌 값으로 설정할 수 있습니다,<br/>            투영에 식별자를 연결하려는 경우. 이렇게 할 경우 식별자가 일관된 투영 방법 이름에 포함되도록 보장해야 합니다<br/>            (이 속성을 설정해도 투영 방법 이름은 변경되지 않습니다). |
| projection_method_name | string | r/w | 투영 방법의 이름입니다. 기본값이 없으며 이 매개변수를 <see langword="null" /> 값이 아니도록 반드시 설정해야 합니다, 왜냐하면<br/>            투영 이름이 없는 투영 SRS는 쓸모가 없기 때문입니다. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | X(수평) 차원을 설명하는 축입니다. 기본값은 동쪽 방향의 축입니다. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Y(수직) 차원을 설명하는 축입니다. 기본값은 북쪽 방향의 축입니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | 이 SRS에 투영 매개변수를 추가합니다. 동일한 이름의 매개변수가 이미 추가된 경우 - 업데이트합니다. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | 지정된 이름의 투영 매개변수를 가져옵니다. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

새 인스턴스를 생성합니다.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

이 SRS에 투영 매개변수를 추가합니다. 동일한 이름의 매개변수가 이미 추가된 경우 - 업데이트합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parameter_name | string | 투영 매개변수의 이름입니다. |
| value | double | 매개변수의 값입니다. 값의 단위는 [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            또는 [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/)의 [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)에 있어야 합니다. |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

지정된 이름의 투영 매개변수를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| parameter_name | string | 매개변수의 이름입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 투영 매개변수 값입니다. |


