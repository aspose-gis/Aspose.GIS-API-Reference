---
title: "SpatialReferenceSystem.CreateFromEpsg"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。基于指定的 EPSG 代码创建空间参考系统。"
type: docs
weight: 10
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromepsg/
---
## SpatialReferenceSystem.CreateFromEpsg method

基于指定的 EPSG 代码创建空间参考系统。

```csharp
public static SpatialReferenceSystem CreateFromEpsg(int epsg)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| epsg | Int32 | 空间参考系统的 EPSG 代码。 |

### 返回值

使用指定 EPSG 代码的新空间参考系统。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 参数不是正数。 |
| NotSupportedException | 指定的 EPSG 代码未知。 |

### 另见

* method [TryCreateFromEpsg](../trycreatefromepsg/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


