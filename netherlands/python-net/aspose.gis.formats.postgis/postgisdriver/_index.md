---
title: "PostGisDriver Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Staat het starten van het proces toe om de gegevensbron [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) te configureren voor verder gebruik. |
| [from_query(query)](#from_query_query_2) | De gegevensbron configureren voor aangepaste database‑query's. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Staat het starten van het proces toe om de gegevensbron [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) te configureren voor verder gebruik.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| table_name | string | Naam van de databasetabel waaruit de gegevens worden geëxtraheerd |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

De gegevensbron configureren voor aangepaste database‑query's.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| query | string | Query‑string. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


