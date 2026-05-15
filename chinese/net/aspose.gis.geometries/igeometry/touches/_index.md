---
title: "IGeometry.Touches"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。确定此几何体与指定几何体是否相切"
type: docs
weight: 360
url: /zh/net/aspose.gis.geometries/igeometry/touches/
---
## IGeometry.Touches method

确定此几何体与指定几何体是否相接触。

```csharp
public bool Touches(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体"spatially touches"另一个几何体。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试几何体是否在 DE-9IM 相交矩阵的意义上相接。若两个几何体至少共享一个边界点且没有内部点，则它们相接。即：两个[`LineString`](../../linestring/)若共享端点但不共享线段，则相接；两个多边形若共享外环或内环的一部分，但其内部不重叠，则相接。此方法等价于：

```csharp
this.Relate(other, "FT*******") || this.Relate(other, "F**T*****") || this.Relate(other, "F***T****");
```

请参阅 OpenGIS Simple Features Specification 以获取有关 DE-9IM 和 "spatially touches" 关系的更多细节。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


