---
title: "Класс DatabaseQueryDataSourceBuilder"
type: docs
weight: 40
url: /ru/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Настраивает имя поля, которое будет содержать информацию для атрибута объекта. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Настройте полученный слой для отслеживания изменений и создайте источник данных для синхронизации внесённых изменений. |
| [build()](#build__3) | Метод получает реализацию [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Настраивает имя поля, из которого будет извлекаться геометрия. |
| [srid_field(name)](#srid_field_name_5) | Настройка имени поля запроса, которое будет содержать идентификатор системы пространственной ссылки (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Позволяет настроить источник данных для использования сторонних данных системы пространственных ссылок, обходя предустановленные данные в библиотеке Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Настраивает имя поля, которое будет содержать информацию для атрибута объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя поля запроса для атрибута. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Тип данных, в который должны быть преобразованы данные из базы данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Настройте полученный слой для отслеживания изменений и создайте источник данных для синхронизации внесённых изменений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| table_name | string | Имя таблицы, в которой будут внесены изменения. |
| identity_attribute | string | Атрибут объекта, который будет рассматриваться как уникально идентифицирующий объект. |
| overwrite_same_key | bool | Если этот флаг установлен в true, то вновь добавленные объекты с уникальным идентификатором, совпадающим с уже существующим в слое, будут перезаписаны, и данные будут считаться обновлёнными, если обнаружены различия. |
| db_func | string | Функция, которая будет использована в SQL‑запросе для преобразования бинарных данных в географическое представление текущей базы данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Метод получает реализацию [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Тип | Описание |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Реализация [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Настраивает имя поля, из которого будет извлекаться геометрия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя поля геометрии. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Настройка имени поля запроса, которое будет содержать идентификатор системы пространственной ссылки (srid).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя поля запроса, содержащего идентификатор системы пространственной ссылки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Позволяет настроить источник данных для использования сторонних данных системы пространственных ссылок, обходя предустановленные данные в библиотеке Aspose.GIS.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| srs_query | string | Запрос для получения информации о дополнительных системах пространственных координат, используемых в основном запросе для получения объектов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


