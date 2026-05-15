---
title: "类 ProjectedSpatialReferenceSystem"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.ProjectedSpatialReferenceSystem 类。Projected SRS 是将投影应用于地理 SRS 的结果。投影 SRS 可以是二维的或三维的。如果投影 SRS 为三维，则它实际上是由二维投影 SRS 和一维垂直 SRS 组成的复合 SRS。"
type: docs
weight: 4670
url: /zh/net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/
---
## ProjectedSpatialReferenceSystem class

投影 SRS 是对地理 SRS 应用投影的结果。投影 SRS 可以是二维或三维的。如果投影 SRS 为三维，则实际上是由二维投影 SRS 和一维垂直 SRS 组成的复合 SRS。

```csharp
public abstract class ProjectedSpatialReferenceSystem : SpatialReferenceSystem
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [AngularUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/angularunit/) { get; } | 此 SRS 中用于角度值的单位，以及用于 [`Projection`](./projection/) 的角度参数。与 [`Base`](./base/) 的角度单位相匹配。 |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | 返回此 SRS 转换为 [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/)。使用 [`IsCompound`](../spatialreferencesystem/iscompound/) 来判断是否可以进行转换。 |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | 返回此 SRS 转换为 [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | 返回此 SRS 转换为 [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | 返回此 SRS 转换为 [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| [AsProjected](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/asprojected/) { get; } | 返回此对象。 |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | 返回此 SRS 转换为 [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 以确定是否可以进行转换。 |
| abstract [AxisesOrder](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/axisesorder/) { get; } | 此 SRS 中轴的顺序。如果此 SRS 无效且轴方向错误，将返回 Invalid。 |
| abstract [Base](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/base/) { get; } | 通过对 [`Projection`](./projection/) 应用而得到此 SRS 的地理 SRS。 |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/dimensionscount/) { get; } | 返回此 SRS 的维度计数。对于投影 SRS，这可能是：两 - 如果这是单一投影 SRS。三 - 如果这是复合 SRS，由单一二维投影 SRS 和垂直 SRS 组成，后者增加第三维度。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum/) { get; } | 返回此 SRS 的地理基准。 |
| [HasGeographicDatum](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/hasgeographicdatum/) { get; } | 返回 true，因为投影 SRS 总是具有本初子午线。 |
| [HasPrimeMeridian](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/hasprimemeridian/) { get; } | 返回 true，因为投影 SRS 总是具有本初子午线。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | 返回此 SRS 是否为复合（两个 SRS 的联合）。在复合 SRS 中，以下 SRS 组合被视为有效：Geographic SRS + Vertical SRS，此时复合 SRS 的类型为 Geographic；Projected SRS + Vertical SRS，此时复合 SRS 的类型为 Projected。如果 SRS 组合不同，复合 SRS 的类型将为 Unknown。 |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | 返回此 SRS 是否为单一（不是两个 SRS 的联合）。 |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | 与 [`Validate`](../spatialreferencesystem/validate/) 相同，但不返回错误信息。 |
| abstract [LinearUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/linearunit/) { get; } | 单位，用于此 SRS 中的线性维度以及 [`Projection`](./projection/) 的线性参数。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian/) { get; } | 返回此 SRS 的本初子午线。 |
| abstract [Projection](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/projection/) { get; } | 投影，已应用于 [`Base`](./base/) 以获得此 SRS。 |
| [Type](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/type/) { get; } | 返回 Projected。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | 返回此 SRS 的 WKT 字符串表示。结果 WKT 字符串将符合 OGC 01-009 规范，通常称为 "WKT1"。 |
| abstract [GetAxis](../../aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/)(int) | 获取描述维度的 [`Axis`](../axis/)。 |
| abstract [GetUnit](../../aspose.gis.spatialreferencing/spatialreferencesystem/getunit/)(int) | 获取维度的 [`Unit`](../unit/)。 |
| virtual [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | 检测此 SRS 是否等价于其他 SRS。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| abstract [Validate](../../aspose.gis.spatialreferencing/spatialreferencesystem/validate/)(out string) | 确定此 SRS 是否有效。 |

### 另见

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


