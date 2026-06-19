---
title: "IGeometry.ReplacePolygonsByLines"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。获取此几何对象的多边形，以线的形式表示。"
type: docs
weight: 300
url: /zh/net/aspose.gis.geometries/igeometry/replacepolygonsbylines/
---
## IGeometry.ReplacePolygonsByLines method

获取此几何体以线表示的多边形。

```csharp
public IGeometry ReplacePolygonsByLines()
```

### 返回值

一种没有多边形几何体的几何体。应用以下转换：多边形被线性化（转换为 LineString），MultiPolygon 被合并为 MultiLineString。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException |  |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


