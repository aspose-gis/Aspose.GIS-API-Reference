---
title: "Kelas IRasterValues"
type: docs
weight: 30
url: /id/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"bool\" />. |
| [as_byte(band_index)](#as_byte_band_index_2) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"byte\" />. |
| [as_double(band_index)](#as_double_band_index_3) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"double\" />. |
| [as_float(band_index)](#as_float_band_index_4) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"float\" />. |
| [as_integer(band_index)](#as_integer_band_index_5) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"int\" />. |
| [as_long(band_index)](#as_long_band_index_6) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"long\" />. |
| [as_short(band_index)](#as_short_band_index_7) | Mengonversi data band yang ditentukan menjadi nilai <see langword=\"short\" />. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Memeriksa apakah nilai mewakili latar belakang atau 'tidak ada data' dalam band yang ditentukan. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Mendapatkan tipe nilai. |
| [is_null(band_index)](#is_null_band_index_10) | Memeriksa apakah nilai raster telah diatur dalam band yang ditentukan. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"bool\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai yang dikonversi. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"byte\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Nilai yang dikonversi. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"double\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Nilai yang dikonversi. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"float\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float | Nilai yang dikonversi. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"int\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai yang dikonversi. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"long\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Nilai yang dikonversi. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Mengonversi data band yang ditentukan menjadi nilai <see langword=\"short\" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| short | Nilai yang dikonversi. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Memeriksa apakah nilai mewakili latar belakang atau 'tidak ada data' dalam band yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Kembalikan 'true' jika mewakili latar belakang atau 'tidak ada data'. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Mendapatkan tipe nilai.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | Tipe nilai. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Memeriksa apakah nilai raster telah diatur dalam band yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Kembalikan 'false' jika tidak ada. |


