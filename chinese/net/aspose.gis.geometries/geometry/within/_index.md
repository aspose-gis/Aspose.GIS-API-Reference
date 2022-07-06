---
title: Within
second_title: Aspose.GIS for .NET API 参考
description: 确定此几何图形是否在指定范围内
type: docs
weight: 440
url: /zh/net/aspose.gis.geometries/geometry/within/
---
## Within(Extent) {#within}

确定此几何图形是否在指定范围内。

```csharp
public bool Within(Extent extent)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extent | Extent | 范围。 |

### 返回值

`true`如果此几何在范围内；`false`否则。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数是`null`。 |

### 也可以看看

* class [Extent](../../../aspose.gis/extent)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.Gis.Geometries](../../geometry)
* 部件 [Aspose.GIS](../../../)

---

## Within(IGeometry) {#within_1}

确定此几何是否在指定几何内。

```csharp
public bool Within(IGeometry other)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| other | IGeometry | 几何。 |

### 返回值

`true`如果这个几何体在“空间内”另一个几何体。`false`否则。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数是`null`。 |
| ArgumentException | 其中一个几何图形无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem)几何不等价。 您可以使用SpatialReferenceSystemTransformation将几何图形转换为相同的空间 参考系统。 |

### 评论

此方法根据 DE-9IM 相交矩阵测试一个几何体是否在另一个几何体中。 一个几何体在另一个几何体中，如果另一个几何体包含几何体和几何体的每个点 内部相交。&lt;cr /&gt; 此方法等效to: 有关 DE-9IM 和“空间内”关系的更多详细信息，请参阅 OpenGIS 简单功能规范。

```csharp
this.Relate(other, "T*F**F***");
```

### 也可以看看

* method [CoveredBy](../../igeometry/coveredby)
* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* 命名空间 [Aspose.Gis.Geometries](../../geometry)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->