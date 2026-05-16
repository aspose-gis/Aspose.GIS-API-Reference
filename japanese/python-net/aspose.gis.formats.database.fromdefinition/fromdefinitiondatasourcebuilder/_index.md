---
title: "FromDefinitionDataSourceBuilder クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | フィーチャ属性情報を格納するフィールドの名前を設定します。 |
| [build()](#build__2) | このメソッドは [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) の実装を取得します。 |
| [geometry_field(name)](#geometry_field_name_3) | ジオメトリが抽出されるフィールドの名前を設定します。 |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | 変更の追跡を可能にする必須設定です。 |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

フィーチャ属性情報を格納するフィールドの名前を設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性用データベースフィールドの名前。 |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | データベースからのデータを変換すべきデータ型。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

このメソッドは [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) の実装を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | 実装 [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

変更の追跡を可能にする必須設定です。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | フィーチャを一意に識別する属性として扱われる属性。 |
| overwrite_same_key | bool | このフラグが true に設定されている場合、レイヤーに既に存在する同じ一意識別子を持つ新しく追加されたフィーチャは、<br/>            現在のフィーチャで上書きされ、差分が見つかった場合はデータが更新されたものとして読み取られます。<br/>            それ以外の場合は例外がスローされます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


