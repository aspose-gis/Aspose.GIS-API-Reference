---
title: "Geometry.Overlaps"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。确定此几何体是否与指定几何体重叠"
type: docs
weight: 290
url: /zh/net/aspose.gis.geometries/geometry/overlaps/
---
## Geometry.Overlaps method

确定此几何体是否与指定几何体重叠。

```csharp
public bool Overlaps(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 表示此几何体“空间上重叠”另一个几何体。`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 的几何体空间参考系统不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试几何体在 DE-9IM 交叉矩阵意义上是否重叠。如果两个几何体共享部分但不是全部内部点，并且几何体的交集具有与几何体本身相同的维度，则它们重叠。对于两个 Point 几何体或两个 Surface 几何体，此方法等价于：

```csharp
this.Relate(other, "T*T***T**");
```

对于两个 Line 几何体，此方法等价于：

```csharp
this.Relate(other, "1*T***T**");
```

对于维度不相等的两个几何体（[`Dimension`](../../igeometry/dimension/)），此方法始终返回 `false`。有关 DE-9IM 和 “空间上重叠” 关系的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


