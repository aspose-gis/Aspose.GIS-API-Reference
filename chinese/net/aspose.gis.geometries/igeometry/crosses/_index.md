---
title: "IGeometry.Crosses"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。确定此几何体与指定几何体是否相交"
type: docs
weight: 160
url: /zh/net/aspose.gis.geometries/igeometry/crosses/
---
## IGeometry.Crosses method

确定此几何体与指定几何体是否相交。

```csharp
public bool Crosses(IGeometry other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |

### 返回值

`true` 如果此几何体“在空间上相交”另一个几何体。`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) 的几何体不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法测试几何体在 DE-9IM 交叉矩阵方面是否相交。若两个几何体共享部分但不是全部内部点，且交叉的维度小于至少一个几何体的维度，则它们相交。即：两个 [`LineString`](../../linestring/) 相交时会形成字母 'X'，[`LineString`](../../linestring/) 与 [`Polygon`](../../polygon/) 相交时，若该 LineString 穿过 Polygon 的内部。有关 DE-9IM 以及 "在空间上相交" 关系的更多细节，请参阅 OpenGIS Simple Features Specification。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


