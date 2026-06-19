---
title: "IGeometry.GetConvexHull"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。计算此几何体的凸包"
type: docs
weight: 220
url: /zh/net/aspose.gis.geometries/igeometry/getconvexhull/
---
## IGeometry.GetConvexHull method

计算此几何体的凸包。

```csharp
public IGeometry GetConvexHull()
```

### 返回值

一种表示此几何体凸包的几何体。如果此几何体没有点，则结果为[`Null`](../../geometry/null/)。如果此几何体只有一个点，则结果为该点。如果此几何体只有两个点，则结果为带有这些点的[`ILineString`](../../ilinestring/)。如果此几何体有三个或更多点，则结果为表示围绕所有几何点的凸包的[`ILinearRing`](../../ilinearring/)。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


