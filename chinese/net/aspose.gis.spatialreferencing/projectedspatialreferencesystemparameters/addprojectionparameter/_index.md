---
title: "ProjectedSpatialReferenceSystemParameters.AddProjectionParameter"
second_title: "Aspose.GIS for .NET API 参考"
description: "ProjectedSpatialReferenceSystemParameters 方法。向此 SRS 添加投影参数。如果已经添加了同名参数，则更新它。"
type: docs
weight: 100
url: /zh/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/
---
## ProjectedSpatialReferenceSystemParameters.AddProjectionParameter method

向此 SRS 添加投影参数。如果已存在同名参数，则更新它。

```csharp
public void AddProjectionParameter(string parameterName, double value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameterName | String | 投影参数的名称。 |
| value | Double | 参数的值。值的单位应为 [`LinearUnit`](../linearunit/) 或 [`AngularUnit`](../../geographicspatialreferencesystem/angularunit/) 的 [`Base`](../base/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *parameterName* 为 null。 |

### 另见

* class [ProjectedSpatialReferenceSystemParameters](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projectedspatialreferencesystemparameters/)
* assembly [Aspose.GIS](../../../)


