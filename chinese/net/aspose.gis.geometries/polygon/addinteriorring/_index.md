---
title: "Polygon.AddInteriorRing"
second_title: "Aspose.GIS for .NET API 参考"
description: "Polygon 方法。添加内部环。"
type: docs
weight: 90
url: /zh/net/aspose.gis.geometries/polygon/addinteriorring/
---
## Polygon.AddInteriorRing method

添加内部环。

```csharp
public void AddInteriorRing(ILinearRing ring)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 环 | ILinearRing | 要添加的环。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此几何体的 [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 与参数的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 均不为 `null` 且彼此不相等。 |

### 另见

* interface [ILinearRing](../../ilinearring/)
* class [Polygon](../)
* namespace [Aspose.Gis.Geometries](../../polygon/)
* assembly [Aspose.GIS](../../../)


