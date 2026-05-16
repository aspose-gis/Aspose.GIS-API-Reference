---
title: "Kelas DatabaseQueryDataSourceBuilder"
type: docs
weight: 40
url: /id/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Mengonfigurasi nama bidang yang akan berisi informasi untuk atribut fitur. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Konfigurasikan lapisan yang dihasilkan untuk melacak perubahan dan buat sumber data untuk menyinkronkan perubahan yang dibuat. |
| [build()](#build__3) | Metode ini mengambil implementasi dari [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Mengonfigurasi nama bidang dari mana geometri akan diekstrak. |
| [srid_field(name)](#srid_field_name_5) | Mengonfigurasi nama bidang kueri yang akan berisi pengidentifikasi sistem referensi spasial (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Memungkinkan Anda mengonfigurasi sumber data untuk menggunakan data sistem referensi spasial pihak ketiga, melewati data yang telah dipasang sebelumnya dalam pustaka Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Mengonfigurasi nama bidang yang akan berisi informasi untuk atribut fitur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama bidang kueri untuk atribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipe data ke mana data dari basis data harus dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Konfigurasikan lapisan yang dihasilkan untuk melacak perubahan dan buat sumber data untuk menyinkronkan perubahan yang dibuat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| table_name | string | Nama tabel tempat perubahan akan dilakukan. |
| identity_attribute | string | Sebuah atribut dari fitur yang akan diperlakukan sebagai pengidentifikasi unik fitur tersebut. |
| overwrite_same_key | bool | Jika flag ini diatur ke true, maka fitur yang baru ditambahkan dengan pengidentifikasi unik yang sama dengan yang sudah ada di lapisan akan ditimpa, dan data akan dibaca sebagai diperbarui jika ditemukan perbedaan. |
| db_func | string | Fungsi yang akan disediakan dalam kueri SQL untuk mengubah data biner menjadi representasi data geografis dari basis data saat ini. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Metode ini mengambil implementasi dari [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementasi dari [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Mengonfigurasi nama bidang dari mana geometri akan diekstrak.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama bidang gemetry. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Mengonfigurasi nama bidang kueri yang akan berisi pengidentifikasi sistem referensi spasial (srid).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama bidang kueri yang berisi pengidentifikasi sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Memungkinkan Anda mengonfigurasi sumber data untuk menggunakan data sistem referensi spasial pihak ketiga, melewati data yang telah dipasang sebelumnya dalam pustaka Aspose.GIS.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| srs_query | string | Kueri untuk mengambil informasi tentang sistem koordinat spasial tambahan yang digunakan dalam kueri utama untuk mengambil fitur. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


