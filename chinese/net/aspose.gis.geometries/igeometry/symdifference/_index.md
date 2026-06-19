---
title: "IGeometry.SymDifference"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。构建此几何对象与指定几何对象之间的对称差。"
type: docs
weight: 330
url: /zh/net/aspose.gis.geometries/igeometry/symdifference/
---
## IGeometry.SymDifference method

构建此几何体与指定几何体的对称差。

```csharp
public IGeometry SymDifference(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 用于计算对称差的几何。 |

### 返回值

表示此几何与参数的对称差的几何。结果几何包含出现在其中一个几何中但不同时出现在两个几何中的点集。

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


