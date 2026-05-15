---
title: "SpatialReferenceSystemTransformation.SpatialReferenceSystemTransformation"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystemTransformation 构造函数。创建新实例。"
type: docs
weight: 10
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/spatialreferencesystemtransformation/
---
## SpatialReferenceSystemTransformation constructor

创建新实例。

```csharp
public SpatialReferenceSystemTransformation(SpatialReferenceSystem sourceSrs, 
    SpatialReferenceSystem targetSrs)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceSrs | SpatialReferenceSystem | 源 [`SpatialReferenceSystem`](../../spatialreferencesystem/)。 |
| targetSrs | SpatialReferenceSystem | 目标 [`SpatialReferenceSystem`](../../spatialreferencesystem/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 不支持给定空间参考系统之间的转换。 |
| [TransformationException](../../transformationexception/) | 由于 SRS 中的参数错误，转换创建失败。 |

### 另见

* class [SpatialReferenceSystem](../../spatialreferencesystem/)
* class [SpatialReferenceSystemTransformation](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystemtransformation/)
* assembly [Aspose.GIS](../../../)


