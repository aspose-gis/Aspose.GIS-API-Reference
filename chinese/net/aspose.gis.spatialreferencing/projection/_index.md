---
title: "类 Projection"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.Projection 类。表示一种带参数的投影方法，可将经度纬度转换为 x y。"
type: docs
weight: 4690
url: /zh/net/aspose.gis.spatialreferencing/projection/
---
## Projection class

表示一种带有参数的投影方法，将 (经度, 纬度) 转换为 (x, y)。

```csharp
public class Projection : IdentifiableObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AngularParametersUnit](../../aspose.gis.spatialreferencing/projection/angularparametersunit/) { get; } | 用于角度参数的单位。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| [LinearParametersUnit](../../aspose.gis.spatialreferencing/projection/linearparametersunit/) { get; } | 用于线性参数的单位。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| [ParametersNames](../../aspose.gis.spatialreferencing/projection/parametersnames/) { get; } | 获取分配给此投影的参数名称的可枚举集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetParameterValue](../../aspose.gis.spatialreferencing/projection/getparametervalue/)(string, ParameterType) | 获取此投影中指定名称的参数。 |
| [IsEquivalent](../../aspose.gis.spatialreferencing/projection/isequivalent/)(Projection) | 确定两个投影是否等价。等价的投影以相同方式将 (longitude, latitude) 映射到 (x, y)。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| [TryGetParameterValue](../../aspose.gis.spatialreferencing/projection/trygetparametervalue/)(string, ParameterType) | 获取此投影中指定名称的参数。如果不存在此类参数，则返回 `null`。 |

### 另见

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


