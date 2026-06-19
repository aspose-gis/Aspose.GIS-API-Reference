---
title: "IGeometry.CoveredBy"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。确定此几何是否被指定几何覆盖"
type: docs
weight: 140
url: /zh/net/aspose.gis.geometries/igeometry/coveredby/
---
## IGeometry.CoveredBy method

确定此几何体是否被指定的几何体覆盖。

```csharp
public bool CoveredBy(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 表示此几何“空间上被”另一个几何覆盖；`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法根据 DE-9IM 相交矩阵测试一个几何是否被另一个几何覆盖。此方法等价于：

```csharp
other.Covers(this);
```

### 另见

* method [SpatiallyContains](../spatiallycontains/)
* method [Covers](../covers/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


