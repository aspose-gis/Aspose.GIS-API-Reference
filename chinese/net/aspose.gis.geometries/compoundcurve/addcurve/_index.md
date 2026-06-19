---
title: "CompoundCurve.AddCurve"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "CompoundCurve 方法。向此 CompoundCurve 的末尾添加曲线"
type: docs
weight: 120
url: /zh/net/aspose.gis.geometries/compoundcurve/addcurve/
---
## CompoundCurve.AddCurve method

向此 [`CompoundCurve`](../) 的末尾添加曲线。

```csharp
public void AddCurve(ICurve curve)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 曲线 | ICurve | 要添加的曲线。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 参数类型是 [`CompoundCurve`](../) 参数为空 [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/)（此几何体的）且参数的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 均不为 `null` 且两者不相等 |

### 另见

* interface [ICurve](../../icurve/)
* class [CompoundCurve](../)
* namespace [Aspose.Gis.Geometries](../../compoundcurve/)
* assembly [Aspose.GIS](../../../)


