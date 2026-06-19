---
title: "类 GeometryCollection"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Geometries.GeometryCollection 类。GeometryCollection 是一种几何体，它是一个或多个几何体的集合"
type: docs
weight: 2710
url: /zh/net/aspose.gis.geometries/geometrycollection/
---
## GeometryCollection class

`GeometryCollection` 是一个 [`Geometry`](../geometry/) ，它是一个或多个几何体的集合。

```csharp
public class GeometryCollection : Geometry, IGeometryCollection
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GeometryCollection](geometrycollection/)() | 初始化 `GeometryCollection` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | 获取此 [`Geometry`](../geometry/) 的坐标维数。 |
| [Count](../../aspose.gis.geometries/geometrycollection/count/) { get; } | 获取此集合中几何体的数量。 |
| override [Dimension](../../aspose.gis.geometries/geometrycollection/dimension/) { get; } | 获取此 [`Geometry`](../geometry/) 的拓扑维度。如果集合为空，则返回 Point。 |
| override [GeometryType](../../aspose.gis.geometries/geometrycollection/geometrytype/) { get; } | 获取几何体的类型。 |
| override [HasCurveGeometry](../../aspose.gis.geometries/geometrycollection/hascurvegeometry/) { get; } | 获取一个值，指示此几何体是否为或包含曲线（非线性）几何体。 |
| override [HasM](../../aspose.gis.geometries/geometrycollection/hasm/) { get; set; } | 获取一个值，指示此实例是否具有 M 坐标。 |
| override [HasZ](../../aspose.gis.geometries/geometrycollection/hasz/) { get; set; } | 获取一个值，指示此实例是否具有 Z 坐标。 |
| override [IsEmpty](../../aspose.gis.geometries/geometrycollection/isempty/) { get; } | 获取一个值，指示此实例是否为空。 |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | 获取一个值，指示从 SFA 角度看此实例是否为简单。 |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | 获取一个值，指示此实例是否有效。 |
| [Item](../../aspose.gis.geometries/geometrycollection/item/) { get; } | 获取指定索引处的 [`IGeometry`](../igeometry/)。 |
| override [SpatialReferenceSystem](../../aspose.gis.geometries/geometrycollection/spatialreferencesystem/) { get; set; } | 获取此实例的 SpatialReferenceSystem。此属性可以为 `null`，表示 SpatialReferenceSystem 未知。分配新的 SpatialReferenceSystem 不会执行任何坐标转换，只会更改引用。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.geometries/geometrycollection/add/)(IGeometry) | 将指定的几何体添加到集合中。 |
| [AddRange](../../aspose.gis.geometries/geometrycollection/addrange/)(IEnumerable&lt;IGeometry&gt;) | 将指定的多个几何体添加到集合中。 |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | 将此几何体转换为其 Well-Known Text 表示。 |
| override [Clone](../../aspose.gis.geometries/geometrycollection/clone/)() | 克隆此实例。 |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | 确定此几何体是否被指定的几何体覆盖。 |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | 确定此几何体是否覆盖指定的几何体。 |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | 确定此几何体与指定的几何体是否相交。 |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | 从此几何体中减去指定的几何体。 |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | 确定此几何体是否与指定的几何体不相交。 |
| [Equals](../../aspose.gis.geometries/geometrycollection/equals/#equals)(IGeometryCollection) | 指示当前对象是否等于同类型的另一个对象。 |
| override [Equals](../../aspose.gis.geometries/geometrycollection/equals/#equals_1)(object) | 确定指定的对象是否等于当前对象。 |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | 计算此几何体的面积。 |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | 计算此几何体周围的缓冲区。 |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | 计算此几何体的质心。 |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | 计算此几何体的凸包。 |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | 计算此几何体与指定几何体之间的最小距离。 |
| [GetEnumerator](../../aspose.gis.geometries/geometrycollection/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | 计算并返回此几何体的边界范围。 |
| override [GetHashCode](../../aspose.gis.geometries/geometrycollection/gethashcode/)() | 用作默认的哈希函数。 |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | 计算此几何体的长度。 |
| [GetPointOnSurface](../../aspose.gis.geometries/geometrycollection/getpointonsurface/)() | 查找一个保证位于此集合中某个表面的点。 |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | 构建此几何体与指定几何体的交集。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | 确定此几何体是否与指定范围相交。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | 确定此几何体和指定几何体是否相交。 |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | 确定此几何体是否与指定几何体重叠。 |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | 确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。 |
| [RemoveAt](../../aspose.gis.geometries/geometrycollection/removeat/)(int) | 从集合中移除指定的几何对象。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometrycollection/replacepolygonsbylines/#replacepolygonsbylines_1)() | 获取以此几何对象的线表示的多边形。（2 种方法） |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | 将 M 坐标四舍五入到指定的小数位数。 |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | 将 X 和 Y 坐标四舍五入到指定的小数位数。 |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | 将 Z 坐标四舍五入到指定的小数位数。 |
| override [SetEmpty](../../aspose.gis.geometries/geometrycollection/setempty/)() | 将此 [`Geometry`](../geometry/) 设为空。 |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | 确定此几何体在空间上是否包含指定的几何体。 |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | 确定此几何体在空间上是否等于指定的几何体。 |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | 构建此几何体与指定几何体的对称差。 |
| [ToEditable](../../aspose.gis.geometries/geometrycollection/toeditable/#toeditable_1)() | 获取此几何体的可编辑副本。（2 种方法） |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/geometrycollection/tolineargeometry/#tolineargeometry_2)() | 使用默认的 `tolerance` 获取此几何体的近似或等效的非曲线版本。（2 个方法） |
| [ToLinearGeometry](../../aspose.gis.geometries/geometrycollection/tolineargeometry/#tolineargeometry_3)(double) | 使用指定的 `tolerance` 获取此几何体的近似或等效的非曲线版本。（2 个方法） |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | 返回表示当前对象的字符串。 |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | 将此几何体转换为 Svg 表示。 |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | 确定此几何体与指定几何体是否相接。 |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | 合并此几何体和指定几何体。 |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | 确定此几何体是否位于指定的范围内。 |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | 确定此几何体是否位于指定的几何体内。 |
| [operator ==](../../aspose.gis.geometries/geometrycollection/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.gis.geometries/geometrycollection/op_inequality/) | 实现运算符 !=。 |

### 另见

* class [Geometry](../geometry/)
* interface [IGeometryCollection](../igeometrycollection/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


