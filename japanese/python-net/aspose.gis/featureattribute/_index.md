---
title: "FeatureAttribute クラス"
type: docs
weight: 840
url: /ja/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | 新しい [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) クラスのインスタンスを初期化します。 |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | 新しい [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| can_be_null | bool | 読み/書き | このインスタンスが null になる可能性があるかどうかを示す値を取得します。 |
| can_be_unset | bool | 読み/書き | この属性の値を省略できるかどうかを示す値を取得または設定します。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | 属性のデータ型を取得します。 |
| default_value | object | 読み/書き | 欠損データを示す属性の値を取得または設定します。 |
| has_custom_default_value | bool | r | この属性の事前定義されたデフォルト値がカスタム値で上書きされたかどうかを示す値を取得します。 |
| is_locked | bool | r | この属性がロックされているかどうかを示す値を取得します。 |
| 名前 | string | 読み/書き | 属性の名前を取得します。 |
| precision | Nullable<int> | 読み/書き | 保存する小数点以下の最大桁数を取得または設定します。 |
| type_name | string | 読み/書き | 属性の型名です。 |
| width | Nullable<int> | 読み/書き | 属性の文字表現で許容される最大幅を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| lock() | この属性をロックします。 |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

新しい [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性の名前です。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 属性のデータ型です。 |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

新しい [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 属性の名前です。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 属性のデータ型です。 |
| can_be_null | bool | <see langword="true" /> このインスタンスが null になる可能性がある場合; それ以外の場合は <see langword="false" />。 |

