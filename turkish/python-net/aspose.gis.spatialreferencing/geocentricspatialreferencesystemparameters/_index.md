---
title: "GeocentricSpatialReferenceSystemParameters Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | GeocentricSpatialReferenceSystemParameters sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Eksen sırası. Varsayılan değer [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Geocentric SRS'nin datum'u. Varsayılan değer [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Bu SRS'de kullanılacak birimler. Varsayılan değer [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| ad | string | r/w | Geocentric SRS'nin adı. Varsayılan değer \"Unnamed\". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Bu SRS'nin baş meridyeni. Varsayılan değer [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Geocentric SRS'nin 'X' boyutunu tanımlayan eksen (baş meridyene işaret eden eksen). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Geocentric SRS'nin 'Y' boyutunu tanımlayan eksen (ekvator düzleminde X ekseninin soluna ya da sağına işaret eden eksen).<br/>            Varsayılan değer [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) yönündeki eksen. |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Geocentric SRS'nin 'Z' boyutunu tanımlayan eksen (kuzey ya da güney kutbuna işaret eden eksen).<br/>            Varsayılan değer [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) yönündeki eksen. |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

GeocentricSpatialReferenceSystemParameters sınıfının yeni bir örneğini başlatır

