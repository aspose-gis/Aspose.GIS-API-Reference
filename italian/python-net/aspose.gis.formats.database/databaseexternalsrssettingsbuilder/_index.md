---
title: "Classe DatabaseExternalSrsSettingsBuilder"
type: docs
weight: 30
url: /it/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Completa la configurazione del srs esterno e restituisci il contesto padre. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Specifica i nomi dei campi speciali da cui leggere le informazioni sui sistemi di riferimento spaziale richiesti aggiuntivamente. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Completa la configurazione del srs esterno e restituisci il contesto padre.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Specifica i nomi dei campi speciali da cui leggere le informazioni sui sistemi di riferimento spaziale richiesti aggiuntivamente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| auth_srid_field | string | Campo per leggere l'ID del riferimento spaziale, predefinito: auth_srid. |
| sr_text_field | string | Campo per leggere il sistema di coordinate spaziali rappresentato in WKT, predefinito: srtext. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


