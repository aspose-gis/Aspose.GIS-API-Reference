---
title: "枚举 SpatialReferenceSystemType"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.SpatialReferenceSystemType 枚举。表示空间参考系统的类型"
type: docs
weight: 4720
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystemtype/
---
## SpatialReferenceSystemType enumeration

表示空间参考系统的类型。

```csharp
public enum SpatialReferenceSystemType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Unknown | `0` | 默认值。如果这是具有无效底层 SRS 组合的复合 SRS，则可以从 [`Type`](../spatialreferencesystem/type/) 返回。参见 [`IsCompound`](../spatialreferencesystem/iscompound/)。 |
| Geographic | `1` | Geographic SRS 基于角度经度和角度纬度。Geographic SRS 可以通过 [`AsGeographic`](../spatialreferencesystem/asgeographic/) 方法转换为 [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/)。 |
| Geocentric | `2` | Geocentric SRS 是以地球中心为原点的三维笛卡尔 SRS。Geocentric SRS 可以通过 [`AsGeocentric`](../spatialreferencesystem/asgeocentric/) 方法转换为 [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/)。 |
| Projected | `3` | Projected SRS 基于线性 X 和线性 Y。它是对 Geographic SRS 应用投影的结果。Projected SRS 可以通过 [`AsProjected`](../spatialreferencesystem/asprojected/) 方法转换为 [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/)。 |
| Vertical | `4` | Vertical SRS 描述线性高度坐标。Vertical SRS 可以通过 [`AsVertical`](../spatialreferencesystem/asvertical/) 方法转换为 [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/)。 |
| Local | `5` | Local SRS 将坐标关联到某个对象，而不是地球。Local SRS 可以通过 [`AsLocal`](../spatialreferencesystem/aslocal/) 方法转换为 [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/)。 |

### 另见

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


