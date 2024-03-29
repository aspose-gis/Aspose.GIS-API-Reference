---
title: Geometry.SpatiallyEquals
second_title: Aspose.GIS for .NET API 参考
description: Geometry 方法. 确定此几何图形在空间上是否等于指定的几何图形
type: docs
weight: 370
url: /zh/net/aspose.gis.geometries/geometry/spatiallyequals/
---
## Geometry.SpatiallyEquals method

确定此几何图形在空间上是否等于指定的几何图形。

```csharp
public bool SpatiallyEquals(IGeometry other)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | IGeometry | 一个几何。 |

### 返回值

`true`如果此几何图形“在空间上等于”指定的几何图形。`false`否则.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数是`null`. |
| ArgumentException | 其中一个几何图形无效，无法完成操作。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/)几何形状不等价。 您可以使用[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/)为了将几何图形转换为相同的 spatial 参考系统。 |

### 评论

此方法根据 DE-9IM 交集矩阵测试相等性。它不依赖于组件的 order （例如多边形内环的顺序）、Z 和 M 值。基本上，它测试 两个几何图形在投影到二维空间时占据相同的“空间”。 这个方法等同于： 有关 DE-9IM 的更多详细信息，请参阅 OpenGIS 简单功能规范。

```csharp
this.Relate(other, "T*F**FFF*");
```

### 也可以看看

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* 命名空间 [Aspose.Gis.Geometries](../../geometry/)
* 部件 [Aspose.GIS](../../../)


