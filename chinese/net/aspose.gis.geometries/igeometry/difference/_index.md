---
title: "IGeometry.Difference"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。从此几何体中减去指定几何体"
type: docs
weight: 170
url: /zh/net/aspose.gis.geometries/igeometry/difference/
---
## IGeometry.Difference method

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


