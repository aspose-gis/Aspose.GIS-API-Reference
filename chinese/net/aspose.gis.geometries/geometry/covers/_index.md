---
title: "Geometry.Covers"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。确定此几何对象是否覆盖指定的几何对象"
type: docs
weight: 160
url: /zh/net/aspose.gis.geometries/geometry/covers/
---
## Geometry.Covers method

确定此几何体是否覆盖指定的几何体。

```csharp
public bool Covers(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 表示此几何对象“空间上覆盖”另一个几何对象。`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 的几何体空间参考系统不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法根据 DE-9IM 交叉矩阵测试一个几何对象是否覆盖另一个几何对象。如果一个几何对象包含另一个几何对象的每个点，则前者覆盖后者。此方法类似于 [`SpatiallyContains`](../../igeometry/spatiallycontains/)，但更常返回 `true`，因为它不区分内部点和边界点。因此，如果几何对象 A 位于几何对象 B 的边界上，[`SpatiallyContains`](../../igeometry/spatiallycontains/) 返回 `false`，而此方法返回 `true`。此方法等价于：

```csharp
this.Relate(other, "T*****FF*") || this.Relate(other, "*T****FF*") || this.Relate(other, "***T**FF*) || this.Relate(other, "***T*FF*");
```

### 另见

* method [SpatiallyContains](../../igeometry/spatiallycontains/)
* method [CoveredBy](../../igeometry/coveredby/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


