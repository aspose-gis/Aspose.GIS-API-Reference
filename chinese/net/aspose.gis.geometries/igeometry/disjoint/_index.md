---
title: "IGeometry.Disjoint"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。确定此几何体是否与指定几何体不相交"
type: docs
weight: 180
url: /zh/net/aspose.gis.geometries/igeometry/disjoint/
---
## IGeometry.Disjoint method

确定此几何体是否与指定的几何体不相交。

```csharp
public bool Disjoint(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体是 \"空间上不相交\" 另一个几何体。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试在 DE-9IM 交叉矩阵的意义下，几何体是否不相交。基本上，它测试两个几何体没有公共点。此方法等价于：

```csharp
this.Relate(other, "FF*FF****");
```

有关 DE-9IM 的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* method [Intersects](../intersects/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


