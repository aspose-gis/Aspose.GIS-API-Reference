---
title: "PostGisDriver 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | 允许开始配置数据源 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) 的过程，以便进一步使用它。 |
| [from_query(query)](#from_query_query_2) | 为自定义数据库查询配置数据源。 |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

允许开始配置数据源 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) 的过程，以便进一步使用它。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| table_name | string | 要提取数据的数据库表的名称 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

为自定义数据库查询配置数据源。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| query | string | 查询字符串。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


