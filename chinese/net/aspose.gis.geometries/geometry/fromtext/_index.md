---
title: "Geometry.FromText"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。根据其 WellKnown Text 表示创建几何体"
type: docs
weight: 480
url: /zh/net/aspose.gis.geometries/geometry/fromtext/
---
## FromText(string) {#fromtext}

从其已知文本（Well-Known Text）表示创建几何体。

```csharp
public static IGeometry FromText(string wkt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wkt | String | 几何体的 Well-Known Text 表示。 |

### 返回值

由参数表示的几何体。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 null。 |
| NotSupportedException | 参数表示一种不受支持类型的几何体。 |
| FormatException | 参数不是有效的 Well-Known Text。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## FromText(string, SpatialReferenceSystem) {#fromtext_1}

从其已知文本（Well-Known Text）表示创建几何体。

```csharp
public static IGeometry FromText(string wkt, SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wkt | String | 几何体的 Well-Known Text 表示。 |
| spatialReferenceSystem | SpatialReferenceSystem | 要分配给几何体的空间参考系统。 |

### 返回值

由参数表示的几何体。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 null。 |
| NotSupportedException | 参数表示一种不受支持类型的几何体。 |
| FormatException | 参数不是有效的 Well-Known Text。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


