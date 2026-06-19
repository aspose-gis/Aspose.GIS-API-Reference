---
title: "接口 IGeometry"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Geometries.IGeometry 接口。几何层次结构的接口根类"
type: docs
weight: 2780
url: /zh/net/aspose.gis.geometries/igeometry/
---
## IGeometry interface

Geometries 层次结构的接口根类。

```csharp
public interface IGeometry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Dimension](../../aspose.gis.geometries/igeometry/dimension/) { get; } | 获取此 `IGeometry` 的拓扑维度。如果维度未知（例如对于空的 GEOMETRYCOLLECTION），则返回 Point。 |
| [GeometryType](../../aspose.gis.geometries/igeometry/geometrytype/) { get; } | 获取几何体的类型。 |
| [HasCurveGeometry](../../aspose.gis.geometries/igeometry/hascurvegeometry/) { get; } | 获取一个值，指示此几何体是否为或包含曲线（非线性）几何体。 |
| [HasM](../../aspose.gis.geometries/igeometry/hasm/) { get; } | 获取一个值，指示此实例是否具有 M 坐标。 |
| [HasZ](../../aspose.gis.geometries/igeometry/hasz/) { get; } | 获取一个值，指示此实例是否具有 Z 坐标。 |
| [IsEmpty](../../aspose.gis.geometries/igeometry/isempty/) { get; } | 获取一个值，指示此实例是否为空（表示空点集）。 |
| [IsSimple](../../aspose.gis.geometries/igeometry/issimple/) { get; } | 获取一个值，指示从 SFA 角度看此实例是否为简单。 |
| [IsValid](../../aspose.gis.geometries/igeometry/isvalid/) { get; } | 获取一个值，指示此实例是否有效。 |
| [SpatialReferenceSystem](../../aspose.gis.geometries/igeometry/spatialreferencesystem/) { get; } | 获取此实例的 SpatialReferenceSystem。如果 SpatialReferenceSystem 未知，此属性可以为 `null`。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AsBinary](../../aspose.gis.geometries/igeometry/asbinary/#asbinary)() | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsBinary](../../aspose.gis.geometries/igeometry/asbinary/#asbinary_1)(WkbVariant) | 将此几何体转换为其 Well-Known Binary 表示。 |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage)(Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage_1)(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsImage](../../aspose.gis.geometries/igeometry/asimage/#asimage_2)(string, Measurement, Measurement, Renderer, VectorSymbolizer) | 将此几何体导出为图像表示。 |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext)() | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext_1)(WktVariant) | 将此几何体转换为其 Well-Known Text 表示。 |
| [AsText](../../aspose.gis.geometries/igeometry/astext/#astext_2)(WktVariant, NumericFormat) | 将此几何体转换为其 Well-Known Text 表示。 |
| [Clone](../../aspose.gis.geometries/igeometry/clone/)() | 克隆此实例。 |
| [CoveredBy](../../aspose.gis.geometries/igeometry/coveredby/)(IGeometry) | 确定此几何体是否被指定的几何体覆盖。 |
| [Covers](../../aspose.gis.geometries/igeometry/covers/)(IGeometry) | 确定此几何体是否覆盖指定的几何体。 |
| [Crosses](../../aspose.gis.geometries/igeometry/crosses/)(IGeometry) | 确定此几何体与指定的几何体是否相交。 |
| [Difference](../../aspose.gis.geometries/igeometry/difference/)(IGeometry) | 从此几何体中减去指定的几何体。 |
| [Disjoint](../../aspose.gis.geometries/igeometry/disjoint/)(IGeometry) | 确定此几何体是否与指定的几何体不相交。 |
| [GetArea](../../aspose.gis.geometries/igeometry/getarea/)() | 计算此几何体的面积。 |
| [GetBuffer](../../aspose.gis.geometries/igeometry/getbuffer/)(double, int) | 计算此几何体周围的缓冲区。 |
| [GetCentroid](../../aspose.gis.geometries/igeometry/getcentroid/)() | 计算此几何体的质心。 |
| [GetConvexHull](../../aspose.gis.geometries/igeometry/getconvexhull/)() | 计算此几何体的凸包。 |
| [GetDistanceTo](../../aspose.gis.geometries/igeometry/getdistanceto/)(IGeometry) | 计算此几何体与指定几何体之间的最小距离。 |
| [GetExtent](../../aspose.gis.geometries/igeometry/getextent/)() | 计算并返回此几何体的边界范围。 |
| [GetLength](../../aspose.gis.geometries/igeometry/getlength/)() | 计算此几何体的长度。 |
| [Intersection](../../aspose.gis.geometries/igeometry/intersection/)(IGeometry) | 构建此几何体与指定几何体的交集。 |
| [Intersects](../../aspose.gis.geometries/igeometry/intersects/#intersects)(Extent) | 确定此几何体是否与指定范围相交。 |
| [Intersects](../../aspose.gis.geometries/igeometry/intersects/#intersects_1)(IGeometry) | 确定此几何体和指定几何体是否相交。 |
| [Overlaps](../../aspose.gis.geometries/igeometry/overlaps/)(IGeometry) | 确定此几何体是否与指定几何体重叠。 |
| [Relate](../../aspose.gis.geometries/igeometry/relate/)(IGeometry, string) | 确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。 |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometry/replacepolygonsbylines/)() | 获取此几何体以线表示的多边形。 |
| [SpatiallyContains](../../aspose.gis.geometries/igeometry/spatiallycontains/)(IGeometry) | 确定此几何体在空间上是否包含指定的几何体。 |
| [SpatiallyEquals](../../aspose.gis.geometries/igeometry/spatiallyequals/)(IGeometry) | 确定此几何体在空间上是否等于指定的几何体。 |
| [SymDifference](../../aspose.gis.geometries/igeometry/symdifference/)(IGeometry) | 构建此几何体与指定几何体的对称差。 |
| [ToEditable](../../aspose.gis.geometries/igeometry/toeditable/#toeditable)() | 获取此几何体的可编辑副本。 |
| [ToEditable&lt;T&gt;](../../aspose.gis.geometries/igeometry/toeditable/#toeditable_1)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometry/tolineargeometry/#tolineargeometry)() | 使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometry/tolineargeometry/#tolineargeometry_1)(double) | 使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| [Touches](../../aspose.gis.geometries/igeometry/touches/)(IGeometry) | 确定此几何体与指定几何体是否相接。 |
| [Union](../../aspose.gis.geometries/igeometry/union/)(IGeometry) | 合并此几何体和指定几何体。 |
| [Within](../../aspose.gis.geometries/igeometry/within/#within)(Extent) | 确定此几何体是否位于指定的范围内。 |
| [Within](../../aspose.gis.geometries/igeometry/within/#within_1)(IGeometry) | 确定此几何体是否位于指定的几何体内。 |

### 另见

* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


