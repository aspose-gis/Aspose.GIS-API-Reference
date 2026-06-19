---
title: "类 GeocentricSpatialReferenceSystemParameters"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.GeocentricSpatialReferenceSystemParameters 类。用于创建地心 SRS 的参数。这些参数具有合理的默认值，因此您只需分配其中的一部分。如果对任何参数赋值为 null，将使用默认值。"
type: docs
weight: 4550
url: /zh/net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---
## GeocentricSpatialReferenceSystemParameters class

用于创建地心 SRS 的参数。这些参数具有合理的默认值，因此您只需分配其中的一部分。如果将 `null` 分配给任何参数，将使用默认值。

```csharp
public class GeocentricSpatialReferenceSystemParameters
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GeocentricSpatialReferenceSystemParameters](geocentricspatialreferencesystemparameters/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AxisesOrder](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/axisesorder/) { get; set; } | 轴的顺序。默认是 XYZ。 |
| [Datum](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/datum/) { get; set; } | 地心 SRS 的基准面。默认是 [`Wgs84`](../geographicdatum/wgs84/)。 |
| [LinearUnit](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/linearunit/) { get; set; } | 此 SRS 使用的单位。默认是 [`Meter`](../unit/meter/)。 |
| [Name](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/name/) { get; set; } | 地心 SRS 的名称。默认是 "Unnamed"。 |
| [PrimeMeridian](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/primemeridian/) { get; set; } | 此 SRS 的本初子午线。默认是 [`Greenwich`](../primemeridian/greenwich/)。 |
| [XAxis](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/xaxis/) { get; set; } | 描述 'X' 维度的地心 SRS 轴（指向本初子午线的轴）。 |
| [YAxis](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/yaxis/) { get; set; } | 描述 'Y' 维度的地心 SRS 轴（在赤道平面上指向 X 轴左侧或右侧的轴）。默认是指向东向的轴。 |
| [ZAxis](../../aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/zaxis/) { get; set; } | 描述 'Z' 维度的地心 SRS 轴（指向北极或南极的轴）。默认是指向北向的轴。 |

### 另见

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


