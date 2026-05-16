---
title: "Kelas GeographicDatum"
type: docs
weight: 70
url: /id/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, digunakan dalam datum ini untuk mendekati Bumi. |
| epsg_code | int | r | Jika pengenal objek ini adalah pengenal EPSG - kembalikan kodenya. Jika tidak - kembalikan -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Pengenal objek yang dapat diidentifikasi ini. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum NAD 83. |
| nama | string | r | Nama objek ini. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters yang dapat digunakan untuk mengubah koordinat dalam datum ini menjadi koordinat dalam datum WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 84. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Menentukan apakah dua datum setara.<br/>            Koordinat yang sama dari datum yang setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter dari datum yang setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Menentukan apakah dua datum setara.<br/>            Koordinat yang sama dari datum yang setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter dari datum yang setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama datum ini. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid dari datum ini. Tidak boleh null. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parameter, yang dapat diberikan ke formula bursa wolf, untuk mengonversi koordinat dalam datum ini menjadi koordinat dalam datum WGS84.<br/>            Jika datum ini dekat dengan WGS84 dan tidak diperlukan transformasi, berikan parameter bursa wolf dengan semua nilai diatur ke 0.<br/>            Jika null, ToWgs84 akan diatur ke parameter [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Pengidentifikasi datum ini. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Menentukan apakah dua datum setara.<br/>            Koordinat yang sama dari datum yang setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter dari datum yang setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Datum pertama. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Datum kedua. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, yang menunjukkan apakah dua datum setara. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Menentukan apakah dua datum setara.<br/>            Koordinat yang sama dari datum yang setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter dari datum yang setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Datum lain. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, yang menunjukkan apakah dua datum setara. |


