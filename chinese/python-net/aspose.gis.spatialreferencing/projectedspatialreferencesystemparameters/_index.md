---
title: "ProjectedSpatialReferenceSystemParameters 类"
type: docs
weight: 160
url: /zh/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | 轴的顺序。默认是 [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/)。 |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | 基础地理 SRS（投影应用的 SRS）。<br/>            您必须将此属性设置为非 <see langword="null" /> 值，以创建有效的 SRS，<br/>            此属性没有任何默认值。 |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 此 SRS 中使用的单位。默认是 [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)。 |
| 名称 | string | r/w | 投影 SRS 的名称。默认是 "Unnamed"。 |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | 投影方法的标识符。没有默认值，您可以将此参数设置为非 <see langword="null" /> 值，<br/>            如果您想为投影附加标识符。若这样做——您需要确保标识符在一致的投影方法中<br/>            名称（设置此属性时投影方法名称不会更改）。 |
| projection_method_name | string | r/w | 投影方法的名称。没有默认值，您必须将此参数设置为非 <see langword="null" /> 值，因为<br/>            没有投影名称的投影坐标参考系统是无用的。 |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述 X（水平）维度的轴。默认使用指向东的轴。 |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述 Y（垂直）维度的轴。默认使用指向北的轴。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | 向此 SRS 添加投影参数。如果已添加具有相同名称的参数，则更新它。 |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | 获取具有指定名称的投影参数。 |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

创建新实例。

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

向此 SRS 添加投影参数。如果已添加具有相同名称的参数，则更新它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parameter_name | string | 投影参数的名称。 |
| value | double | 参数的值。值的单位应为 [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            或者是 [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/)（取自 [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)）。 |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

获取具有指定名称的投影参数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parameter_name | string | 参数的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 投影参数值。 |


