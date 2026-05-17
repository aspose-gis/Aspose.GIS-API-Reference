---
title: "PostGisDriver klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Tillåter påbörjandet av processen att konfigurera datakällan [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) för vidare arbete med den. |
| [from_query(query)](#from_query_query_2) | Konfigurering av datakällan för anpassade databasfrågor. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Tillåter påbörjandet av processen att konfigurera datakällan [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) för vidare arbete med den.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| table_name | string | Namnet på databastabellen som datan ska extraheras från |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Konfigurering av datakällan för anpassade databasfrågor.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| query | string | Frågesträng. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


