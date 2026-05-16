---
title: "DatabaseExternalSrsSettingsBuilder Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Voltooi de configuratie van de externe srs en retourneer de bovenliggende context. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Specificeert speciale veldnamen waaruit informatie over extra aangevraagde ruimtelijke referentiesystemen moet worden gelezen. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Voltooi de configuratie van de externe srs en retourneer de bovenliggende context.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Specificeert speciale veldnamen waaruit informatie over extra aangevraagde ruimtelijke referentiesystemen moet worden gelezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| auth_srid_field | string | Veld voor het lezen van de ruimtelijke referentie-id, standaard: auth_srid. |
| sr_text_field | string | Veld voor het lezen van het ruimtelijke coördinatensysteem weergegeven in WKT, standaard: srtext. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


