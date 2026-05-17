---
title: "GeographicSpatialReferenceSystemParameters Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | GeographicSpatialReferenceSystemParameters sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Bu SRS'de kullanılacak birimler. Varsayılan [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | Eksenlerin sırası. Varsayılan [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) dir. |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Coğrafi SRS'nin datum'u. Varsayılan [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) dir. |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Enlemi tanımlayan eksen. Varsayılan, kuzey yönünde bir eksendir. |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Boylamı tanımlayan eksen. Varsayılan, doğu yönünde bir eksendir. |
| ad | string | r/w | Coğrafi SRS'nin adı. Varsayılan "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Bu SRS'nin baş meridyeni. Varsayılan değer [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

GeographicSpatialReferenceSystemParameters sınıfının yeni bir örneğini başlatır

