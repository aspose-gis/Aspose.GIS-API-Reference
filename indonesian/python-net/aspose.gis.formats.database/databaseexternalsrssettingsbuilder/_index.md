---
title: "Kelas DatabaseExternalSrsSettingsBuilder"
type: docs
weight: 30
url: /id/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Selesaikan konfigurasi srs eksternal dan kembalikan konteks induk. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Menentukan nama bidang khusus yang digunakan untuk membaca informasi tentang sistem referensi spasial yang diminta tambahan. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Selesaikan konfigurasi srs eksternal dan kembalikan konteks induk.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Menentukan nama bidang khusus yang digunakan untuk membaca informasi tentang sistem referensi spasial yang diminta tambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| auth_srid_field | string | Bidang untuk membaca id referensi spasial, default: auth_srid. |
| sr_text_field | string | Bidang untuk membaca sistem koordinat spasial yang direpresentasikan oleh WKT, default: srtext. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


