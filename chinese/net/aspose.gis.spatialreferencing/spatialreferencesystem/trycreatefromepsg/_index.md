---
title: "SpatialReferenceSystem.TryCreateFromEpsg"
second_title: "Aspose.GIS for .NET API 参考"
description: "SpatialReferenceSystem 方法。基于指定的 EPSG 代码创建空间参考系统。"
type: docs
weight: 400
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/
---
## SpatialReferenceSystem.TryCreateFromEpsg method

基于指定的 EPSG 代码创建空间参考系统。

```csharp
public static bool TryCreateFromEpsg(int epsg, out SpatialReferenceSystem value)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| epsg | Int32 | 空间参考系统的 EPSG 代码。 |
| 值 | SpatialReferenceSystem& | 当此方法返回 `true` 时，包含具有指定 EPSG 代码的 SRS；否则，包含 `null`。 |

### 返回值

`true` 表示已知指定的 EPSG 代码并已创建 SRS；`false` 表示否则。

### 另见

* method [CreateFromEpsg](../createfromepsg/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


