---
title: "PostGisDriver Classe"
type: docs
weight: 10
url: /it/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Consente l'avvio del processo di configurazione dell'origine dati [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) per ulteriori operazioni con essa. |
| [from_query(query)](#from_query_query_2) | Configurazione dell'origine dati per query di database personalizzate. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Consente l'avvio del processo di configurazione dell'origine dati [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) per ulteriori operazioni con essa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| table_name | string | Nome della tabella del database da cui verranno estratti i dati |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Configurazione dell'origine dati per query di database personalizzate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| query | string | Stringa di query. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


