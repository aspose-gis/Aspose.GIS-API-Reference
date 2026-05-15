---
title: "类 Geometry"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Geometries.Geometry 类。几何层次结构的抽象根类"
type: docs
weight: 2700
url: /zh/net/aspose.gis.geometries/geometry/
---
## Geometry class

几何层次结构的抽象根类。

```csharp
public abstract class Geometry : IGeometry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CoordinateDimension](../../aspose.gis.geometries/geometry/coordinatedimension/) { get; } | 获取此 `Geometry` 的坐标维度数量。 |
| abstract [Dimension](../../aspose.gis.geometries/geometry/dimension/) { get; } | 获取此 `Geometry` 的拓扑维度。如果维度未知（例如对于空的 GEOMETRYCOLLECTION），则返回 Point。 |
| abstract [GeometryType](../../aspose.gis.geometries/geometry/geometrytype/) { get; } | 获取几何体的类型。 |
| virtual [HasCurveGeometry](../../aspose.gis.geometries/geometry/hascurvegeometry/) { get; } | 获取一个值，指示此几何体是否为或包含曲线（非线性）几何体。 |
| virtual [HasM](../../aspose.gis.geometries/geometry/hasm/) { get; set; } | 获取一个值，指示此实例是否具有 M 坐标。 |
| virtual [HasZ](../../aspose.gis.geometries/geometry/hasz/) { get; set; } | 获取一个值，指示此实例是否具有 Z 坐标。 |
| virtual [IsEmpty](../../aspose.gis.geometries/geometry/isempty/) { get; } | 获取一个值，指示此实例是否为空。 |
| [IsSimple](../../aspose.gis.geometries/geometry/issimple/) { get; } | 获取一个值，指示从 SFA 角度看此实例是否简单。 |
| [IsValid](../../aspose.gis.geometries/geometry/isvalid/) { get; } | 获取一个值，指示此实例是否有效。 |
| abstract [SpatialReferenceSystem](../../aspose.gis.geometries/geometry/spatialreferencesystem/) { get; set; } | 获取此实例的 SpatialReferenceSystem。此属性可以为 `null`，表示 SpatialReferenceSystem 未知。为 SpatialReferenceSystem 分配新值不会执行任何坐标转换，只会更改引用。 |
| static [Null](../../aspose.gis.geometries/geometry/null/) { get; } | 获取空几何的实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/#asbinary)() | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsBinary](../../aspose.gis.geometries/geometry/asbinary/#asbinary_1)(WkbVariant) | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage_1)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/geometry/asimage/#asimage_2)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext)() | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext_1)(WktVariant) | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/geometry/astext/#astext_2)(WktVariant, NumericFormat) | 将此几何体转换为其 Well-Known Text 表示。 |
| abstract [Clone](../../aspose.gis.geometries/geometry/clone/)() | 克隆此实例。 |
| [CoveredBy](../../aspose.gis.geometries/geometry/coveredby/)(IGeometry) | 确定此几何体是否被指定几何体覆盖。 |
| [Covers](../../aspose.gis.geometries/geometry/covers/)(IGeometry) | 确定此几何体是否覆盖指定几何体。 |
| [Crosses](../../aspose.gis.geometries/geometry/crosses/)(IGeometry) | 确定此几何体与指定几何体是否相交。 |
| [Difference](../../aspose.gis.geometries/geometry/difference/)(IGeometry) | 从此几何体中减去指定的几何体。 |
| [Disjoint](../../aspose.gis.geometries/geometry/disjoint/)(IGeometry) | 确定此几何体是否与指定的几何体不相交。 |
| [GetArea](../../aspose.gis.geometries/geometry/getarea/)() | 计算此几何体的面积。 |
| [GetBuffer](../../aspose.gis.geometries/geometry/getbuffer/)(double, int) | 计算此几何体周围的缓冲区。 |
| [GetCentroid](../../aspose.gis.geometries/geometry/getcentroid/)() | 计算此几何体的质心。 |
| [GetConvexHull](../../aspose.gis.geometries/geometry/getconvexhull/)() | 计算此几何体的凸包。 |
| [GetDistanceTo](../../aspose.gis.geometries/geometry/getdistanceto/)(IGeometry) | 计算此几何体与指定几何体之间的最小距离。 |
| [GetExtent](../../aspose.gis.geometries/geometry/getextent/)() | 计算并返回此几何体的边界范围。 |
| [GetLength](../../aspose.gis.geometries/geometry/getlength/)() | 计算此几何体的长度。 |
| [Intersection](../../aspose.gis.geometries/geometry/intersection/)(IGeometry) | 构建此几何体与指定几何体的交集。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/#intersects)(Extent) | 确定此几何体是否与指定范围相交。 |
| [Intersects](../../aspose.gis.geometries/geometry/intersects/#intersects_1)(IGeometry) | 确定此几何体与指定几何体是否相交。 |
| [Overlaps](../../aspose.gis.geometries/geometry/overlaps/)(IGeometry) | 确定此几何体是否与指定几何体重叠。 |
| [Relate](../../aspose.gis.geometries/geometry/relate/)(IGeometry, string) | 确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/geometry/replacepolygonsbylines/)() | 获取此几何体中表示为线的多边形。 |
| [RoundM](../../aspose.gis.geometries/geometry/roundm/)(int) | 将 M 坐标四舍五入到指定的小数位数。 |
| [RoundXY](../../aspose.gis.geometries/geometry/roundxy/)(int) | 将 X 和 Y 坐标四舍五入到指定的小数位数。 |
| [RoundZ](../../aspose.gis.geometries/geometry/roundz/)(int) | 将 Z 坐标四舍五入到指定的小数位数。 |
| virtual [SetEmpty](../../aspose.gis.geometries/geometry/setempty/)() | 使此 `Geometry` 为空。 |
| [SpatiallyContains](../../aspose.gis.geometries/geometry/spatiallycontains/)(IGeometry) | 确定此几何体在空间上是否包含指定的几何体。 |
| [SpatiallyEquals](../../aspose.gis.geometries/geometry/spatiallyequals/)(IGeometry) | 确定此几何体在空间上是否等于指定的几何体。 |
| [SymDifference](../../aspose.gis.geometries/geometry/symdifference/)(IGeometry) | 构建此几何体与指定几何体的对称差。 |
| [ToEditable](../../aspose.gis.geometries/geometry/toeditable/#toeditable)() | 获取此几何体的可编辑副本。 |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/geometry/toeditable/#toeditable_1)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/#tolineargeometry)() | 使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/geometry/tolineargeometry/#tolineargeometry_1)(double) | 使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| override [ToString](../../aspose.gis.geometries/geometry/tostring/)() | 返回表示当前对象的字符串。 |
| [ToSvg](../../aspose.gis.geometries/geometry/tosvg/)(Extent) | 将此几何体转换为 Svg 表示。 |
| [Touches](../../aspose.gis.geometries/geometry/touches/)(IGeometry) | 确定此几何体与指定几何体是否相接触。 |
| [Union](../../aspose.gis.geometries/geometry/union/)(IGeometry) | 合并此几何体和指定几何体。 |
| [Within](../../aspose.gis.geometries/geometry/within/#within)(Extent) | 确定此几何体是否位于指定范围内。 |
| [Within](../../aspose.gis.geometries/geometry/within/#within_1)(IGeometry) | 确定此几何体是否位于指定几何体内部。 |
| static [FromBinary](../../aspose.gis.geometries/geometry/frombinary/#frombinary)(byte[]) | 从其已知二进制（Well-Known Binary）表示创建几何体。 |
| static [FromBinary](../../aspose.gis.geometries/geometry/frombinary/#frombinary_1)(byte[], SpatialReferenceSystem) | 从其已知二进制（Well-Known Binary）表示创建几何体。 |
| static [FromText](../../aspose.gis.geometries/geometry/fromtext/#fromtext)(string) | 从其已知文本（Well-Known Text）表示创建几何体。 |
| static [FromText](../../aspose.gis.geometries/geometry/fromtext/#fromtext_1)(string, SpatialReferenceSystem) | 从其已知文本（Well-Known Text）表示创建几何体。 |

### 另见

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


