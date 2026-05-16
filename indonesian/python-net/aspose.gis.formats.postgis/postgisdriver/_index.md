---
title: "PostGisDriver Kelas"
type: docs
weight: 10
url: /id/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Mengizinkan memulai proses konfigurasi sumber data [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) untuk pekerjaan lebih lanjut dengan itu. |
| [from_query(query)](#from_query_query_2) | Mengonfigurasi sumber data untuk kueri basis data khusus. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Mengizinkan memulai proses konfigurasi sumber data [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) untuk pekerjaan lebih lanjut dengan itu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| table_name | string | Nama tabel basis data dari mana data akan diekstrak |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Mengonfigurasi sumber data untuk kueri basis data khusus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| query | string | String kueri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


