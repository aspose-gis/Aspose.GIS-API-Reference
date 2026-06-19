---
title: "LocalSpatialReferenceSystem.GetUnit"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "LocalSpatialReferenceSystem 方法。获取维度的单位"
type: docs
weight: 110
url: /zh/net/aspose.gis.spatialreferencing/localspatialreferencesystem/getunit/
---
## LocalSpatialReferenceSystem.GetUnit method

获取维度的 [`Unit`](../unit/)。

```csharp
public override Unit GetUnit(int dimension)
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
* class [LocalSpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../localspatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


