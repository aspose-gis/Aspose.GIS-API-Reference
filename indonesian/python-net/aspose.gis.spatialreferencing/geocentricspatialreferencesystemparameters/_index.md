---
title: "Kelas GeocentricSpatialReferenceSystemParameters"
type: docs
weight: 60
url: /id/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Menginisialisasi sebuah instance baru dari kelas GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Urutan sumbu. Defaultnya [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum dari SRS geosentrik. Defaultnya adalah [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Satuan yang akan digunakan dalam SRS ini. Defaultnya [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nama | string | r/w | Nama SRS geosentrik. Defaultnya adalah "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Meridian utama dari SRS ini. Defaultnya [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu SRS geosentrik yang menggambarkan dimensi 'X' (sumbu yang mengarah ke meridian utama). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu SRS geosentrik yang menggambarkan dimensi 'Y' (sumbu yang mengarah ke kiri atau kanan sumbu X pada bidang ekuatorial).<br/>            Defaultnya sumbu dengan arah [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu SRS geosentrik yang menggambarkan dimensi 'Z' (sumbu yang mengarah ke kutub utara atau selatan).<br/>            Defaultnya sumbu dengan arah [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Menginisialisasi sebuah instance baru dari kelas GeocentricSpatialReferenceSystemParameters

