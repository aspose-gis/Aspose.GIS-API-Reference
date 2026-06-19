---
title: "类 Extent"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Extent 类。二维空间边界框"
type: docs
weight: 1610
url: /zh/net/aspose.gis/extent/
---
## Extent class

二维空间边界框。

```csharp
public class Extent : IEquatable<Extent>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Extent](extent/#constructor)() | 创建新实例。 |
| [Extent](extent/#constructor_1)(SpatialReferenceSystem) | 创建新实例。 |
| [Extent](extent/#constructor_2)(double, double, double, double, SpatialReferenceSystem) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Center](../../aspose.gis/extent/center/) { get; } | 范围的中心。 |
| [Height](../../aspose.gis/extent/height/) { get; } | 范围的高度。 |
| [IsValid](../../aspose.gis/extent/isvalid/) { get; } | 确定此 `Extent` 是否有效。 |
| [SpatialReferenceSystem](../../aspose.gis/extent/spatialreferencesystem/) { get; set; } | [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) 与此范围关联。如果 [`SpatialReferenceSystem`](./spatialreferencesystem/) 未知，则可以为 `null`。使用 [`GetTransformed`](./gettransformed/) 在不同空间参考系统之间转换范围。 |
| [Width](../../aspose.gis/extent/width/) { get; } | 范围的宽度。 |
| [XMax](../../aspose.gis/extent/xmax/) { get; set; } | X 坐标的最大值。 |
| [XMin](../../aspose.gis/extent/xmin/) { get; set; } | X 坐标的最小值。 |
| [YMax](../../aspose.gis/extent/ymax/) { get; set; } | Y 坐标的最大值。 |
| [YMin](../../aspose.gis/extent/ymin/) { get; set; } | Y 坐标的最小值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.gis/extent/clone/)() | 克隆此实例。 |
| [Contains](../../aspose.gis/extent/contains/#contains)(Extent) | 确定此范围是否包含该参数。 |
| [Contains](../../aspose.gis/extent/contains/#contains_1)(IGeometry) | 确定此范围是否包含该参数。 |
| [Contains](../../aspose.gis/extent/contains/#contains_2)(double, double) | 确定此范围是否包含由参数定义的坐标。 |
| [Equals](../../aspose.gis/extent/equals/#equals)(Extent) | 指示当前对象是否等于同类型的另一个对象。 |
| override [Equals](../../aspose.gis/extent/equals/#equals_1)(object) | 确定指定的对象是否等于当前对象。 |
| override [GetHashCode](../../aspose.gis/extent/gethashcode/)() | 用作默认的哈希函数。 |
| [GetTransformed](../../aspose.gis/extent/gettransformed/)(SpatialReferenceSystem) | 返回在指定的[`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/)中包含此范围的新范围。 |
| [Grow](../../aspose.gis/extent/grow/#grow)(Extent) | 扩展此范围，使其包含参数。 |
| [Grow](../../aspose.gis/extent/grow/#grow_1)(double, double) | 扩展此范围，使其包含指定的点。 |
| [GrowX](../../aspose.gis/extent/growx/)(double) | 沿 X 轴扩展此范围，使其包含指定的值。 |
| [GrowY](../../aspose.gis/extent/growy/)(double) | 沿 Y 轴扩展此范围，使其包含指定的值。 |
| [Intersects](../../aspose.gis/extent/intersects/#intersects)(Extent) | 确定此范围是否与参数相交。 |
| [Intersects](../../aspose.gis/extent/intersects/#intersects_1)(IGeometry) | 确定此范围是否与参数相交。 |
| [Normalize](../../aspose.gis/extent/normalize/)() | 如果[`Width`](./width/)为负，则交换[`XMin`](./xmin/)和[`XMax`](./xmax/)；如果[`Height`](./height/)为负，则交换[`YMin`](./ymin/)和[`YMax`](./ymax/)。 |
| [ToPolygon](../../aspose.gis/extent/topolygon/)() | 将此范围转换为表示它的矩形多边形。 |
| override [ToString](../../aspose.gis/extent/tostring/)() | 返回表示当前对象的字符串。 |
| [operator ==](../../aspose.gis/extent/op_equality/) | 实现 '==' 运算符。 |
| [operator !=](../../aspose.gis/extent/op_inequality/) | 实现 '!=' 运算符。 |

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


