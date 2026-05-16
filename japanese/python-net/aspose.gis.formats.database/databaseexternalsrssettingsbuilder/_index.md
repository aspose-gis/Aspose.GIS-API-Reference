---
title: "DatabaseExternalSrsSettingsBuilder クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | 外部 SRS の構成を完了し、親コンテキストを返します。 |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | 追加で要求された空間参照系に関する情報を読み取るための特別なフィールド名を指定します。 |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

外部 SRS の構成を完了し、親コンテキストを返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

追加で要求された空間参照系に関する情報を読み取るための特別なフィールド名を指定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| auth_srid_field | string | 空間参照 ID を読み取るフィールド、デフォルト: auth_srid。 |
| sr_text_field | string | WKT で表現された空間座標系を読み取るフィールド、デフォルト: srtext。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


