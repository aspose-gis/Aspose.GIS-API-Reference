---
title: "GeometryCollection.ReplacePolygonsByLines"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeometryCollection 方法。获取此几何体中以线表示的多边形"
type: docs
weight: 190
url: /zh/net/aspose.gis.geometries/geometrycollection/replacepolygonsbylines/
---
## GeometryCollection.ReplacePolygonsByLines method

获取此几何体中表示为线的多边形。

```csharp
public IGeometryCollection ReplacePolygonsByLines()
```

### 返回值

一种没有多边形几何体的几何体。应用以下转换：多边形被线性化（转换为 LineString），MultiPolygon 被合并为 MultiLineString。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException |  |

### 另见

* interface [IGeometryCollection](../../igeometrycollection/)
* class [GeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../geometrycollection/)
* assembly [Aspose.GIS](../../../)


