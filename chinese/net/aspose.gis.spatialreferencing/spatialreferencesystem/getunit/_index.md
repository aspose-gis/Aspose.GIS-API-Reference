---
title: "SpatialReferenceSystem.GetUnit"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。获取维度的单位。"
type: docs
weight: 210
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/getunit/
---
## SpatialReferenceSystem.GetUnit method

获取维度的 [`Unit`](../../unit/)。

```csharp
public abstract Unit GetUnit(int dimension)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 维度 | Int32 | 维度的数量。 |

### 返回值

维度的单位。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *dimension* 小于 0 或大于或等于 [`DimensionsCount`](../dimensionscount/) |

### 另见

* class [Unit](../../unit/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


