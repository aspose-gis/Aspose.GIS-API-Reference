---
title: "类 SpatialReferenceSystem"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.SpatialReferenceSystem 类。空间参考系统将坐标映射到地球上的位置。有不同类型的 SRS，请参见 Type。更进一步，如果 SRS 的类型是 Geographic 或 Projected，SRS 可以是复合的或单一的，请参见 IsCompound"
type: docs
weight: 4700
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/
---
## SpatialReferenceSystem class

空间参考系统将坐标映射到地球上的位置。有不同类型的 SRS，请参见 [`Type`](./type/)。更进一步，如果 SRS 的类型是 Geographic 或 Projected，SRS 可以是复合的或单一的，请参见 [`IsCompound`](./iscompound/)。

```csharp
public abstract class SpatialReferenceSystem : IdentifiableObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | 返回此 SRS 转换为 [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/)。使用 [`IsCompound`](./iscompound/) 来判断是否可以进行转换。 |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | 返回此 SRS 转换为 [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/)。使用 [`Type`](./type/) 来判断是否可以进行转换。 |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | 返回此 SRS 转换为 [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/)。使用 [`Type`](./type/) 来判断是否可以进行转换。 |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | 返回此 SRS 转换为 [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/)。使用 [`Type`](./type/) 来判断是否可以进行转换。 |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | 返回此 SRS 转换为 [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/)。使用 [`Type`](./type/) 来判断是否可以进行转换。 |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | 返回此 SRS 转换为 [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/)。使用 [`Type`](./type/) 来判断是否可以进行转换。 |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/spatialreferencesystem/dimensionscount/) { get; } | 返回此 SRS 的维度数量。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum/) { get; } | 返回此 SRS 的地理基准。 |
| abstract [HasGeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/hasgeographicdatum/) { get; } | 确定此 SRS 是否具有地理基准。这对所有 geographic、projected 和 geocentric SRS 均为 true。 |
| abstract [HasPrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/hasprimemeridian/) { get; } | 返回此 SRS 是否具有本初子午线。这对所有 geographic、projected 和 geocentric SRS 均为 true。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | 返回此 SRS 是否为复合（两个 SRS 的联合）。在复合 SRS 中，以下 SRS 组合被视为有效：Geographic SRS + Vertical SRS，此时复合 SRS 的类型为 Geographic；Projected SRS + Vertical SRS，此时复合 SRS 的类型为 Projected。如果 SRS 组合不同，复合 SRS 的类型将为 Unknown。 |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | 返回此 SRS 是否为单一（不是两个 SRS 的联合）。 |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | 与 [`Validate`](./validate/) 相同，但不返回错误信息。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian/) { get; } | 返回此 SRS 的本初子午线。 |
| abstract [Type](../../aspose.gis.spatialreferencing/spatialreferencesystem/type/) { get; } | 获取此 SRS 的类型，请参见 [`SpatialReferenceSystemType`](../spatialreferencesystemtype/)。 |
| static [Etrs89](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89/) { get; } | ETRS 89 (EPSG:4258) 空间参考系统。 |
| static [Etrs89LambertAzimuthalEqualArea](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89lambertazimuthalequalarea/) { get; } | ETRS 89 / ETRS Lambert 方位等面积 (EPSG:3035) 空间参考系统。 |
| static [Etrs89LambertConformalConic](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89lambertconformalconic/) { get; } | ETRS 89 / Lambert 正形圆锥投影 (EPSG:3034) 空间参考系统。 |
| static [Nad83](../../aspose.gis.spatialreferencing/spatialreferencesystem/nad83/) { get; } | NAD 83 (EPSG:4269) 空间参考系统。 |
| static [Osgb36](../../aspose.gis.spatialreferencing/spatialreferencesystem/osgb36/) { get; } | OSGB 36 (EPSG:4277) 空间参考系统。 |
| static [Osgb36BritishNationalGrid](../../aspose.gis.spatialreferencing/spatialreferencesystem/osgb36britishnationalgrid/) { get; } | OSGB 36 / 英国国家网格 (EPSG:27700) 空间参考系统。 |
| static [WebMercator](../../aspose.gis.spatialreferencing/spatialreferencesystem/webmercator/) { get; } | Web Mercator (EPSG:3857) 空间参考系统。 |
| static [Wgs72](../../aspose.gis.spatialreferencing/spatialreferencesystem/wgs72/) { get; } | WGS 72 (EPSG:4322) 空间参考系统。 |
| static [Wgs84](../../aspose.gis.spatialreferencing/spatialreferencesystem/wgs84/) { get; } | WGS 84 (EPSG:4326) 空间参考系统。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFromEpsg](../../aspose.gis.spatialreferencing/spatialreferencesystem/createfromepsg/)(int) | 基于指定的 EPSG 代码创建空间参考系统。 |
| static [CreateFromWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/)(string) | 基于 WKT（Well-Known Text）字符串创建新的 `SpatialReferenceSystem`。 |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | 返回此 SRS 的 WKT 字符串表示。结果 WKT 字符串将符合 OGC 01-009 规范，通常命名为 "WKT1"。 |
| abstract [GetAxis](../../aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/)(int) | 获取描述维度的 [`Axis`](../axis/)。 |
| abstract [GetUnit](../../aspose.gis.spatialreferencing/spatialreferencesystem/getunit/)(int) | 获取维度的 [`Unit`](../unit/)。 |
| virtual [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | 检测此 SRS 是否等价于其他 SRS。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | 创建从此 `SpatialReferenceSystem` 到另一个 `SpatialReferenceSystem` 的转换。 |
| abstract [Validate](../../aspose.gis.spatialreferencing/spatialreferencesystem/validate/)(out string) | 确定此 SRS 是否有效。 |
| static [CreateCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/)(string, SpatialReferenceSystem, SpatialReferenceSystem, Identifier) | 创建复合 SRS。 |
| static [CreateGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/creategeocentric/)(GeocentricSpatialReferenceSystemParameters, Identifier) | 使用自定义参数创建地心 SRS。 |
| static [CreateGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/creategeographic/)(GeographicSpatialReferenceSystemParameters, Identifier) | 使用自定义参数创建地理 SRS。 |
| static [CreateLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/)(string, LocalDatum, Unit, ICollection&lt;Axis&gt;, Identifier) | 创建本地空间参考系统。 |
| static [CreateProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/createprojected/)(ProjectedSpatialReferenceSystemParameters, Identifier) | 使用自定义参数创建投影 SRS。 |
| static [CreateVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/createvertical/)(string, VerticalDatum, Unit, Axis, Identifier) | 创建垂直 SRS。 |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem, SpatialReferenceSystem) | 确定两个 SRS 是否等价。等价 SRS 的相同坐标对应地球上的同一位置。等价 SRS 的某些参数可能不同，例如 [`Name`](../identifiableobject/name/)。 |
| static [TryCreateFromEpsg](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/)(int, out SpatialReferenceSystem) | 基于指定的 EPSG 代码创建空间参考系统。 |
| static [TryCreateFromWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromwkt/)(string, out SpatialReferenceSystem) | 基于 WKT（Well-Known Text）字符串创建新的 `SpatialReferenceSystem`。 |

### 另见

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


