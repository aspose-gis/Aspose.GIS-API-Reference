---
title: "DatabaseExternalSrsSettingsBuilder Classe"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Complétez la configuration du srs externe et renvoyez le contexte parent. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Spécifie les noms de champs spéciaux à partir desquels lire les informations sur les systèmes de référence spatiale supplémentaires demandés. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Complétez la configuration du srs externe et renvoyez le contexte parent.

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Spécifie les noms de champs spéciaux à partir desquels lire les informations sur les systèmes de référence spatiale supplémentaires demandés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| auth_srid_field | string | Champ pour lire l'identifiant de référence spatiale, par défaut : auth_srid. |
| sr_text_field | string | Champ pour lire le système de coordonnées spatiales représenté par WKT, par défaut : srtext. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


