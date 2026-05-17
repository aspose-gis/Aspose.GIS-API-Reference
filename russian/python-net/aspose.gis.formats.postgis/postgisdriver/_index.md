---
title: "Класс PostGisDriver"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Позволяет начать процесс настройки источника данных [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) для дальнейшей работы с ним. |
| [from_query(query)](#from_query_query_2) | Настройка источника данных для пользовательских запросов к базе данных. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Позволяет начать процесс настройки источника данных [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) для дальнейшей работы с ним.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| table_name | string | Имя таблицы базы данных, из которой будут извлекаться данные |

**Returns**

| Тип | Описание |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Настройка источника данных для пользовательских запросов к базе данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| query | string | Строка запроса. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


