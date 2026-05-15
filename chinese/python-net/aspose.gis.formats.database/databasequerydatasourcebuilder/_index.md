---
title: "DatabaseQueryDataSourceBuilder 类"
type: docs
weight: 40
url: /zh/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | 配置将包含要素属性信息的字段名称。 |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | 配置生成的图层以跟踪更改，并创建数据源来同步所做的更改。 |
| [build()](#build__3) | 该方法检索 [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 的实现。 |
| [geometry_field(name)](#geometry_field_name_4) | 配置提取几何信息的字段名称。 |
| [srid_field(name)](#srid_field_name_5) | 配置将包含空间参考系统标识符 (srid) 的查询字段名称。 |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | 允许您配置数据源使用第三方空间参考系统数据，绕过 Aspose.GIS 库中预装的数据。 |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

配置将包含要素属性信息的字段名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的查询字段名称。 |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 数据库数据应转换成的目标数据类型。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

配置生成的图层以跟踪更改，并创建数据源来同步所做的更改。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| table_name | string | 进行更改的表的名称。 |
| identity_attribute | string | 特征的属性，将被视为唯一标识该特征。 |
| overwrite_same_key | bool | 如果此标志设置为 true，则新添加的具有与图层中已存在的唯一标识符相同的要素将覆盖当前要素，并且如果发现差异，数据将被读取为已更新。 |
| db_func | string | 将在 SQL 查询中提供的函数，用于将二进制数据转换为当前数据库的地理数据表示。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

该方法检索 [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 的实现。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) 的实现 |


### Method: geometry_field(name) {#geometry_field_name_4}


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
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

配置将包含空间参考系统标识符 (srid) 的查询字段名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 包含空间参考系统标识符的查询字段名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

允许您配置数据源使用第三方空间参考系统数据，绕过 Aspose.GIS 库中预装的数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| srs_query | string | 查询以检索关于主查询中用于检索要素的附加空间坐标系的信息。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


