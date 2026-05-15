---
title: "IGeometry.SpatiallyEquals"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。确定此几何对象是否在空间上等于指定的几何对象。"
type: docs
weight: 320
url: /zh/net/aspose.gis.geometries/igeometry/spatiallyequals/
---
## IGeometry.SpatiallyEquals method

确定此几何体在空间上是否等于指定的几何体。

```csharp
public bool SpatiallyEquals(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 表示此几何对象在空间上等于指定的几何对象。`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法根据 DE-9IM 交叉矩阵测试相等性。它不依赖于组件的顺序（例如多边形内部环的顺序）、Z 和 M 值。基本上，它测试两个几何对象在投影到二维空间时是否占据相同的“空间”。此方法等价于：

```csharp
this.Relate(other, "T*F**FFF*");
```

有关 DE-9IM 的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


