---
title: "SpatialReferenceSystem.CreateVertical"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。创建垂直 SRS"
type: docs
weight: 390
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createvertical/
---
## SpatialReferenceSystem.CreateVertical method

创建垂直 SRS。

```csharp
public static VerticalSpatialReferenceSystem CreateVertical(string name, 
    VerticalDatum verticalDatum, Unit verticalUnit = null, Axis verticalAxis = null, 
    Identifier identifier = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | SRS 的名称。如果为 `null`。 |
| verticalDatum | VerticalDatum | 在 SRS 中使用的基准面。 |
| verticalUnit | Unit | 在 SRS 中使用的单位。如果 `null`，将使用 [`Meter`](../../unit/meter/)。 |
| verticalAxis | 轴 | 在 SRS 中使用的轴，方向为 up 或 down。如果 `null`，将使用向上的轴。 |
| 标识符 | 标识符 | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。由您自行确保标识符与 SRS 参数的一致性。 |

### 返回值

新的垂直 SRS。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | *verticalAxis* 方向不是 up 或 down。 |
| ArgumentNullException | 某些必需的参数为 null。 |

### 另见

* class [VerticalSpatialReferenceSystem](../../verticalspatialreferencesystem/)
* class [VerticalDatum](../../verticaldatum/)
* class [Unit](../../unit/)
* class [Axis](../../axis/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


