---
title: "DatabaseExternalSrsSettingsBuilder klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Slutför konfigurationen av den externa srs och returnera den överordnade kontexten. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Anger speciella fältnamn som information om ytterligare begärda rumsliga referenssystem ska läsas från. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Slutför konfigurationen av den externa srs och returnera den överordnade kontexten.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Anger speciella fältnamn som information om ytterligare begärda rumsliga referenssystem ska läsas från.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| auth_srid_field | string | Fält för att läsa rumsligt referens‑id, standard: auth_srid. |
| sr_text_field | string | Fält för att läsa det rumsliga koordinatsystemet representerat av WKT, standard: srtext. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


