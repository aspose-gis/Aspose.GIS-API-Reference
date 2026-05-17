---
title: "Класс FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Настраивает имя поля, которое будет содержать информацию для атрибута объекта. |
| [build()](#build__2) | Метод получает реализацию [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Настраивает имя поля, из которого будет извлекаться геометрия. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Обязательная настройка, позволяющая отслеживать изменения. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Настраивает имя поля, которое будет содержать информацию для атрибута объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя поля базы данных для атрибута. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Тип данных, в который должны быть преобразованы данные из базы данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Метод получает реализацию [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Тип | Описание |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Реализация [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Обязательная настройка, позволяющая отслеживать изменения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Атрибут объекта, который будет рассматриваться как уникально идентифицирующий объект. |
| overwrite_same_key | bool | Если этот флаг установлен в true, то вновь добавленные объекты с уникальным идентификатором, совпадающим с уже существующим в слое, <br/>            текущий будет перезаписан, и данные будут считаться обновлёнными, если найдены различия.<br/>            В противном случае будет выброшено исключение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


