---
title: "Kelas MultiStreamPath"
type: docs
weight: 2760
url: /id/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | Menginisialisasi instance baru dari kelas [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| lokasi | string | r | Mendapatkan representasi string dari lokasi <c>AbstractPath</c> ini. |
| separator | char | r | Mendapatkan karakter pemisah yang digunakan untuk memisahkan tingkat direktori pada string [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [combine(location)](#combine_location_1) | Menggabungkan [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini dengan komponen jalur yang ditentukan. |
| delete() | Menghapus file yang ditunjuk oleh jalur ini. |
| [from_local_path(path)](#from_local_path_path_2) | Membuat [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) yang mewakili lokasi pada sistem berkas lokal. |
| [from_stream(stream)](#from_stream_stream_3) | Membuat [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dari aliran. |
| [get_extension()](#get_extension__4) | Mengembalikan ekstensi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini. |
| [get_file_name()](#get_file_name__5) | Mengembalikan nama berkas dan ekstensi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini. |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Mengembalikan nama berkas dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini tanpa ekstensi. |
| [is_file()](#is_file__7) | Mendapatkan nilai yang menunjukkan apakah jalur ini menunjuk ke berkas yang ada dan dapat dibuka untuk membaca. |
| [list_directory()](#list_directory__8) | Mengembalikan jalur yang berada di dalam <c>AbstractPath</c> ini, jika itu adalah direktori. |
| [open(access)](#open_access_9) | Menyederhanakan sekumpulan format multi‑berkas streaming terbuka menjadi jalur untuk mengakses data. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Mengembalikan [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) baru dengan ekstensi berkas yang diubah ke nilai yang ditentukan. |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

Menginisialisasi instance baru dari kelas [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| entry_file_name | string | Nama berkas entri. |
| file_names | string | Nama‑nama berkas. |
| streams | _io.BufferedRandom[] | Aliran‑aliran tersebut. |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Menggabungkan [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini dengan komponen jalur yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| location | string | Komponen jalur untuk ditambahkan ke [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sebuah [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) baru yang menunjuk ke [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) yang merupakan kombinasi lokasi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini dan<br/>            argumen. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Membuat [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) yang mewakili lokasi pada sistem berkas lokal.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Sebuah jalur pada sistem berkas lokal, seperti <c>"C:\\file.shp"</c> atau <c>"D:\\directory\\"</c>. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sebuah [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) yang mewakili lokasi yang ditentukan oleh <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Membuat [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dari aliran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | _io.BufferedRandom | Aliran untuk membuat [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dari. <c>Aspose.GIS</c> tidak membuang aliran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sebuah instance dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dengan aliran yang ditentukan sebagai isinya. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Mengembalikan ekstensi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Ekstensi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini (termasuk titik ".") atau<br/>            string kosong jika [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) tidak memiliki ekstensi. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Mengembalikan nama berkas dan ekstensi dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Karakter setelah pemisah [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) terakhir dalam [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Jika<br/>            karakter terakhir adalah pemisah [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), string kosong dikembalikan. Jika tidak ada karakter pemisah [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) dalam [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) itu sendiri<br/>            dikembalikan. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Mengembalikan nama berkas dari [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ini tanpa ekstensi.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | String yang dikembalikan oleh [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) dikurangi titik terakhir dan semua karakter setelahnya. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Mendapatkan nilai yang menunjukkan apakah jalur ini menunjuk ke berkas yang ada dan dapat dibuka untuk membaca.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword="true" /> jika lokasi menunjuk ke sebuah berkas; <see langword="false" /> sebaliknya. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Mengembalikan jalur yang berada di dalam <c>AbstractPath</c> ini, jika itu adalah direktori.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Jalur yang berada di dalam <c>AbstractPath</c> ini. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Menyederhanakan sekumpulan format multi‑berkas streaming terbuka menjadi jalur untuk mengakses data.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| akses | System.IO.FileAccess | Menentukan subset operasi yang dapat dilakukan pada sebuah aliran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| _io.BufferedRandom | Ini dapat berupa   atau aliran yang awalnya diberikan oleh klien. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Mengembalikan [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) baru dengan ekstensi berkas yang diubah ke nilai yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_extension | string | Ekstensi baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sebuah [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) baru, yang menunjuk ke berkas dalam direktori yang sama, tetapi dengan ekstensi baru. |


