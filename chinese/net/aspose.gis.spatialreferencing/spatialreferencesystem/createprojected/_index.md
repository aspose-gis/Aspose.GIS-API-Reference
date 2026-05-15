---
title: "SpatialReferenceSystem.CreateProjected"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。根据自定义参数创建投影 SRS。"
type: docs
weight: 380
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createprojected/
---
## SpatialReferenceSystem.CreateProjected method

使用自定义参数创建投影 SRS。

```csharp
public static ProjectedSpatialReferenceSystem CreateProjected(
    ProjectedSpatialReferenceSystemParameters parameters, Identifier identifier = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 参数 | ProjectedSpatialReferenceSystemParameters | 用于创建的参数。 |
| 标识符 | 标识符 | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。由您自行确保标识符与 SRS 参数的一致性。 |

### 返回值

新的投影坐标参考系统。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 参数中的基础坐标参考系统为 `null`。参数中的投影方法为 `null`。 |

### 另见

* class [ProjectedSpatialReferenceSystem](../../projectedspatialreferencesystem/)
* class [ProjectedSpatialReferenceSystemParameters](../../projectedspatialreferencesystemparameters/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


