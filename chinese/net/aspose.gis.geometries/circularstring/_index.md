---
title: "类 CircularString"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Geometries.CircularString 类。一个在点之间进行圆形插值的多顶点曲线。"
type: docs
weight: 2660
url: /zh/net/aspose.gis.geometries/circularstring/
---
## CircularString class

一个在点之间具有圆形插值的多顶点曲线。

```csharp
public class CircularString : Curve, ICircularString
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CircularString](circularstring/#constructor)() | 初始化 `CircularString` 类的新实例。 |
| [CircularString](circularstring/#constructor_1)(ICircularString) | 初始化 `CircularString` 类的新实例。 |
| [CircularString](circularstring/#constructor_2)(IEnumerable&lt;IPoint&gt;) | 初始化 `CircularString` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | 获取此 [`Geometry`](../geometry/) 的坐标维度数量。 |
| [Count](../../aspose.gis.geometries/circularstring/count/) { get; } | 获取 `CircularString` 中的点数。 |
| [Dimension](../../aspose.gis.geometries/curve/dimension/) { get; } | 获取此 [`Geometry`](../geometry/) 的拓扑维度。 |
| override [EndPoint](../../aspose.gis.geometries/circularstring/endpoint/) { get; } | 返回曲线终点的副本。 |
| override [GeometryType](../../aspose.gis.geometries/circularstring/geometrytype/) { get; } | 获取几何体的类型。 |
| override [HasCurveGeometry](../../aspose.gis.geometries/circularstring/hascurvegeometry/) { get; } | 获取一个值，指示此几何体是否为或包含曲线（非线性）几何体。 |
| [HasM](../../aspose.gis.geometries/circularstring/hasm/) { get; set; } | 获取一个值，指示此实例是否具有 M 坐标。 |
| [HasZ](../../aspose.gis.geometries/circularstring/hasz/) { get; set; } | 获取一个值，指示此实例是否具有 Z 坐标。 |
| [IsClosed](../../aspose.gis.geometries/curve/isclosed/) { get; } | 获取一个值，指示曲线是否闭合。如果曲线的起点等于终点，则曲线闭合。 |
| override [IsEmpty](../../aspose.gis.geometries/circularstring/isempty/) { get; } | 获取一个值，指示此实例是否为空。 |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | 获取一个值，指示从 SFA 角度看此实例是否简单。 |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | 获取一个值，指示此实例是否有效。 |
| [Item](../../aspose.gis.geometries/circularstring/item/) { get; set; } | 获取或设置指定索引处的 [`IPoint`](../ipoint/)。 |
| [SpatialReferenceSystem](../../aspose.gis.geometries/circularstring/spatialreferencesystem/) { get; set; } | 获取此实例的 SpatialReferenceSystem。如果未设置 SpatialReferenceSystem，则此属性可以为 `null`。分配新的 SpatialReferenceSystem 不会执行任何坐标转换，只会更改参考。 |
| override [StartPoint](../../aspose.gis.geometries/circularstring/startpoint/) { get; } | 返回曲线起点的副本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint)(IPoint) | 在圆形字符串的末尾添加一个点。 |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_1)(double, double) | 在圆形字符串的末尾添加一个点。 |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_2)(double, double, double) | 在圆形字符串的末尾添加一个点。 |
| [AddPoint](../../aspose.gis.geometries/circularstring/addpoint/#addpoint_3)(double, double, double, double) | 在圆形字符串的末尾添加一个点。 |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)() | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/)(WkbVariant) | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)() | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant) | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/)(WktVariant, NumericFormat) | 将此几何体转换为其 Well-Known Text 表示。 |
| override [Clone](../../aspose.gis.geometries/circularstring/clone/)() | 克隆此实例。 |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | 确定此几何体是否被指定几何体覆盖。 |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | 确定此几何体是否覆盖指定几何体。 |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | 确定此几何体与指定几何体是否相交。 |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | 从此几何体中减去指定的几何体。 |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | 确定此几何体是否与指定的几何体不相交。 |
| [Equals](../../aspose.gis.geometries/circularstring/equals/#equals)(ICircularString) | 指示当前对象是否等于同类型的另一个对象。 |
| override [Equals](../../aspose.gis.geometries/circularstring/equals/#equals_1)(object) | 确定指定对象是否等于当前对象。 |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | 计算此几何体的面积。 |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | 计算此几何体周围的缓冲区。 |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | 计算此几何体的质心。 |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | 计算此几何体的凸包。 |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | 计算此几何体与指定几何体之间的最小距离。 |
| [GetEnumerator](../../aspose.gis.geometries/circularstring/getenumerator/)() | 返回遍历集合的枚举器。 |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | 计算并返回此几何体的边界范围。 |
| override [GetHashCode](../../aspose.gis.geometries/circularstring/gethashcode/)() | 作为默认的哈希函数。 |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | 计算此几何体的长度。 |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | 构建此几何体与指定几何体的交集。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(Extent) | 确定此几何体是否与指定范围相交。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/)(IGeometry) | 确定此几何体与指定几何体是否相交。 |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | 确定此几何体是否与指定几何体重叠。 |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | 确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | 获取此几何体中表示为线的多边形。 |
| override [Reverse](../../aspose.gis.geometries/circularstring/reverse/)() | 反转此 `CircularString` 中点的顺序。 |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | 将 M 坐标四舍五入到指定的小数位数。 |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | 将 X 和 Y 坐标四舍五入到指定的小数位数。 |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | 将 Z 坐标四舍五入到指定的小数位数。 |
| override [SetEmpty](../../aspose.gis.geometries/circularstring/setempty/)() | 将此 [`Geometry`](../geometry/) 设为空。 |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | 确定此几何体在空间上是否包含指定的几何体。 |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | 确定此几何体在空间上是否等于指定的几何体。 |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | 构建此几何体与指定几何体的对称差。 |
| [ToEditable](../../aspose.gis.geometries/circularstring/toeditable/#toeditable)() | 获取此几何对象的可编辑副本。（3 种方法） |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)() | 获取此几何体的近似或等效的非曲线版本，使用默认的 `tolerance`。（2 个方法） |
| [ToLinearGeometry](../../aspose.gis.geometries/curve/tolineargeometry/)(double) | 获取此几何体的近似或等效的非曲线版本，使用指定的 `tolerance`。（2 个方法） |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | 返回表示当前对象的字符串。 |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | 将此几何体转换为 Svg 表示。 |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | 确定此几何体与指定几何体是否相接触。 |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | 合并此几何体和指定几何体。 |
| [Within](../../aspose.gis.geometries/geometry/within/)(Extent) | 确定此几何体是否位于指定范围内。 |
| [Within](../../aspose.gis.geometries/geometry/within/)(IGeometry) | 确定此几何体是否位于指定几何体内部。 |
| [operator ==](../../aspose.gis.geometries/circularstring/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.gis.geometries/circularstring/op_inequality/) | 实现运算符 !=。 |

## 备注

`CircularString` 由一个或多个首尾相连的圆弧段组成。前三个点定义第一段。第一个点是弧的起始点。第二个点是弧上除起始点和终止点之外的任意中间点。第三个点是弧的终止点。后续的弧仅通过其中间点和终止点定义，因为起始点隐式为前一段的终止点。

### 另见

* class [Curve](../curve/)
* interface [ICircularString](../icircularstring/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


