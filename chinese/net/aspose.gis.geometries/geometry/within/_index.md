---
title: "Geometry.Within"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。确定此几何体是否位于指定范围内"
type: docs
weight: 450
url: /zh/net/aspose.gis.geometries/geometry/within/
---
## Within(Extent) {#within}

确定此几何体是否位于指定范围内。

```csharp
public bool Within(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 该范围。 |

### 返回值

`true` 如果此几何体位于范围内；`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* method [Contains](../../../aspose.gis/extent/contains/)
* class [Extent](../../../aspose.gis/extent/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

确定此几何体是否位于指定几何体内部。

```csharp
public bool Within(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体“空间上位于”另一个几何体内。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法根据 DE-9IM 相交矩阵测试一个几何体是否位于另一个几何体内部。如果另一个几何体包含该几何体的每个点且几何体内部相交，则该几何体位于另一个几何体内部。此方法等价于：

```csharp
this.Relate(other, "T*F**F***");
```

有关 DE-9IM 和“空间上位于”关系的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* method [SpatiallyContains](../../igeometry/spatiallycontains/)
* method [CoveredBy](../../igeometry/coveredby/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


