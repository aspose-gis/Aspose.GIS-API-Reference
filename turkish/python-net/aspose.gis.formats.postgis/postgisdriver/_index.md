---
title: "PostGisDriver Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Veri kaynağını [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) yapılandırma sürecinin başlatılmasına izin verir, böylece onunla daha ileri çalışmalar yapılabilir. |
| [from_query(query)](#from_query_query_2) | Özel veritabanı sorguları için veri kaynağını yapılandırma. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Veri kaynağını [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) yapılandırma sürecinin başlatılmasına izin verir, böylece onunla daha ileri çalışmalar yapılabilir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| table_name | string | Verinin çıkarılacağı veritabanı tablosunun adı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Özel veritabanı sorguları için veri kaynağını yapılandırma.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| query | string | Sorgu dizesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


