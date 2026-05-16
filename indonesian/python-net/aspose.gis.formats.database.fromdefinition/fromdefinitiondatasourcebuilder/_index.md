---
title: "Kelas FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /id/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Mengonfigurasi nama bidang yang akan berisi informasi untuk atribut fitur. |
| [build()](#build__2) | Metode ini mengambil implementasi dari [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Mengonfigurasi nama bidang dari mana geometri akan diekstrak. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Pengaturan wajib yang memungkinkan pelacakan perubahan. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Mengonfigurasi nama bidang yang akan berisi informasi untuk atribut fitur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama bidang basis data untuk atribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipe data ke mana data dari basis data harus dikonversi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Metode ini mengambil implementasi dari [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implementasi dari [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Pengaturan wajib yang memungkinkan pelacakan perubahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Sebuah atribut dari fitur yang akan diperlakukan sebagai pengidentifikasi unik fitur tersebut. |
| overwrite_same_key | bool | Jika flag ini diatur ke true, maka fitur yang baru ditambahkan dengan pengidentifikasi unik yang sama yang sudah ada di lapisan, <br/>            yang saat ini akan ditimpa, dan data akan dibaca sebagai diperbarui jika ditemukan perbedaan.<br/>            Jika tidak, sebuah pengecualian akan dilempar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


