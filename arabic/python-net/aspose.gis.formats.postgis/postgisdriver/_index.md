---
title: "فئة PostGisDriver"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | يسمح ببدء عملية تكوين مصدر البيانات [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) للعمل معه لاحقًا. |
| [from_query(query)](#from_query_query_2) | تكوين مصدر البيانات لاستعلامات قاعدة بيانات مخصصة. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

يسمح ببدء عملية تكوين مصدر البيانات [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) للعمل معه لاحقًا.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| table_name | string | اسم جدول قاعدة البيانات الذي سيتم استخراج البيانات منه |

**Returns**

| نوع | وصف |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

تكوين مصدر البيانات لاستعلامات قاعدة بيانات مخصصة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| query | string | سلسلة الاستعلام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


