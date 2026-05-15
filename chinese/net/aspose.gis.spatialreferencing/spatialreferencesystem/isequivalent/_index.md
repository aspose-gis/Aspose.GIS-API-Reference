---
title: "SpatialReferenceSystem.IsEquivalent"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。检测此 SRS 是否等价于其他 SRS。"
type: docs
weight: 220
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/
---
## IsEquivalent(SpatialReferenceSystem)

检测此 SRS 是否等价于其他 SRS。

```csharp
public virtual bool IsEquivalent(SpatialReferenceSystem other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | SpatialReferenceSystem | 其他 SRS. |

### 返回值

bool 值，指示此 SRS 是否等价于其他 SRS.

### 另见

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)

---

## IsEquivalent(SpatialReferenceSystem, SpatialReferenceSystem)

确定两个 SRS 是否等价。等价 SRS 的相同坐标对应地球上的同一位置。等价 SRS 的某些参数可能不同，例如 [`Name`](../../identifiableobject/name/)。

```csharp
public static bool IsEquivalent(SpatialReferenceSystem srs1, SpatialReferenceSystem srs2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srs1 | SpatialReferenceSystem | 第一个 SRS。 |
| srs2 | SpatialReferenceSystem | 第二个 SRS。 |

### 返回值

布尔值，指示两个 SRS 是否等价。

### 另见

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


