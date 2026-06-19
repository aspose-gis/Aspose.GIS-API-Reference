---
title: "Geometry.Disjoint"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。确定此几何体是否与指定几何体不相交"
type: docs
weight: 190
url: /zh/net/aspose.gis.geometries/geometry/disjoint/
---
## Geometry.Disjoint method

确定此几何体是否与指定的几何体不相交。

```csharp
public bool Disjoint(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体在空间上与另一个几何体不相交。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 的几何体空间参考系统不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试几何体在 DE-9IM 交叉矩阵意义上是否不相交。基本上，它测试两个几何体没有公共点。此方法等价于：

```csharp
this.Relate(other, "FF*FF****");
```

有关 DE-9IM 的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* method [Intersects](../../igeometry/intersects/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


