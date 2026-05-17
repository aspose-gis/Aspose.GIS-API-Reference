---
title: "Класс DatabaseExternalSrsSettingsBuilder"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Завершите настройку внешней srs и верните родительский контекст. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Указывает специальные имена полей, из которых читается информация о дополнительно запрошенных системах пространственных ссылок. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Завершите настройку внешней srs и верните родительский контекст.

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Указывает специальные имена полей, из которых читается информация о дополнительно запрошенных системах пространственных ссылок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| auth_srid_field | string | Поле для чтения идентификатора пространственной ссылки, по умолчанию: auth_srid. |
| sr_text_field | string | Поле для чтения системы координат, представленной в формате WKT, по умолчанию: srtext. |

**Returns**

| Тип | Описание |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


