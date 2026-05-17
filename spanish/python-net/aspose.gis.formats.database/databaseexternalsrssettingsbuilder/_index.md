---
title: "Clase DatabaseExternalSrsSettingsBuilder"
type: docs
weight: 30
url: /es/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Complete la configuración del srs externo y devuelva el contexto padre. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Especifica nombres de campos especiales desde los cuales leer información sobre sistemas de referencia espacial solicitados adicionalmente. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Complete la configuración del srs externo y devuelva el contexto padre.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Especifica nombres de campos especiales desde los cuales leer información sobre sistemas de referencia espacial solicitados adicionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| auth_srid_field | string | Campo para leer el id de referencia espacial, por defecto: auth_srid. |
| sr_text_field | string | Campo para leer el sistema de coordenadas espaciales representado por WKT, por defecto: srtext. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


