---
title: "DatabaseExternalSrsSettingsBuilder Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Harici srs yapılandırmasını tamamlayın ve üst bağlamı döndürün. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Ek olarak istenen mekansal referans sistemleri hakkında bilgi okumak için kullanılacak özel alan adlarını belirtir. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Harici srs yapılandırmasını tamamlayın ve üst bağlamı döndürün.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Ek olarak istenen mekansal referans sistemleri hakkında bilgi okumak için kullanılacak özel alan adlarını belirtir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| auth_srid_field | string | Mekansal referans kimliğini okumak için alan, varsayılan: auth_srid. |
| sr_text_field | string | WKT ile temsil edilen mekansal koordinat sistemini okumak için alan, varsayılan: srtext. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


