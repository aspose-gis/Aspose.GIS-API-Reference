---
title: "Geometry.GetDistanceTo"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。计算此几何体与指定几何体之间的最小距离"
type: docs
weight: 240
url: /zh/net/aspose.gis.geometries/geometry/getdistanceto/
---
## Geometry.GetDistanceTo method

计算此几何体与指定几何体之间的最小距离。

```csharp
public double GetDistanceTo(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 用于查找距离的几何体。 |

### 返回值

如果两个几何体都不是 [`IsEmpty`](../isempty/) - 则返回几何体最近点之间的距离。如果至少有一个几何体为空，则返回 -1。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 的几何体空间参考系统不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


