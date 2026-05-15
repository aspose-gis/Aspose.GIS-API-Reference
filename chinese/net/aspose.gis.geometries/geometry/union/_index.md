---
title: "Geometry.Union"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。将此几何与指定几何合并"
type: docs
weight: 440
url: /zh/net/aspose.gis.geometries/geometry/union/
---
## Geometry.Union method

合并此几何体和指定几何体。

```csharp
public IGeometry Union(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 用于合并的几何。 |

### 返回值

表示此几何与参数的并集的几何。结果几何包含出现在此几何或参数中的点集。

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


