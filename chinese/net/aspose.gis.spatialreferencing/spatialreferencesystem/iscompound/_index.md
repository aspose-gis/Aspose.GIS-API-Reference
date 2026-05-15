---
title: "SpatialReferenceSystem.IsCompound"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem property. 返回此 SRS 是否为复合的，即由两个 SRS 合并而成。以下在复合 SRS 中的 SRS 组合被视为有效：Geographic SRS  Vertical SRS 在此情况下复合 SRS 的类型为 Geographic。Projected SRS  Vertical SRS 在此情况下复合 SRS 的类型为 Projected。如果 SRS 的组合类型不同，复合 SRS 的类型将为 Unknown。"
type: docs
weight: 130
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/
---
## SpatialReferenceSystem.IsCompound property

返回此 SRS 是否为复合（两个 SRS 的联合）。在复合 SRS 中，以下 SRS 组合被视为有效：Geographic SRS + Vertical SRS，此时复合 SRS 的类型为 Geographic；Projected SRS + Vertical SRS，此时复合 SRS 的类型为 Projected。如果 SRS 组合不同，复合 SRS 的类型将为 Unknown。

```csharp
public virtual bool IsCompound { get; }
```

## 备注

在 WKT 中，这表示 COMPD_CS。

### 另见

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


