---
title: "Geometry.Intersects"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。确定此几何是否与指定范围相交"
type: docs
weight: 280
url: /zh/net/aspose.gis.geometries/geometry/intersects/
---
## Intersects(Extent) {#intersects}

确定此几何体是否与指定范围相交。

```csharp
public bool Intersects(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 该范围。 |

### 返回值

`true` 如果此几何与范围相交；`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* method [Intersects](../../../aspose.gis/extent/intersects/)
* class [Extent](../../../aspose.gis/extent/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## Intersects(IGeometry) {#intersects_1}

确定此几何体与指定几何体是否相交。

```csharp
public bool Intersects(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何 "空间相交" 另一个几何。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法等价于：

```csharp
!this.Disjoint(other);
```

这是 [`Disjoint`](../../igeometry/disjoint/) 的否定。请参阅 [`Disjoint`](../../igeometry/disjoint/) 获取更多细节。

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


