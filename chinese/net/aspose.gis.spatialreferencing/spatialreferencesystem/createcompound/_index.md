---
title: "SpatialReferenceSystem.CreateCompound"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystem 方法。创建复合 SRS"
type: docs
weight: 340
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/
---
## SpatialReferenceSystem.CreateCompound method

创建复合 SRS。

```csharp
public static CompoundSpatialReferenceSystem CreateCompound(string name, 
    SpatialReferenceSystem head, SpatialReferenceSystem tail, Identifier identifier = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | 字符串 | 新 SRS 的名称。 |
| 头部 | SpatialReferenceSystem | 新 SRS 的头部 SRS。 |
| 尾部 | SpatialReferenceSystem | 新 SRS 的尾部 SRS。 |
| 标识符 | 标识符 | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。由您自行确保标识符与 SRS 参数的一致性。 |

### 返回值

新的复合 SRS。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任何参数除 *identifier* 外为 `null`。 |
| InvalidOperationException | *head* 或 *tail* 本身是复合 SRS。 |

### 另见

* class [CompoundSpatialReferenceSystem](../../compoundspatialreferencesystem/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


