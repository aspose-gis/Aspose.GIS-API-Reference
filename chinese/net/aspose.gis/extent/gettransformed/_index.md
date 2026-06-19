---
title: "Extent.GetTransformed"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Extent 方法。返回在指定 SpatialReferenceSystem 中包含此范围的新范围"
type: docs
weight: 150
url: /zh/net/aspose.gis/extent/gettransformed/
---
## Extent.GetTransformed method

返回在指定的 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) 中包含此范围的新范围。

```csharp
public Extent GetTransformed(SpatialReferenceSystem targetSrs)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | 要转换到的 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)。 |

### 返回值

此范围转换到指定 SRS 的结果。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| NotSupportedException | 不支持转换到提供的 SRS。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 转换失败。 |
| InvalidOperationException | 此范围的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 为 `null`。 |

### 另见

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


