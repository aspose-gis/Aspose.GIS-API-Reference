---
title: "Geometry.GetConvexHull"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。计算此几何对象的凸包"
type: docs
weight: 230
url: /zh/net/aspose.gis.geometries/geometry/getconvexhull/
---
## Geometry.GetConvexHull method

计算此几何体的凸包。

```csharp
public IGeometry GetConvexHull()
```

### 返回值

表示此几何对象的凸包的几何对象。如果此几何对象没有点，则结果为 [`Null`](../null/)。如果只有一个点，则结果为该点。如果只有两个点，则结果为包含这些点的 [`ILineString`](../../ilinestring/)。如果有三个或更多点，则结果为表示围绕所有几何点的凸包的 [`ILinearRing`](../../ilinearring/)。

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


