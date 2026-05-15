---
title: "PostGisDriver Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Επιτρέπει την έναρξη της διαδικασίας ρύθμισης της πηγής δεδομένων [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) για περαιτέρω εργασία με αυτήν. |
| [from_query(query)](#from_query_query_2) | Ρύθμιση της πηγής δεδομένων για προσαρμοσμένα ερωτήματα βάσης δεδομένων. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Επιτρέπει την έναρξη της διαδικασίας ρύθμισης της πηγής δεδομένων [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) για περαιτέρω εργασία με αυτήν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| table_name | string | Όνομα του πίνακα βάσης δεδομένων από τον οποίο θα εξαχθούν τα δεδομένα |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Ρύθμιση της πηγής δεδομένων για προσαρμοσμένα ερωτήματα βάσης δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| query | string | Συμβολοσειρά ερωτήματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


