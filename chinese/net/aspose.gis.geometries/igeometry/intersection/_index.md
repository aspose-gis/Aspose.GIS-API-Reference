---
title: "IGeometry.Intersection"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。构建此几何体与指定几何体的交集"
type: docs
weight: 260
url: /zh/net/aspose.gis.geometries/igeometry/intersection/
---
## IGeometry.Intersection method

构建此几何体与指定几何体的交集。

```csharp
public IGeometry Intersection(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 用于计算交集的几何体。 |

### 返回值

表示此几何体与参数交集的几何体。结果几何体包含同时存在于此几何体和参数中的点集合。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *other* 为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


