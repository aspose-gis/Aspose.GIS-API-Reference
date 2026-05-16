---
title: "Kelas ImageMetadataReader"
type: docs
weight: 30
url: /id/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Membuat instance pembaca untuk tag EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Membuat instance pembaca untuk tag EXIF |
| [read_data()](#read_data__3) | Mengekstrak semua tag EXIF yang didukung |
| [save(file_name)](#save_file_name_4) | Simpan ke file baru karena file asli terkunci untuk perubahan |
| [save(file_name, format)](#save_file_name_format_5) | Simpan ke file baru karena file asli terkunci untuk perubahan |
| [save(stream)](#save_stream_6) | Menyimpan perubahan ke aliran terpisah |
| [save(stream, format)](#save_stream_format_7) | Menyimpan perubahan ke aliran terpisah |
| [set_artist(artist)](#set_artist_artist_8) | Menyimpan tag EXIF Artist, menambah atau menimpa data. |
| [set_description(description)](#set_description_description_9) | Menyimpan tag EXIF ImageDescription, menambahkan atau menimpa data. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Menyimpan tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, dan GPSLongitude, menambahkan atau menimpa data. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Menyimpan tag EXIF ImageWidth dan ImageHeight, menambahkan atau menimpa data. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Menyimpan tag EXIF ModifyDate (DataTime), menambahkan atau menimpa data. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Ia mencoba menemukan tag EXIF Artist, jika tag tidak ditemukan ia mengembalikan null |
| [try_get_description(description)](#try_get_description_description_14) | Ia mencoba menemukan tag EXIF ImageDescription, jika tag tidak ditemukan ia mengembalikan null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Ia mencoba menemukan sekumpulan tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, jika tag tidak ada ia mengembalikan null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Ia mencoba menemukan sekumpulan tag EXIF ImageWidth dan ImageHeight, jika tag tidak ada ia mengembalikan null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Ia mencoba menemukan tag EXIF ModifyDate (DataTime), jika tag tidak ditemukan ia mengembalikan nilai default DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Membuat instance pembaca untuk tag EXIF

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | string | Nama lengkap file gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instansi pembaca metadata |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Membuat instance pembaca untuk tag EXIF

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | _io.BufferedRandom | Aliran sumber data gambar |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instansi pembaca metadata |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Mengekstrak semua tag EXIF yang didukung

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData yang mewakili sekumpulan tag yang didukung |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Simpan ke file baru karena file asli terkunci untuk perubahan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | string | Nama lengkap file tujuan |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Simpan ke file baru karena file asli terkunci untuk perubahan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | string | Nama lengkap file tujuan |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Menentukan format untuk penyimpanan |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Menyimpan perubahan ke aliran terpisah

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | _io.BufferedRandom | Aliran tujuan |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Menyimpan perubahan ke aliran terpisah

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | _io.BufferedRandom | Aliran tujuan |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Menentukan format untuk penyimpanan |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Menyimpan tag EXIF Artist, menambah atau menimpa data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| artist | string | Artis. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Menyimpan tag EXIF ImageDescription, menambahkan atau menimpa data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string | Deskripsi. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Menyimpan tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, dan GPSLongitude, menambahkan atau menimpa data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| latitude | double | Lintang. |
| longitude | double | Bujur. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Menyimpan tag EXIF ImageWidth dan ImageHeight, menambahkan atau menimpa data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Lebar. |
| tinggi | int | Tinggi. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Menyimpan tag EXIF ModifyDate (DataTime), menambahkan atau menimpa data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| modify_date | datetime | Tanggal modifikasi. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Ia mencoba menemukan tag EXIF Artist, jika tag tidak ditemukan ia mengembalikan null

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| artist | String | Artis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar jika berhasil |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Ia mencoba menemukan tag EXIF ImageDescription, jika tag tidak ditemukan ia mengembalikan null

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | String | Deskripsi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar jika berhasil |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Ia mencoba menemukan sekumpulan tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, jika tag tidak ada ia mengembalikan null

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Lokasi geo. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar jika berhasil |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Ia mencoba menemukan sekumpulan tag EXIF ImageWidth dan ImageHeight, jika tag tidak ada ia mengembalikan null

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Ukuran gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar jika berhasil |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Ia mencoba menemukan tag EXIF ModifyDate (DataTime), jika tag tidak ditemukan ia mengembalikan nilai default DataTime

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| modify_date | datetime[] | Tanggal modifikasi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Benar jika berhasil |


