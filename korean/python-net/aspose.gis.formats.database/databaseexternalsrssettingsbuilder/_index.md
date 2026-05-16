---
title: "DatabaseExternalSrsSettingsBuilder 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | 외부 srs 구성을 완료하고 상위 컨텍스트를 반환합니다. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | 추가로 요청된 공간 기준 시스템에 대한 정보를 읽어올 특수 필드 이름을 지정합니다. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

외부 srs 구성을 완료하고 상위 컨텍스트를 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

추가로 요청된 공간 기준 시스템에 대한 정보를 읽어올 특수 필드 이름을 지정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| auth_srid_field | string | 공간 기준 ID를 읽기 위한 필드이며, 기본값은 auth_srid입니다. |
| sr_text_field | string | WKT로 표현된 공간 좌표 시스템을 읽기 위한 필드이며, 기본값은 srtext입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


