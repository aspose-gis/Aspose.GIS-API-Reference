---
title: "SpatialReferenceSystem.Validate"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystem 方法。确定此 SRS 是否有效"
type: docs
weight: 240
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/validate/
---
## SpatialReferenceSystem.Validate method

确定此 SRS 是否有效。

```csharp
public abstract bool Validate(out string errorMessage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 错误信息 | String& | 如果方法返回 `false`，则这是无效性的描述。 |

### 返回值

`true` 表示 SRS 有效，`false` 表示无效。

## 备注

有效的 SRS 必须具有有效的椭球体。- Geographic SRS 必须恰好有一个东西向（East/West）轴、恰好一个南北向（North/South）轴，以及可选的上下向（Up/Down）轴（当 Geographic SRS 是 2D 地理 SRS 与垂直 SRS 的组合时，会出现可选轴）。- Projected SRS 必须恰好有一个东西向（East/West）轴、恰好一个南北向（North/South）轴，以及可选的上下向（Up/Down）轴（当 Projected SRS 是 2D 地理 SRS 与垂直 SRS 的组合时，会出现可选轴）。- Geocentric SRS 必须恰好有一个东西向（East/West）轴、恰好一个南北向（North/South）轴和恰好一个其他（Other）轴。- Vertical SRS 必须恰好有一个上下向（Up/Down）轴。- Local SRS 必须至少有一个轴。轴的方向不计量。- Compound SRS 必须是有效的 Geographic/Projected 与有效的 Vertical SRS 的组合。

### 另见

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


