---
title: "FromDefinitionDataSourceBuilder 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | 配置将包含要素属性信息的字段名称。 |
| [build()](#build__2) | 该方法检索 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) 的实现。 |
| [geometry_field(name)](#geometry_field_name_3) | 配置提取几何信息的字段名称。 |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | 允许跟踪更改的必需设置。 |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

配置将包含要素属性信息的字段名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的数据库字段名称。 |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 数据库数据应转换成的目标数据类型。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

该方法检索 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) 的实现。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | 实现 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


```
 geometry_field(name) 
```

配置提取几何信息的字段名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 几何字段的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

允许跟踪更改的必需设置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 特征的属性，将被视为唯一标识该特征。 |
| overwrite_same_key | bool | 如果此标志设置为 true，则新添加的具有与层中已存在的唯一标识符相同的特征，<br/>            当前特征将被覆盖，如果发现差异，数据将被视为已更新。<br/>            否则，将抛出异常。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


