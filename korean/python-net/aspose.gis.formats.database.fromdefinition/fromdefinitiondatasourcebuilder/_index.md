---
title: "FromDefinitionDataSourceBuilder 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | 특성 속성 정보를 포함할 필드의 이름을 구성합니다. |
| [build()](#build__2) | 이 메서드는 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)의 구현을 검색합니다. |
| [geometry_field(name)](#geometry_field_name_3) | 지오메트리를 추출할 필드의 이름을 구성합니다. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | 변경 사항을 추적할 수 있는 필수 설정입니다. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

특성 속성 정보를 포함할 필드의 이름을 구성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성을 위한 데이터베이스 필드 이름. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 데이터베이스의 데이터를 변환해야 하는 데이터 유형. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

이 메서드는 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)의 구현을 검색합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | 다음의 구현 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

변경 사항을 추적할 수 있는 필수 설정입니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 피처를 고유하게 식별하는 것으로 간주되는 피처의 속성. |
| overwrite_same_key | bool | 이 플래그가 true로 설정되면, 레이어에 이미 존재하는 고유 식별자와 동일한 새로 추가된 피처가 있을 경우, 현재 피처가 덮어쓰여지고 차이가 발견되면 데이터가 업데이트된 것으로 읽힙니다.<br/>            그렇지 않으면 예외가 발생합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


