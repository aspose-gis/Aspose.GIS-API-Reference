---
title: SpatialReferenceSystem.TryCreateFromEpsg
second_title: Aspose.GIS for .NET API 参考
description: SpatialReferenceSystem 方法. 根据指定的 EPSG 代码创建空间参考系统
type: docs
weight: 400
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/
---
## SpatialReferenceSystem.TryCreateFromEpsg method

根据指定的 EPSG 代码创建空间参考系统。

```csharp
public static bool TryCreateFromEpsg(int epsg, out SpatialReferenceSystem value)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| epsg | Int32 | 空间参考系统的 EPSG 代码。 |
| value | SpatialReferenceSystem& | 当此方法返回时`true` , 包含具有指定 EPSG 代码的 SRS；否则， 包含`null`. |

### 返回值

`true`如果指定的 EPSG 代码已知并且 SRS 已创建；`false`否则。

### 也可以看看

* method [CreateFromEpsg](../createfromepsg/)
* class [SpatialReferenceSystem](../)
* 命名空间 [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* 部件 [Aspose.GIS](../../../)


