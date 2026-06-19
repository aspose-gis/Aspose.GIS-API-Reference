---
title: "SpatialReferenceSystem.TryCreateTransformationTo"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystem 方法。创建从此 SpatialReferenceSystem 到另一个 SpatialReferenceSystem 的转换"
type: docs
weight: 230
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/
---
## SpatialReferenceSystem.TryCreateTransformationTo method

创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。

```csharp
public bool TryCreateTransformationTo(SpatialReferenceSystem targetSrs, 
    out SpatialReferenceSystemTransformation value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | 另一个 `SpatialReferenceSystem`。 |
| 值 | SpatialReferenceSystemTransformation& | 当此方法返回 `true` 时，包含一个转换；否则，包含 `null`。 |

### 返回值

从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。

`true` 表示转换成功创建；`false` 表示未成功。

### 另见

* method [CreateTransformationTo](../createtransformationto/)
* class [SpatialReferenceSystemTransformation](../../spatialreferencesystemtransformation/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


