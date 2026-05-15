---
title: "Classe PostGisDriver"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Permet de démarrer le processus de configuration de la source de données [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) pour un travail ultérieur avec celle-ci. |
| [from_query(query)](#from_query_query_2) | Configuration de la source de données pour des requêtes de base de données personnalisées. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Permet de démarrer le processus de configuration de la source de données [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) pour un travail ultérieur avec celle-ci.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| table_name | string | Nom de la table de base de données à partir de laquelle les données seront extraites |

**Returns**

| Type | Description |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Configuration de la source de données pour des requêtes de base de données personnalisées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| query | string | Chaîne de requête. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


