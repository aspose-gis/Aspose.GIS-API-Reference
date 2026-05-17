---
title: "GeocentricSpatialReferenceSystemParameters Класс"
type: docs
weight: 60
url: /ru/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Инициализирует новый экземпляр класса GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Порядок осей. По умолчанию [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Датум геоцентрической SRS. По умолчанию [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Единицы измерения, используемые в этой SRS. По умолчанию [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| имя | string | r/w | Имя геоцентрической SRS. По умолчанию "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Главный меридиан этой SRS. По умолчанию [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось геоцентрической SRS, описывающая измерение 'X' (ось, указывающая на главный меридиан). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось геоцентрической SRS, описывающая измерение 'Y' (ось, указывающая влево или вправо от оси X на экваториальной плоскости).<br/>            По умолчанию ось с направлением [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось геоцентрической SRS, описывающая измерение 'Z' (ось, указывающая на северный или южный полюс).<br/>            По умолчанию ось с направлением [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Инициализирует новый экземпляр класса GeocentricSpatialReferenceSystemParameters

