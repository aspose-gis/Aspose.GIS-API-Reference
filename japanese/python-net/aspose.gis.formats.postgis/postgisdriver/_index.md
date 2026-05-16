---
title: "PostGisDriver クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | データソース [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) の構成プロセスの開始を許可し、以降の作業に使用できるようにします。 |
| [from_query(query)](#from_query_query_2) | カスタムデータベースクエリ用にデータソースを構成します。 |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

データソース [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) の構成プロセスの開始を許可し、以降の作業に使用できるようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| table_name | string | データが抽出されるデータベーステーブルの名前 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

カスタムデータベースクエリ用にデータソースを構成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| query | string | クエリ文字列です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


