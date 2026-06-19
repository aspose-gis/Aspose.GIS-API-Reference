---
title: "Aspose.Gis.SpatialReferencing"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing 命名空间提供用于处理空间参考坐标参考系统的类。"
type: docs
weight: 750
url: /zh/net/aspose.gis.spatialreferencing/
---
`Aspose.Gis.SpatialReferencing` 命名空间提供用于处理空间参考（坐标参考系统）的类。

## 类

| 类 | 描述 |
| --- | --- |
| [Axis](./axis/) | 轴描述 SRS 的一个维度。 |
| [BursaWolfParameters](./bursawolfparameters/) | 包含 Bursa-Wolf 公式参数以转换到其他基准的类。 |
| [CompoundSpatialReferenceSystem](./compoundspatialreferencesystem/) | 复合 SRS 将两个基础 SRS 组合在一起，且它们均不能是复合的。 |
| [Ellipsoid](./ellipsoid/) | 椭球体表示一种近似地球的椭球体。 |
| [GeocentricSpatialReferenceSystem](./geocentricspatialreferencesystem/) | 地心 SRS 是以地球中心为原点的三维笛卡尔 SRS。 |
| [GeocentricSpatialReferenceSystemParameters](./geocentricspatialreferencesystemparameters/) | 用于创建地心 SRS 的参数。这些参数具有合理的默认值，因此您只需分配其中的一部分。如果将 `null` 分配给任何参数，将使用默认值。 |
| [GeographicDatum](./geographicdatum/) | 地理基准将经度和纬度关联到地球上的特定位置。 |
| [GeographicSpatialReferenceSystem](./geographicspatialreferencesystem/) | 地理 SRS 是基于经度和纬度的 SRS。地理 SRS 可以是二维或三维的。如果地理 SRS 为三维，则实际上是由二维 SRS 和垂直 SRS 组成的复合 SRS。 |
| [GeographicSpatialReferenceSystemParameters](./geographicspatialreferencesystemparameters/) | 用于创建地理 SRS 的参数。这些参数具有合理的默认值，因此您只需分配其中的一部分。如果将 `null` 分配给任何参数，将使用默认值。 |
| [IdentifiableObject](./identifiableobject/) | 表示可能具有 EPSG 代码和名称的对象。 |
| [Identifier](./identifier/) | 表示标识符——对象外部描述的引用。如果您从 WKT 创建 SRS，[`Identifier`](../aspose.gis.spatialreferencing/identifier/) 对应于 "AUTHORITY" 关键字。 |
| [LocalDatum](./localdatum/) | 指示在本地空间参考系统中用于测量的方法。 |
| [LocalSpatialReferenceSystem](./localspatialreferencesystem/) | 本地 SRS 将坐标关联到某个对象，而非地球。 |
| [PrimeMeridian](./primemeridian/) | 本初子午线表示经度被定义为 0 的子午线。 |
| [ProjectedSpatialReferenceSystem](./projectedspatialreferencesystem/) | 投影 SRS 是对地理 SRS 应用投影的结果。投影 SRS 可以是二维或三维的。如果投影 SRS 为三维，则实际上是由二维投影 SRS 和一维垂直 SRS 组成的复合 SRS。 |
| [ProjectedSpatialReferenceSystemParameters](./projectedspatialreferencesystemparameters/) | 用于创建投影 SRS 的参数。有些参数有默认值。某些参数具有合理的默认值，因此您不必仅分配它们。如果将 `null` 分配给这些参数，将使用默认值。[`ProjectionMethodName`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) 和 [`Base`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) 没有默认值——您必须为这些属性分配非 `null` 的值。 |
| [Projection](./projection/) | 表示一种带有参数的投影方法，将 (经度, 纬度) 转换为 (x, y)。 |
| [SpatialReferenceSystem](./spatialreferencesystem/) | 空间参考系统将坐标映射到地球上的位置。SRS 有不同的类型，参见 [`Type`](../aspose.gis.spatialreferencing/spatialreferencesystem/type/)。此外，如果 SRS 的类型是 Geographic 或 Projected，SRS 可以是复合的或单一的，参见 [`IsCompound`](../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/)。 |
| [SpatialReferenceSystemTransformation](./spatialreferencesystemtransformation/) | 空间参考系统转换将几何体从源空间参考系统转换到目标空间参考系统。 |
| [TransformationException](./transformationexception/) | 当坐标转换或转换创建期间出现错误时，会抛出转换异常。 |
| [Unit](./unit/) | 表示测量单位。 |
| [VerticalDatum](./verticaldatum/) | 指示用于垂直测量的方法。 |
| [VerticalSpatialReferenceSystem](./verticalspatialreferencesystem/) | 垂直 SRS 是一种描述高度坐标的一维空间参考系统。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AxisDirection](./axisdirection/) | 轴方向定义轴指向的方向。 |
| [GeocentricAxisesOrder](./geocentricaxisesorder/) | 表示地心 SRS 中轴的顺序。 |
| [GeographicAxisesOrder](./geographicaxisesorder/) | 表示地理 SRS 中轴的顺序。 |
| [ParameterType](./parametertype/) | 确定 [`Projection`](../aspose.gis.spatialreferencing/projection/) 中参数的类型。 |
| [ProjectedAxisesOrder](./projectedaxisesorder/) | 表示地理 SRS 中轴的顺序。 |
| [SpatialReferenceSystemType](./spatialreferencesystemtype/) | 表示空间参考系统的类型。 |


