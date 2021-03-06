---
title: Aspose.Gis.SpatialReferencing
second_title: Aspose.GIS for .NET API 参考
description:  Aspose.Gis.SpatialReferencing 命名空间提供了用于处理空间参考坐标参考系统的类
type: docs
weight: 330
url: /zh/net/aspose.gis.spatialreferencing/
---
` Aspose.Gis.SpatialReferencing` 命名空间提供了用于处理空间参考（坐标参考系统）的类。

## 课程

| 班级 | 描述 |
| --- | --- |
| [Axis](./axis) | 轴描述 SRS 的一维。 |
| [BursaWolfParameters](./bursawolfparameters) | 包含 Bursa-Wolf 公式的参数以转换为另一个数据的类。 |
| [CompoundSpatialReferenceSystem](./compoundspatialreferencesystem) | 复合 SRS 将两个基础 SRS 结合在一起，其中任何一个都不能是复合的。 |
| [Ellipsoid](./ellipsoid) | Ellipsoid 表示一个椭圆体，它近似于地球。 |
| [GeocentricSpatialReferenceSystem](./geocentricspatialreferencesystem) | 地心 SRS 是 3 维笛卡尔 SRS，原点位于地球中心。 |
| [GeocentricSpatialReferenceSystemParameters](./geocentricspatialreferencesystemparameters) | 创建地心 SRS 的参数。 参数具有合理的默认值，因此您只需分配其中的一些。 如果将`null`分配给任何参数，将使用默认值。 |
| [GeographicDatum](./geographicdatum) | 地理基准将经度和纬度与地球上的特定位置联系起来。 |
| [GeographicSpatialReferenceSystem](./geographicspatialreferencesystem) | 地理 SRS 是基于经度和纬度的 SRS。 地理 SRS 可以是二维或三维的。 如果地理SRS是三维的，那么它实际上是二维SRS和垂直SRS的复合SRS。 |
| [GeographicSpatialReferenceSystemParameters](./geographicspatialreferencesystemparameters) | 创建地理 SRS 的参数。 参数具有合理的默认值，因此您只需分配其中的一些。 如果将`null`分配给任何参数，将使用默认值。 |
| [IdentifiableObject](./identifiableobject) | 表示可能具有 EPSG 代码和名称的对象。 |
| [Identifier](./identifier) | 表示标识符 - 对对象外部描述的引用。 如果您从 WKT 创建 SRS，则[`Identifier`](../aspose.gis.spatialreferencing/identifier)对应于“AUTHORITY”关键字。 |
| [LocalDatum](./localdatum) | 表示在本地空间参考系统中用于测量的方法。 |
| [LocalSpatialReferenceSystem](./localspatialreferencesystem) | 本地 SRS 相关坐标到某个对象，而不是地球。 |
| [PrimeMeridian](./primemeridian) | PrimeMeridian 表示经度定义为 0 的子午线。 |
| [ProjectedSpatialReferenceSystem](./projectedspatialreferencesystem) | 投影 SRS 是对地理 SRS 应用投影的结果。 投影的 SRS 可以是二维或三维的。 如果投影SRS是三维的，那么它实际上是二维投影SRS和一维垂直SRS的复合SRS。 |
| [ProjectedSpatialReferenceSystemParameters](./projectedspatialreferencesystemparameters) | 用于创建投影 SRS 的参数。一些参数有默认值。 一些参数有合理的默认值，所以你不必只分配它们。 如果将`null`分配给这些参数，将使用默认值。 ProjectionMethodName和Base没有默认值 - 您必须为此属性分配一些非`null`值。 |
| [Projection](./projection) | 表示带参数的投影方法，将（经度，纬度）转换为（x，y）。 |
| [SpatialReferenceSystem](./spatialreferencesystem) | 空间参考系统将坐标映射到地球上的位置。 有不同类型的 SRS，请参阅Type。 此外，如果 SRS 的类型是Geographic或 Projected，SRS 可以是复合的或单一的，参见IsCompound。 |
| [SpatialReferenceSystemTransformation](./spatialreferencesystemtransformation) | 空间参考系统转换将几何图形从源空间参考系统转换为目标空间参考系统。 |
| [TransformationException](./transformationexception) | 在坐标变换过程中或变换创建过程中发生错误时抛出变换异常。 |
| [Unit](./unit) | 表示测量单位。 |
| [VerticalDatum](./verticaldatum) | 表示用于垂直测量的方法。 |
| [VerticalSpatialReferenceSystem](./verticalspatialreferencesystem) | 垂直 SRS 是描述高度坐标的一维 SRS。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AxisDirection](./axisdirection) | 轴方向定义轴指向的方向。 |
| [GeocentricAxisesOrder](./geocentricaxisesorder) | 表示地心 SRS 中的轴顺序。 |
| [GeographicAxisesOrder](./geographicaxisesorder) | 表示地理 SRS 中的轴顺序。 |
| [ParameterType](./parametertype) | 确定[`Projection`](../aspose.gis.spatialreferencing/projection)中的参数类型。 |
| [ProjectedAxisesOrder](./projectedaxisesorder) | 表示地理 SRS 中的轴顺序。 |
| [SpatialReferenceSystemType](./spatialreferencesystemtype) | 表示空间参考系统的类型。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
