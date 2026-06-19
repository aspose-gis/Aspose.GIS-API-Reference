---
title: "SpatialReferenceSystem.GetAxis"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystem 方法。获取描述维度的轴"
type: docs
weight: 200
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/
---
## SpatialReferenceSystem.GetAxis method

获取 [`Axis`](../../axis/)，它描述维度。

```csharp
public abstract Axis GetAxis(int dimension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 维度 | Int32 | 维度的数量。 |

### 返回值

描述维度的 Axis。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *dimension* 小于 0 或大于或等于 [`DimensionsCount`](../dimensionscount/) |

### 另见

* class [Axis](../../axis/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


