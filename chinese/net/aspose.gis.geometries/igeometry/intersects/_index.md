---
title: "IGeometry.Intersects"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。确定此几何是否与指定范围相交"
type: docs
weight: 270
url: /zh/net/aspose.gis.geometries/igeometry/intersects/
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

`true` 表示此几何与范围相交；`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* method [Intersects](../../../aspose.gis/extent/intersects/)
* class [Extent](../../../aspose.gis/extent/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## Intersects(IGeometry) {#intersects_1}

确定此几何体和指定几何体是否相交。

```csharp
public bool Intersects(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 表示此几何“空间相交”另一个几何；`false` 表示否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法等价于：

```csharp
!this.Disjoint(other);
```

这是 [`Disjoint`](../disjoint/) 的否定。有关更多细节，请参阅 [`Disjoint`](../disjoint/)。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


