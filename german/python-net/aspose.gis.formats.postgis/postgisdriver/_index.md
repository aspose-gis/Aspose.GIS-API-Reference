---
title: "PostGisDriver Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Ermöglicht den Beginn des Prozesses zur Konfiguration der Datenquelle [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) für die weitere Arbeit damit. |
| [from_query(query)](#from_query_query_2) | Konfiguration der Datenquelle für benutzerdefinierte Datenbankabfragen. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Ermöglicht den Beginn des Prozesses zur Konfiguration der Datenquelle [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) für die weitere Arbeit damit.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| table_name | string | Name der Datenbanktabelle, aus der die Daten extrahiert werden |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Konfiguration der Datenquelle für benutzerdefinierte Datenbankabfragen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| query | string | Abfrage‑String. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


