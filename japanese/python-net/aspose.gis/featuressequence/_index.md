---
title: "FeaturesSequence クラス"
type: docs
weight: 870
url: /ja/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | この[VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)のフィーチャのカスタム属性コレクションを取得します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | このフィーチャーシーケンスの空間参照系を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_extent()](#get_extent__1) | このレイヤーの空間範囲を取得します。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | フィーチャーシーケンスをレイヤーに保存します。 |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | フィーチャーシーケンスをレイヤーに保存します。 |
| [split_to()](#split_to__6) | ジオメトリタイプでフィーチャーを分割します。 |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | 属性値が指定された値と等しいフィーチャーを選択します。 |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | 属性値が指定された値より大きいフィーチャーを選択します。 |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | 属性値が指定された値以上のフィーチャーを選択します。 |
| [where_intersects(extent)](#where_intersects_extent_10) | 範囲に基づいてフィーチャをフィルタリングします。 |
| [where_intersects(geometry)](#where_intersects_geometry_11) | 提供されたジオメトリに基づいてフィーチャをフィルタリングします。 |
| [where_intersects(sequence)](#where_intersects_sequence_12) | 他のフィーチャシーケンス内のすべてのジオメトリの合成に基づいてフィーチャをフィルタリングします。 |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | 属性値が提供された値と等しくないフィーチャを選択します。 |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | 属性が null と等しくないフィーチャを選択します。 |
| [where_null(attribute_name)](#where_null_attribute_name_15) | 属性が null と等しいフィーチャを選択します。 |
| [where_set(attribute_name)](#where_set_attribute_name_16) | 属性が設定されているフィーチャを選択します。 |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | 属性値が提供された値より小さいフィーチャを選択します。 |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | 属性値が提供された値以下のフィーチャを選択します。 |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | 指定された属性が設定されていないフィーチャを選択します。 |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

このレイヤーの空間範囲を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このレイヤーの空間範囲。 |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | string | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | string | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存手順のオプション。 |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

フィーチャーシーケンスをレイヤーに保存します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力レイヤーへのパス。 |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 出力レイヤー用のフォーマットドライバー。 |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 保存手順のオプション。 |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

ジオメトリタイプでフィーチャーを分割します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 同じジオメトリタイプを持つレイヤー。 |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

属性値が指定された値と等しいフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値と等しいフィーチャ。 |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

属性値が指定された値より大きいフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値より大きいフィーチャ。 |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

属性値が指定された値以上のフィーチャーを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値以上のフィーチャ。 |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

範囲に基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | フィルター範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 提供されたジオメトリと交差するフィーチャ。 |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

提供されたジオメトリに基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | ジオメトリをフィルタリング。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 提供されたジオメトリと交差するフィーチャ。 |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

他のフィーチャシーケンス内のすべてのジオメトリの合成に基づいてフィーチャをフィルタリングします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 他のフィーチャのシーケンス。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 他のフィーチャシーケンス内のすべてのジオメトリのユニオンと交差するフィーチャ。 |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

属性値が提供された値と等しくないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値と等しくないフィーチャ。 |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

属性が null と等しくないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が null と等しくないフィーチャ。 |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

属性が null と等しいフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が null と等しいフィーチャ。 |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

属性が設定されているフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が設定されているフィーチャ。 |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

属性値が提供された値より小さいフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値より小さいフィーチャ。 |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

属性値が提供された値以下のフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |
| 値 | object | 比較対象の値。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が提供された値以下のフィーチャ。 |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

指定された属性が設定されていないフィーチャを選択します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | フィルタリングに使用する属性。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 属性値が未設定のフィーチャ。 |


