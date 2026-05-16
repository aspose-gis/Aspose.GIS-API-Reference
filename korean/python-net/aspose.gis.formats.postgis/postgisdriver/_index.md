---
title: "PostGisDriver 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | 데이터 소스 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)를 구성하는 프로세스를 시작하도록 허용합니다. |
| [from_query(query)](#from_query_query_2) | 맞춤형 데이터베이스 쿼리를 위한 데이터 소스 구성. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

데이터 소스 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)를 구성하는 프로세스를 시작하도록 허용합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| table_name | string | 데이터가 추출될 데이터베이스 테이블의 이름 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

맞춤형 데이터베이스 쿼리를 위한 데이터 소스 구성.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| query | string | 쿼리 문자열. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


