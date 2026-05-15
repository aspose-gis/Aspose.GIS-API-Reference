---
title: "DatabaseExternalSrsSettingsBuilder 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | 完成外部 SRS 的配置并返回父上下文。 |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | 指定用于读取额外请求的空间参考系统信息的特殊字段名称。 |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

完成外部 SRS 的配置并返回父上下文。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

指定用于读取额外请求的空间参考系统信息的特殊字段名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| auth_srid_field | string | 用于读取空间参考 ID 的字段，默认值：auth_srid。 |
| sr_text_field | string | 用于读取以 WKT 表示的空间坐标系统的字段，默认值：srtext。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


