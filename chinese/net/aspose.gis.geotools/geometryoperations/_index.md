---
title: "GeometryOperations 类"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.GeoTools.GeometryOperations 类。几何操作类提供了用于几何体的额外地理处理算法"
type: docs
weight: 2490
url: /zh/net/aspose.gis.geotools/geometryoperations/
---
## GeometryOperations class

几何操作类为几何提供了额外的地理处理算法。

```csharp
public static class GeometryOperations
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [BuildCenterline](../../aspose.gis.geotools/geometryoperations/buildcenterline/#buildcenterline_1)(IEnumerable&lt;Point&gt;) | 为点集合（站点）构建中心线图 |
| static [BuildCenterline](../../aspose.gis.geotools/geometryoperations/buildcenterline/#buildcenterline)(Polygon) | 为多边形构建中心线图 |
| static [CloseLinearRing](../../aspose.gis.geotools/geometryoperations/closelinearring/)(IGeometry) | 如果需要，则闭合环中的几何段。 |
| static [CreateMidpoints](../../aspose.gis.geotools/geometryoperations/createmidpoints/)(IGeometry) | 通过在每段的中间添加新点来创建中点。 |
| static [DeleteNearPoints](../../aspose.gis.geotools/geometryoperations/deletenearpoints/)(IGeometry, NearPointsCleanerOptions) | 删除彼此过于接近的点。 |
| static [ExtractGeometryCollection](../../aspose.gis.geotools/geometryoperations/extractgeometrycollection/)(VectorLayer) | 从图层中提取几何集合 |
| static [GetCenterlineLength](../../aspose.gis.geotools/geometryoperations/getcenterlinelength/#getcenterlinelength_1)(IEnumerable&lt;Point&gt;) | 获取中心线长度 |
| static [GetCenterlineLength](../../aspose.gis.geotools/geometryoperations/getcenterlinelength/#getcenterlinelength)(Polygon) | 获取中心线长度 |
| static [MakeVoronoiGraph](../../aspose.gis.geotools/geometryoperations/makevoronoigraph/)(IEnumerable&lt;IPoint&gt;) | 为点集合（站点）构建 "Voronoi" 图 |
| static [OrderGeometryCollection](../../aspose.gis.geotools/geometryoperations/ordergeometrycollection/)(IGeometry) | 按类型将几何集合排序为四个集合（点、线、多边形和其他类型） |
| static [SimplifySegments](../../aspose.gis.geotools/geometryoperations/simplifysegments/)(IGeometry, SimplifySegmentsOptions) | 删除位于同一段上的点。 |

## 备注

其他算法可在 [`Geometry`](../../aspose.gis.geometries/geometry/) 的方法中找到。

### 另见

* namespace [Aspose.Gis.GeoTools](../../aspose.gis.geotools/)
* assembly [Aspose.GIS](../../)


