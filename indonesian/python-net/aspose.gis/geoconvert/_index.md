---
title: "Kelas GeoConvert"
type: docs
weight: 1140
url: /id/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Mengembalikan posisi yang dihitung sebagai string dalam format yang ditentukan. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Mengembalikan posisi yang dihitung sebagai string dalam format yang ditentukan. |
| [parse_point_text(text)](#parse_point_text_text_3) | Mengonversi string yang berisi koordinat menjadi objek IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Mengonversi string yang berisi koordinat menjadi objek IPoint. Nilai kembali menunjukkan apakah konversi berhasil atau gagal. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Mengembalikan posisi yang dihitung sebagai string dalam format yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| latitude | double | Lintang posisi. |
| longitude | double | Bujur posisi. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format hasil. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Posisi sebagai string. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Mengembalikan posisi yang dihitung sebagai string dalam format yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objek IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format hasil. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Posisi sebagai string. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Mengonversi string yang berisi koordinat menjadi objek IPoint.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | string | String yang berisi koordinat untuk dikonversi.<br/>            String harus berisi baik lintang maupun bujur koordinat.<br/>            Koordinat harus dipisahkan oleh spasi, koma, atau titik koma. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objek IPoint dengan koordinat yang setara dengan string input. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Mengonversi string yang berisi koordinat menjadi objek IPoint. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | string | String yang berisi koordinat untuk dikonversi.<br/>            String harus berisi baik lintang maupun bujur koordinat.<br/>            Koordinat harus dipisahkan oleh spasi, koma, atau titik koma. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Saat metode ini mengembalikan, berisi objek IPoint dengan koordinat yang diurai, jika konversi berhasil, atau null jika konversi gagal. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | True jika teks berhasil diurai, jika tidak False. |


