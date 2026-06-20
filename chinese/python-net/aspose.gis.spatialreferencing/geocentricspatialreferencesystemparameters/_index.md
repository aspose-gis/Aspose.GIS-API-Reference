---
title: "GeocentricSpatialReferenceSystemParameters 类"
type: docs
weight: 60
url: /zh/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | 初始化 GeocentricSpatialReferenceSystemParameters 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | 轴的顺序。默认值为 [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/)。 |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | 地心 SRS 的基准面。默认值为 [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/)。 |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 此 SRS 使用的单位。默认值为 [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)。 |
| 名称 | string | r/w | 地心 SRS 的名称。默认值为 "Unnamed"。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | 此 SRS 的本初子午线。默认值为 [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/)。 |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述 'X' 维度的地心 SRS 轴（指向本初子午线的轴）。 |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述 'Y' 维度的地心 SRS 轴（在赤道平面上指向 X 轴左侧或右侧的轴）。<br/>            默认轴方向为 [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/)。 |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述 'Z' 维度的地心 SRS 轴（指向北极或南极的轴）。<br/>            默认轴方向为 [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/)。 |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

初始化 GeocentricSpatialReferenceSystemParameters 类的新实例

