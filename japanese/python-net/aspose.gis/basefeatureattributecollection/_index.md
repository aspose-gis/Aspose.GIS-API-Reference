---
title: "BaseFeatureAttributeCollection クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| count | int | r | [Feature](/psd/python-net/aspose.gis/feature/) の属性数を取得します。 |
| is_locked | bool | r | この属性コレクションがロックされているかどうかを示す値を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | コレクションに属性を追加します。 |
| [contains(name)](#contains_name_2) | 属性コレクションが指定された名前の属性を含んでいるかどうかを判定します。 |
| [index_of(name)](#index_of_name_3) | 属性を検索し、そのゼロベースインデックスを返します。 |
| lock() | この属性コレクションをロックし、以降の変更を防止します。 |
| [remove(index)](#remove_index_4) | コレクションから属性を削除します。 |
| [remove(name)](#remove_name_5) | コレクションから属性を削除します。 |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

コレクションに属性を追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | 追加する属性。 |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

属性コレクションが指定された名前の属性を含んでいるかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性の名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 属性コレクションが指定された名前の属性を含む場合は <see langword="true" />、それ以外の場合は <see langword="false" />。 |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

属性を検索し、そのゼロベースインデックスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性の名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| int | 属性がコレクション内に見つかった場合のゼロベースインデックス。見つからない場合は –1。 |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

コレクションから属性を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 属性のインデックス。 |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

コレクションから属性を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性の名前。 |

