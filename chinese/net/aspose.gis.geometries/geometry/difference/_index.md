---
title: "Geometry.Difference"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。从此几何体中减去指定的几何体"
type: docs
weight: 180
url: /zh/net/aspose.gis.geometries/geometry/difference/
---
## Geometry.Difference method

从此几何体中减去指定的几何体。

```csharp
public IGeometry Difference(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 要减去的几何体。 |

### 返回值

表示此几何体与参数之间差异的几何体。结果几何体包含在此几何体中存在但在参数中不存在的点集。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *other* 为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


