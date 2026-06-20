---
title: "GeographicSpatialReferenceSystemParameters 类"
type: docs
weight: 90
url: /zh/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | 初始化 GeographicSpatialReferenceSystemParameters 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 此 SRS 中使用的单位。默认是 [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/)。 |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | 轴的顺序。默认是 [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/)。 |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | 地理 SRS 的基准。默认是 [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/)。 |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述纬度的轴。默认是指向北方的轴。 |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 描述经度的轴。默认是指向东方的轴。 |
| 名称 | string | r/w | 地理 SRS 的名称。默认是 "Unnamed"。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | 此 SRS 的本初子午线。默认值为 [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/)。 |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

初始化 GeographicSpatialReferenceSystemParameters 类的新实例

