---
title: "IGeometryCollection.ReplacePolygonsByLines"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometryCollection 方法。获取此几何体中以线表示的多边形"
type: docs
weight: 40
url: /zh/net/aspose.gis.geometries/igeometrycollection/replacepolygonsbylines/
---
## IGeometryCollection.ReplacePolygonsByLines method

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

* interface [IGeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../igeometrycollection/)
* assembly [Aspose.GIS](../../../)


