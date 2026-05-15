---
title: "IGeometry.Overlaps"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。确定此几何是否与指定几何重叠"
type: docs
weight: 280
url: /zh/net/aspose.gis.geometries/igeometry/overlaps/
---
## IGeometry.Overlaps method

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试几何体在 DE-9IM 交叉矩阵意义上是否重叠。当两个几何体共享部分但不是全部内部点且它们的交集具有与几何体本身相同的维度时，即视为重叠。对于两个 Point 几何体或两个 Surface 几何体，此方法等价于：

```csharp
this.Relate(other, "T*T***T**");
```

对于两个 Line 几何体，此方法等价于：

```csharp
this.Relate(other, "1*T***T**");
```

对于两个 [`Dimension`](../dimension/) 不相等的几何体，此方法始终返回 `false`。有关 DE-9IM 和 "spatially overlaps" 关系的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


