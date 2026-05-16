---
title: "Kelas Elipsoid"
type: docs
weight: 40
url: /id/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Membuat Elipsoid baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid Airy. |
| epsg_code | int | r | Jika pengenal objek ini adalah pengenal EPSG - kembalikan kodenya. Jika tidak - kembalikan -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Pengenal objek yang dapat diidentifikasi ini. |
| inverse_flattening | double | r | Flattening inversi ellipsoid. 0 jika ini adalah bola. |
| is_sphere | bool | r | Mendeteksi apakah ellipsoid ini adalah bola. |
| is_valid | bool | r | Mendeteksi apakah ellipsoid valid: sumbu semi mayornya lebih dari 0 dan flattening inversi positif atau sama dengan 0. |
| nama | string | r | Nama objek ini. |
| semi_major_axis | double | r | Sumbu semi mayor ellipsoid. |
| semi_minor_axis | double | r | Sumbu semi minor ellipsoid. Sama dengan sumbu semi mayor jika ini adalah bola. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid WGS 84. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Menentukan apakah dua ellipsoid setara.<br/>            Jika ellipsoid A setara dengan ellipsoid B, maka mereka memiliki sumbu semi mayor yang sama dan flattening inversi yang sama. |
| [is_equivalent(other)](#is_equivalent_other_2) | Menentukan apakah dua ellipsoid setara.<br/>            Jika ellipsoid A setara dengan ellipsoid B, maka mereka memiliki sumbu semi mayor yang sama dan flattening inversi yang sama. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Membuat Elipsoid baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama ellipsoid. |
| semi_major_axis | double | Sumbu semi mayor ellipsoid. |
| inverse_flattening | double | Flattening inversi ellipsoid. Harus 0 untuk membuat spheroid. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Pengidentifikasi ellipsoid. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Menentukan apakah dua ellipsoid setara.<br/>            Jika ellipsoid A setara dengan ellipsoid B, maka mereka memiliki sumbu semi mayor yang sama dan flattening inversi yang sama.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid pertama. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid kedua. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, menunjukkan apakah dua ellipsoid setara. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Menentukan apakah dua ellipsoid setara.<br/>            Jika ellipsoid A setara dengan ellipsoid B, maka mereka memiliki sumbu semi mayor yang sama dan flattening inversi yang sama.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid lain. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | nilai bool, menunjukkan apakah dua ellipsoid setara. |


