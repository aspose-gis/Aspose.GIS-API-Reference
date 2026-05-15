---
title: "Projection.GetParameterValue"
second_title: "Aspose.GIS for .NET API 参考"
description: "Projection 方法。获取此投影中具有指定名称的参数"
type: docs
weight: 40
url: /zh/net/aspose.gis.spatialreferencing/projection/getparametervalue/
---
## Projection.GetParameterValue method

获取此投影中具有指定名称的参数。

```csharp
public double GetParameterValue(string name, ParameterType type = ParameterType.Other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 参数的名称。 |
| type | ParameterType | 参数的类型。定义将被取消的单位因子：如果类型是 Linear，则会取消 [`LinearParametersUnit`](../linearparametersunit/) 并且结果以米为单位。如果类型是 Angular，则会取消 [`AngularParametersUnit`](../angularparametersunit/) 并且结果以弧度为单位。如果类型是 Other，参数值将以原样返回。 |

### 返回值

具有指定名称的参数。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 null。 |
| InvalidOperationException | 不存在具有此名称的参数。 |

### 另见

* enum [ParameterType](../../parametertype/)
* class [Projection](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projection/)
* assembly [Aspose.GIS](../../../)


