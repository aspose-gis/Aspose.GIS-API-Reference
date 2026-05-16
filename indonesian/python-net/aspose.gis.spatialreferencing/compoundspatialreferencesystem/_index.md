---
title: "Kelas CompoundSpatialReferenceSystem"
type: docs
weight: 30
url: /id/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Kembalikan ini. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Mengembalikan SRS ini yang dikonversi ke [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Gunakan [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) untuk mengetahui apakah konversi memungkinkan. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Kembalikan representasi geografis dari SRS ini. Jika SRS gabungan ini memang merepresentasikan SRS geografis, hasilnya akan<br/> menjadi SRS geografis tiga dimensi (dengan dimensi longitude, latitude, tinggi). Jika tidak, sebuah pengecualian akan dilempar. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Mengembalikan SRS ini yang dikonversi ke [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/> Gunakan [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) untuk mengetahui apakah konversi memungkinkan. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Kembalikan representasi proyeksi dari SRS ini. Jika SRS gabungan ini memang merepresentasikan SRS proyeksi, hasilnya akan<br/> menjadi SRS proyeksi tiga dimensi (dengan dimensi X, Y, tinggi). Jika tidak, sebuah pengecualian akan dilempar. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Mengembalikan SRS ini yang dikonversi ke [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/> Gunakan [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) untuk mengetahui apakah konversi memungkinkan. |
| dimensions_count | int | r | Jumlah dimensi. Untuk SRS gabungan ini adalah jumlah dimensi dari SRS dasar. |
| epsg_code | int | r | Jika pengenal objek ini adalah pengenal EPSG - kembalikan kodenya. Jika tidak - kembalikan -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistem referensi spasial ETRS 89 (EPSG:4258). |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistem referensi spasial ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035). |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistem referensi spasial ETRS 89 / Lambert Conformal Conic (EPSG:3034). |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Kembalikan datum geografis dari SRS ini.<br/>            Jika kedua [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) dan [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) memiliki datum geografis - kembalikan datum geografis dari head. |
| has_geographic_datum | bool | r | SRS gabungan memiliki datum geografis jika ada SRS dasar yang memiliki datum geografis. |
| has_prime_meridian | bool | r | SRS gabungan memiliki meridian utama jika ada SRS dasar yang memiliki meridian utama. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | SRS dasar pertama. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Pengenal objek yang dapat diidentifikasi ini. |
| is_compound | bool | r | Mengembalikan <see langword="true" />. |
| is_single | bool | r | Mengembalikan apakah SRS ini tunggal (bukan gabungan dari dua SRS). |
| is_valid | bool | r | Sama dengan <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, tetapi tidak mengembalikan pesan kesalahan. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistem referensi spasial NAD 83 (EPSG:4269). |
| nama | string | r | Nama objek ini. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistem referensi spasial OSGB 36 (EPSG:4277). |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistem referensi spasial OSGB 36 / British National Grid (EPSG:27700). |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Kembalikan meridian utama dari SRS ini.<br/>            Jika kedua [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) dan [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) memiliki meridian utama - kembalikan meridian utama dari head. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | SRS dasar kedua. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Tipe dari SRS Gabungan ini. Bisa berupa [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) jika<br/>            SRS Gabungan ini merupakan kombinasi dari SRS geografis dan vertikal, atau [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) jika<br/>            SRS Gabungan ini merupakan kombinasi dari SRS terproyeksi dan vertikal. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistem referensi spasial Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistem referensi spasial WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistem referensi spasial WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Buat SRS gabungan. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Buat sistem referensi spasial berdasarkan kode EPSG yang ditentukan. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Membuat <c>SpatialReferenceSystem</c> baru berdasarkan string WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Buat SRS geosentrik dari parameter khusus. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Buat SRS geografis dari parameter khusus. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Buat Sistem Referensi Spasial lokal. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Buat SRS terproyeksi dari parameter khusus. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Membuat transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lainnya. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Buat SRS vertikal. |
| [export_to_wkt()](#export_to_wkt__10) | Mengembalikan representasi SRS ini sebagai string WKT.<br/>            String WKT hasil akan sesuai dengan spesifikasi OGC 01-009, biasanya disebut "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Dapatkan [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) yang menggambarkan dimensi. |
| [get_unit(dimension)](#get_unit_dimension_12) | Dapatkan [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) dari dimensi. |
| [is_equivalent(other)](#is_equivalent_other_13) | Mendeteksi apakah SRS ini setara dengan SRS lain. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Menentukan apakah dua SRS setara.<br/>            Koordinat yang sama dari SRS setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter SRS setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Buat sistem referensi spasial berdasarkan kode EPSG yang ditentukan. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Membuat <c>SpatialReferenceSystem</c> baru berdasarkan string WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Membuat transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lainnya. |
| [validate(error_message)](#validate_error_message_18) | Tentukan apakah SRS ini valid. Lihat <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> untuk deskripsi validitas. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Buat SRS gabungan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama SRS baru. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS kepala dari SRS baru. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS ekor dari SRS baru. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | SRS Gabungan Baru. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Buat sistem referensi spasial berdasarkan kode EPSG yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| epsg | int | Kode EPSG dari sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Sistem referensi spasial baru dengan kode EPSG yang ditentukan. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Membuat <c>SpatialReferenceSystem</c> baru berdasarkan string WKT (Well-Known Text).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkt | string | String WKT. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Baru <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Buat SRS geosentrik dari parameter khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parameter untuk dibuat dari. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | SRS Geosentrik baru. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Buat SRS geografis dari parameter khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parameter untuk dibuat dari. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | SRS Geografis baru. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Buat Sistem Referensi Spasial lokal.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama Sistem Referensi Spasial. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum yang akan digunakan dalam SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unit yang akan digunakan dalam SRS. |
| sumbu | System.Collections.Generic.ICollection<Axis> | Sumbu yang akan digunakan dalam SRS. Harus tidak kosong. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Sistem Referensi Spasial Lokal baru. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Buat SRS terproyeksi dari parameter khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parameter untuk dibuat dari. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | SRS Proyeksi baru. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Membuat transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Lainnya <c>SpatialReferenceSystem</c>. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lain. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Buat SRS vertikal.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama SRS. Jika <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum yang akan digunakan dalam SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unit yang akan digunakan dalam SRS. Jika <see langword=\"null\" />, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) akan digunakan. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Sumbu dengan arah \"up\" atau \"down\", yang akan digunakan dalam SRS. Jika <see langword=\"null\" />, sumbu dengan arah up akan digunakan. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, yang akan dilampirkan ke SRS. Melampirkan Identifier tidak akan mengubah parameter SRS lainnya.<br/>            Terserah Anda untuk memastikan konsistensi identifier dan parameter SRS. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | SRS Vertikal baru. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Mengembalikan representasi SRS ini sebagai string WKT.<br/>            String WKT hasil akan sesuai dengan spesifikasi OGC 01-009, biasanya disebut "WKT1".

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi WKT dari SRS ini. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Dapatkan [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) yang menggambarkan dimensi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dimensi | int | Jumlah dimensi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Sumbu yang menggambarkan dimensi. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Dapatkan [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) dari dimensi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dimensi | int | Jumlah dimensi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unit dimensi. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Mendeteksi apakah SRS ini setara dengan SRS lain. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS lain. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, menunjukkan apakah SRS ini setara dengan SRS lain. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Menentukan apakah dua SRS setara.<br/>            Koordinat yang sama dari SRS setara menunjukkan tempat yang sama di Bumi.<br/>            Beberapa parameter SRS setara dapat berbeda, misalnya [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS pertama. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS kedua. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, menunjukkan apakah dua SRS setara. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Buat sistem referensi spasial berdasarkan kode EPSG yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| epsg | int | Kode EPSG dari sistem referensi spasial. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ketika metode ini mengembalikan <see langword=\"true\" />, berisi SRS dengan kode EPSG yang ditentukan; jika tidak,<br/>            berisi <see langword=\"null\" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika kode EPSG yang ditentukan diketahui dan SRS telah dibuat; <see langword=\"false\" /> jika tidak. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Membuat <c>SpatialReferenceSystem</c> baru berdasarkan string WKT (Well-Known Text).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkt | string | String WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ketika metode ini mengembalikan <see langword=\"true\" />, berisi SRS yang dibuat dari WKT; jika tidak,<br/>            berisi <see langword=\"null\" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika SRS berhasil dibuat; <see langword=\"false\" /> jika tidak. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Membuat transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Lainnya <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Ketika metode ini mengembalikan <see langword=\"true\" />, berisi transformasi; jika tidak, berisi <see langword=\"null\" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Transformasi dari <c>SpatialReferenceSystem</c> ini ke <c>SpatialReferenceSystem</c> lain. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Tentukan apakah SRS ini valid. Lihat <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> untuk deskripsi validitas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pesan_error | String | Deskripsi ketidakvalidan (jika hasilnya <see langword="false" />) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Jika SRS ini valid - <see langword="true" />, jika tidak - <see langword="false" />. |


