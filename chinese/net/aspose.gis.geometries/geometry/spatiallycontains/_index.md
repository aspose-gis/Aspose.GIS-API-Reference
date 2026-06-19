---
title: "Geometry.SpatiallyContains"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。确定此几何体是否在空间上包含指定的几何体"
type: docs
weight: 360
url: /zh/net/aspose.gis.geometries/geometry/spatiallycontains/
---
## Geometry.SpatiallyContains method

确定此几何体在空间上是否包含指定的几何体。

```csharp
public bool SpatiallyContains(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体在空间上“包含”另一个几何体。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 的几何体空间参考系统不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试一个几何体是否在 DE-9IM 交叉矩阵意义上包含另一个几何体。此方法等价于：

```csharp
other.Within(this);
```

### 另见

* method [Within](../../igeometry/within/)
* method [Covers](../../igeometry/covers/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


