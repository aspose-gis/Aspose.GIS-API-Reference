---
title: "SpatialReferenceSystem.CreateTransformationTo"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。创建从此 SpatialReferenceSystem 到另一个 SpatialReferenceSystem 的转换"
type: docs
weight: 180
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/
---
## SpatialReferenceSystem.CreateTransformationTo method

创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。

```csharp
public SpatialReferenceSystemTransformation CreateTransformationTo(SpatialReferenceSystem targetSrs)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | 另一个 `SpatialReferenceSystem`。 |

### 返回值

从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 不支持此 `SpatialReferenceSystem` 与参数之间的转换。这可能是因为某个投影不受支持，或某个系统是 [`VerticalSpatialReferenceSystem`](../../verticalspatialreferencesystem/) 或 [`LocalSpatialReferenceSystem`](../../localspatialreferencesystem/)。 |
| [TransformationException](../../transformationexception/) | 由于 `SpatialReferenceSystem` 中的参数错误，转换创建失败。 |

### 另见

* method [TryCreateTransformationTo](../trycreatetransformationto/)
* class [SpatialReferenceSystemTransformation](../../spatialreferencesystemtransformation/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


