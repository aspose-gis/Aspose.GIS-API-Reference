---
title: "接口 IGeometryCollection"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Geometries.IGeometryCollection 接口。IGeometryCollection 是一种 IGeometry，它是一个或多个几何体的集合"
type: docs
weight: 2790
url: /zh/net/aspose.gis.geometries/igeometrycollection/
---
## IGeometryCollection interface

`IGeometryCollection` 是一个 [`IGeometry`](../igeometry/)，它是一个或多个几何体的集合。

```csharp
public interface IGeometryCollection : IEnumerable<IGeometry>, IEquatable<IGeometryCollection>, 
    IGeometry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.geometries/igeometrycollection/count/) { get; } | 获取此集合中几何体的数量。 |
| [Item](../../aspose.gis.geometries/igeometrycollection/item/) { get; } | 获取指定索引处的 [`IGeometry`](../igeometry/)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetPointOnSurface](../../aspose.gis.geometries/igeometrycollection/getpointonsurface/)() | 查找一个保证位于此集合中某个表面的点。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometrycollection/replacepolygonsbylines/)() | 获取此几何体以线表示的多边形。 |
| [ToEditable](../../aspose.gis.geometries/igeometrycollection/toeditable/)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry/#tolineargeometry)() | 使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry/#tolineargeometry_1)(double) | 使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |

### 另见

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


