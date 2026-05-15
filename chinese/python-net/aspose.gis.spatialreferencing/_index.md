---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /zh/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **类** | **描述** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | 轴描述 SRS 的一个维度。 |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | 包含 Bursa-Wolf 公式参数以转换到其他基准的类。 |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | 复合 SRS 将两个底层 SRS 组合在一起，且这两个 SRS 都不能是复合的。 |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | 椭球体表示一个近似地球的椭球体。 |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | 地心 SRS 是以地球中心为原点的三维笛卡尔 SRS。 |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | 用于创建地心 SRS 的参数。<br/> 参数具有合理的默认值，因此您只需分配其中的一部分。<br/> 如果将 <see langword="null" /> 分配给任何参数，将使用默认值。 |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | 地理基准将经度和纬度关联到地球上的特定位置。 |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | 地理 SRS 是基于经度和纬度的 SRS。<br/> 地理 SRS 可以是二维的或三维的。<br/> 如果地理 SRS 是三维的，则它实际上是由二维 SRS 和垂直 SRS 组成的复合 SRS。 |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | 用于创建地理 SRS 的参数。<br/> 参数具有合理的默认值，因此您只需分配其中的一部分。<br/> 如果将 <see langword="null" /> 分配给任何参数，将使用默认值。 |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | 表示可能具有 EPSG 代码和名称的对象。 |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | 表示标识符——对象外部描述的引用。<br/> 如果您从 WKT 创建 SRS，[Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) 对应于 "AUTHORITY" 关键字。 |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | 指示在本地空间参考系统中用于测量的方法。 |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | 本地 SRS 相关坐标指向某个对象，而非地球。 |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | 本初子午线表示经度被定义为 0 的子午线。 |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | 投影 SRS 是将投影应用于地理 SRS 的结果。<br/>            投影 SRS 可以是二维的或三维的。<br/>            如果投影 SRS 是三维的，则它实际上是由二维投影 SRS 和一维垂直 SRS 组成的复合 SRS。 |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | 用于创建投影 SRS 的参数。部分参数有默认值。<br/>            某些参数具有合理的默认值，因此您不必仅为它们赋值。<br/>            如果您将 <see langword="null" /> 赋给这些参数，将使用默认值。<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) 和 [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) 没有默认值 -<br/>            您必须为这些属性赋予非 <see langword="null" /> 的值。 |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | 表示一种带参数的投影方法，将 (经度, 纬度) 转换为 (x, y)。 |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空间参考系统将坐标映射到地球上的位置。<br/>            有不同类型的 SRS，参见 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。<br/>            更进一步，如果 SRS 的类型是 [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) 或<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/)，SRS 可以是复合的或单一的，参见 [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。 |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | 空间参考系统转换将几何体从源空间参考系统转换到目标空间参考系统。 |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | 当坐标转换或转换创建过程中出现错误时，会抛出转换异常。 |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | 表示测量单位。 |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | 指示用于垂直测量的方法。 |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | 垂直 SRS 是描述高度坐标的一维 SRS。 |
## **Enumerations**
| **枚举** | **描述** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | 轴方向定义轴指向的方向。 |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | 表示地心 SRS 中轴的顺序。 |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | 表示地理 SRS 中轴的顺序。 |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | 确定 [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) 中参数的类型。 |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | 表示地理 SRS 中轴的顺序。 |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | 表示空间参考系统的类型。 |
