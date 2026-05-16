---
title: "Kelas GeographicSpatialReferenceSystemParameters"
type: docs
weight: 90
url: /id/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | Menginisialisasi instance baru dari kelas GeographicSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unit yang akan digunakan dalam SRS ini. Default adalah [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | Urutan sumbu. Default ke [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum SRS geografis. Default adalah [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu yang menggambarkan lintang. Default adalah sumbu dengan arah utara. |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu yang menggambarkan bujur. Default adalah sumbu dengan arah timur. |
| nama | string | r/w | Nama SRS geografis. Default adalah "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Meridian utama dari SRS ini. Defaultnya [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

Menginisialisasi instance baru dari kelas GeographicSpatialReferenceSystemParameters

