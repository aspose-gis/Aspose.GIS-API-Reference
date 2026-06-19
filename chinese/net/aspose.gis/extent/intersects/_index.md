---
title: "Extent.Intersects"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Extent 方法。确定此范围是否与参数相交"
type: docs
weight: 190
url: /zh/net/aspose.gis/extent/intersects/
---
## Intersects(Extent) {#intersects}

确定此范围是否与参数相交。

```csharp
public bool Intersects(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 另一个范围。 |

### 返回值

值，指示此范围是否与参数相交。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此范围和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null` 且彼此不相等。 |

### 另见

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Intersects(IGeometry) {#intersects_1}

确定此范围是否与参数相交。

```csharp
public bool Intersects(IGeometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 用于测试相交的几何体 |

### 返回值

值，指示此范围是否与参数相交。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此范围和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null` 且彼此不相等。 |

### 另见

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


