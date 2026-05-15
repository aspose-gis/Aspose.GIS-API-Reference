---
title: "DatabaseExternalSrsSettingsBuilder Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Vervollständigen Sie die Konfiguration des externen srs und geben Sie den übergeordneten Kontext zurück. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Gibt spezielle Feldnamen an, aus denen Informationen über zusätzlich angeforderte räumliche Referenzsysteme gelesen werden können. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Vervollständigen Sie die Konfiguration des externen srs und geben Sie den übergeordneten Kontext zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Gibt spezielle Feldnamen an, aus denen Informationen über zusätzlich angeforderte räumliche Referenzsysteme gelesen werden können.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| auth_srid_field | string | Feld zum Lesen der räumlichen Referenz-ID, Standard: auth_srid. |
| sr_text_field | string | Feld zum Lesen des räumlichen Koordinatensystems, das durch WKT dargestellt wird, Standard: srtext. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


