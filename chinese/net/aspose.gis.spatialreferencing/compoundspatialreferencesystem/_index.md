---
title: "类 CompoundSpatialReferenceSystem"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.CompoundSpatialReferenceSystem 类。复合 SRS 将两个底层 SRS 合并，且它们均不能是复合的"
type: docs
weight: 4510
url: /zh/net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---
## CompoundSpatialReferenceSystem class

复合 SRS 将两个底层 SRS 合并，且这两个 SRS 都不能是复合的。

```csharp
public class CompoundSpatialReferenceSystem : SpatialReferenceSystem
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [AsCompound](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/ascompound/) { get; } | 返回此对象。 |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | 返回此 SRS 转换为 [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| override [AsGeographic](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/asgeographic/) { get; } | 返回此 SRS 的地理表示。如果此复合 SRS 确实表示一个 Geographic SRS，则结果将是三维地理 SRS（具有经度、纬度、高度维度）。否则将抛出异常。 |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | 返回此 SRS 转换为 [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 来判断是否可以进行转换。 |
| override [AsProjected](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/asprojected/) { get; } | 返回此 SRS 的投影表示。如果此复合 SRS 确实表示一个 Projected SRS，则结果将是三维投影 SRS（具有 X、Y、高度维度）。否则将抛出异常。 |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | 返回此 SRS 转换为 [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/)。使用 [`Type`](../spatialreferencesystem/type/) 以确定是否可以进行转换。 |
| override [DimensionsCount](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/dimensionscount/) { get; } | 维度数量。对于复合 SRS，这等于底层 SRS 维度数量的总和。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| override [GeographicDatum](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/geographicdatum/) { get; } | 返回此 SRS 的地理基准。如果 [`Head`](./head/) 和 [`Tail`](./tail/) 都具有地理基准，则返回头部的地理基准。 |
| override [HasGeographicDatum](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/hasgeographicdatum/) { get; } | 如果任意底层 SRS 具有地理基准，则复合 SRS 具有地理基准。 |
| override [HasPrimeMeridian](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/hasprimemeridian/) { get; } | 如果任意底层 SRS 具有本初子午线，则复合 SRS 具有本初子午线。 |
| [Head](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/head/) { get; } | 第一个底层 SRS。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| override [IsCompound](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/iscompound/) { get; } | 返回 `true`。 |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | 返回此 SRS 是否为单一（不是两个 SRS 的联合）。 |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | 与 [`Validate`](../spatialreferencesystem/validate/) 相同，但不返回错误信息。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| override [PrimeMeridian](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/primemeridian/) { get; } | 返回此 SRS 的本初子午线。如果 [`Head`](./head/) 和 [`Tail`](./tail/) 都具有本初子午线，则返回头部的本初子午线。 |
| [Tail](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/tail/) { get; } | 第二个底层 SRS。 |
| override [Type](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/type/) { get; } | 此复合 SRS 的类型。如果此复合 SRS 是地理和垂直 SRS 的组合，则为 Geographic；如果此复合 SRS 是投影和垂直 SRS 的组合，则为 Projected。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | 返回此 SRS 的 WKT 字符串表示。结果 WKT 字符串将符合 OGC 01-009 规范，通常称为 "WKT1"。 |
| override [GetAxis](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/getaxis/)(int) | 获取描述维度的 [`Axis`](../axis/)。 |
| override [GetUnit](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/getunit/)(int) | 获取维度的 [`Unit`](../unit/)。 |
| override [IsEquivalent](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | 检测此 SRS 是否等价于其他 SRS。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| override [Validate](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/validate/)(out string) | 确定此 SRS 是否有效。请参阅 [`Validate`](../spatialreferencesystem/validate/) 了解有效性说明。 |

### 另见

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


