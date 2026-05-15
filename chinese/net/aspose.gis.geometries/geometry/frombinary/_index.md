---
title: "Geometry.FromBinary"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。从其 WellKnown Binary 表示创建几何体"
type: docs
weight: 470
url: /zh/net/aspose.gis.geometries/geometry/frombinary/
---
## FromBinary(byte[]) {#frombinary}

从其已知二进制（Well-Known Binary）表示创建几何体。

```csharp
public static IGeometry FromBinary(byte[] wkb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wkb | Byte[] | 几何体的 Well-Known Binary 表示。 |

### 返回值

由参数表示的几何体。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 null。 |
| NotSupportedException | 参数表示一种不受支持类型的几何体。 |
| FormatException | 参数不是有效的 Well-Known Binary。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## FromBinary(byte[], SpatialReferenceSystem) {#frombinary_1}

从其已知二进制（Well-Known Binary）表示创建几何体。

```csharp
public static IGeometry FromBinary(byte[] wkb, SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wkb | Byte[] | 几何体的 Well-Known Binary 表示。 |
| spatialReferenceSystem | SpatialReferenceSystem | 要分配给几何体的空间参考系统。 |

### 返回值

由参数表示的几何体。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 null。 |
| NotSupportedException | 参数表示一种不受支持类型的几何体。 |
| FormatException | 参数不是有效的 Well-Known Binary。 |

## 备注

如果几何体后面有额外的字节，将抛出 FormatException 异常。

### 另见

* interface [IGeometry](../../igeometry/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


