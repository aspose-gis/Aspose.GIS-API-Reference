---
title: "SpatialReferenceSystem.CreateLocal"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。创建本地空间参考系统"
type: docs
weight: 370
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/
---
## SpatialReferenceSystem.CreateLocal method

创建本地空间参考系统。

```csharp
public static LocalSpatialReferenceSystem CreateLocal(string name, LocalDatum datum, Unit unit, 
    ICollection<Axis> axises, Identifier identifier = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 空间参考系统的名称。 |
| 基准 | LocalDatum | 在 SRS 中使用的基准面。 |
| 单位 | 单位 | 在 SRS 中使用的单位。 |
| 轴 | ICollection`1 | 在 SRS 中使用的轴。必须非空。 |
| 标识符 | 标识符 | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。由您自行确保标识符与 SRS 参数的一致性。 |

### 返回值

新的本地空间参考系统。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 必须至少有一个轴。 |
| InvalidOperationException | *axises* 为空。 |
| ArgumentNullException | 任何参数，除 *identifier* 外为 null。 |

### 另见

* class [LocalSpatialReferenceSystem](../../localspatialreferencesystem/)
* class [LocalDatum](../../localdatum/)
* class [Unit](../../unit/)
* class [Axis](../../axis/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


