---
title: "类 VerticalSpatialReferenceSystem"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.VerticalSpatialReferenceSystem 类。垂直 SRS 是描述高度坐标的一维 SRS。"
type: docs
weight: 4760
url: /zh/net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/
---
## VerticalSpatialReferenceSystem class

垂直 SRS 是一种描述高度坐标的一维空间参考系统。

```csharp
public class VerticalSpatialReferenceSystem : SpatialReferenceSystem
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | 返回此 SRS 转换为 [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/)。使用 [`IsCompound`](../spatialreferencesystem/iscompound/) 来判断是否可以进行转换。 |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | 返回此 SRS 转换为 [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | 返回此 SRS 转换为 [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | 返回此 SRS 转换为 [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | 返回此 SRS 转换为 [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| override [AsVertical](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/asvertical/) { get; } | 返回此 SRS。 |
| override [DimensionsCount](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/dimensionscount/) { get; } | 返回 1，因为垂直 SRS 始终是一维的。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| override [GeographicDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/geographicdatum/) { get; } | 抛出 InvalidOperationException，因为垂直 SRS 没有地理基准。 |
| override [HasGeographicDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/hasgeographicdatum/) { get; } | 返回 `false`，因为垂直 SRS 没有地理基准。 |
| override [HasPrimeMeridian](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/hasprimemeridian/) { get; } | 返回 `false`，因为垂直 SRS 没有本初子午线。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | 返回此 SRS 是否为复合（两个 SRS 的联合）。在复合 SRS 中，以下 SRS 组合被视为有效：Geographic SRS + Vertical SRS，此时复合 SRS 的类型为 Geographic；Projected SRS + Vertical SRS，此时复合 SRS 的类型为 Projected。如果 SRS 组合不同，复合 SRS 的类型将为 Unknown。 |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | 返回此 SRS 是否为单一（不是两个 SRS 的联合）。 |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | 同 [`Validate`](../spatialreferencesystem/validate/)，但不返回错误信息。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| override [PrimeMeridian](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/primemeridian/) { get; } | 抛出 InvalidOperationException，因为垂直 SRS 没有本初子午线。 |
| override [Type](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/type/) { get; } | 返回垂直。 |
| [VerticalDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/verticaldatum/) { get; } | 此 SRS 使用的基准面。 |
| [VerticalUnit](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/verticalunit/) { get; } | 此 SRS 使用的单位。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | 返回此 SRS 的 WKT 字符串表示。结果 WKT 字符串将符合 OGC 01-009 规范，通常命名为 "WKT1"。 |
| override [GetAxis](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/getaxis/)(int) | 获取描述维度的 [`Axis`](../axis/)。 |
| override [GetUnit](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/getunit/)(int) | 获取维度的 [`Unit`](../unit/)。 |
| override [IsEquivalent](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | 检测此 SRS 是否等价于其他 SRS。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| override [Validate](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/validate/)(out string) | 确定此 SRS 是否有效。参见 [`Validate`](../spatialreferencesystem/validate/) 获取有效性描述。 |

### 另见

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


