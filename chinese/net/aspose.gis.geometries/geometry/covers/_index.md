---
title: Covers
second_title: Aspose.GIS for .NET API 参考
description: 确定此几何是否覆盖指定几何
type: docs
weight: 160
url: /zh/net/aspose.gis.geometries/geometry/covers/
---
## Geometry.Covers method

确定此几何是否覆盖指定几何。

```csharp
public bool Covers(IGeometry other)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | IGeometry | 几何。 |

### 返回值

`true`如果此几何“空间覆盖”另一个几何。`false`否则。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数是`null`。 |
| ArgumentException | 其中一个几何图形无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem)几何不等价。 您可以使用SpatialReferenceSystemTransformation将几何图形转换为相同的空间 参考系统。 |

### 评论

此方法根据 DE-9IM 相交矩阵测试一个几何图形是否覆盖另一个几何图形。 如果几何包含另一个几何的每个点，则一个几何覆盖另一个几何。 此方法类似于[`SpatiallyContains`](../../igeometry/spatiallycontains)，但返回`true`更常见的是 因为它不区分内部点和边界点。因此，如果几何 A 位于 几何 B 的边界上，则IGeometry)返回`false`, 而这个方法返回`true`.&lt;cr /&gt; 这个方法等价于:

```csharp
this.Relate(other, "T*****FF*") || this.Relate(other, "*T****FF*") || this.Relate(other, "***T**FF*) || this.Relate(other, "***T*FF*");
```

### 也可以看看

* method [CoveredBy](../../igeometry/coveredby)
* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.Gis.Geometries](../../geometry)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->