---
title: "DatabaseQueryDataSourceBuilder 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | 특성 속성 정보를 포함할 필드의 이름을 구성합니다. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | 결과 레이어를 구성하여 변경 사항을 추적하고, 수행된 변경을 동기화할 데이터 소스를 생성합니다. |
| [build()](#build__3) | 이 메서드는 [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 구현을 검색합니다. |
| [geometry_field(name)](#geometry_field_name_4) | 지오메트리를 추출할 필드의 이름을 구성합니다. |
| [srid_field(name)](#srid_field_name_5) | 공간 기준 시스템 식별자(srid)를 포함할 쿼리 필드의 이름을 구성합니다. |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Aspose.GIS 라이브러리에 사전 설치된 데이터를 우회하여 서드파티 공간 기준 시스템 데이터를 사용하도록 데이터 소스를 구성할 수 있습니다. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

특성 속성 정보를 포함할 필드의 이름을 구성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성을 위한 쿼리 필드 이름. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 데이터베이스의 데이터를 변환해야 하는 데이터 유형. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

결과 레이어를 구성하여 변경 사항을 추적하고, 수행된 변경을 동기화할 데이터 소스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| table_name | string | 변경이 적용될 테이블의 이름. |
| identity_attribute | string | 피처를 고유하게 식별하는 것으로 간주되는 피처의 속성. |
| overwrite_same_key | bool | 이 플래그가 true로 설정되면, 레이어에 이미 존재하는 고유 식별자와 동일한 식별자를 가진 새로 추가된 피처는 현재 피처가 덮어쓰여지고, 차이가 발견되면 데이터가 업데이트된 것으로 읽어집니다. |
| db_func | string | 현재 데이터베이스의 지리 데이터 표현으로 바이너리 데이터를 변환하기 위해 SQL 쿼리에서 제공될 함수입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

이 메서드는 [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 구현을 검색합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 구현 |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

지오메트리를 추출할 필드의 이름을 구성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 지오메트리 필드의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

공간 기준 시스템 식별자(srid)를 포함할 쿼리 필드의 이름을 구성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 공간 기준 시스템 식별자를 포함하는 쿼리 필드의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Aspose.GIS 라이브러리에 사전 설치된 데이터를 우회하여 서드파티 공간 기준 시스템 데이터를 사용하도록 데이터 소스를 구성할 수 있습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| srs_query | string | 주 쿼리에서 피처를 검색하기 위해 사용되는 추가 공간 좌표 시스템에 대한 정보를 검색하는 쿼리. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


