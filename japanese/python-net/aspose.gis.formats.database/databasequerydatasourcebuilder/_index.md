---
title: "DatabaseQueryDataSourceBuilder クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | フィーチャ属性情報を格納するフィールドの名前を設定します。 |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | 結果として得られるレイヤーを変更の追跡に設定し、行われた変更を同期するデータソースを作成します。 |
| [build()](#build__3) | このメソッドは [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) の実装を取得します。 |
| [geometry_field(name)](#geometry_field_name_4) | ジオメトリが抽出されるフィールドの名前を設定します。 |
| [srid_field(name)](#srid_field_name_5) | 空間参照系識別子 (srid) を含むクエリフィールドの名前を設定します。 |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Aspose.GIS ライブラリに事前インストールされているデータをバイパスし、サードパーティの空間参照系データを使用するようデータソースを構成できます。 |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

フィーチャ属性情報を格納するフィールドの名前を設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性用クエリフィールドの名前。 |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | データベースからのデータを変換すべきデータ型。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

結果として得られるレイヤーを変更の追跡に設定し、行われた変更を同期するデータソースを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| table_name | string | 変更が行われるテーブルの名前。 |
| identity_attribute | string | フィーチャを一意に識別する属性として扱われる属性。 |
| overwrite_same_key | bool | このフラグが true に設定されている場合、レイヤーに既に存在するユニーク識別子と同じ識別子を持つ新しく追加されたフィーチャは現在のものが上書きされ、差異が見つかった場合はデータが更新されたものとして読み取られます。 |
| db_func | string | 現在のデータベースの地理データ表現にバイナリデータを変換するために SQL クエリで提供される関数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

このメソッドは [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) の実装を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) の実装 |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

ジオメトリが抽出されるフィールドの名前を設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | gemetry フィールドの名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

空間参照系識別子 (srid) を含むクエリフィールドの名前を設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 空間参照系識別子を含むクエリフィールドの名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Aspose.GIS ライブラリに事前インストールされているデータをバイパスし、サードパーティの空間参照系データを使用するようデータソースを構成できます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| srs_query | string | メインクエリで機能を取得するために使用される追加の空間座標系に関する情報を取得するクエリです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


