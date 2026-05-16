---
title: "DynamicFeature クラス"
type: docs
weight: 650
url: /ja/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | フィーチャのジオメトリを取得または設定します。<br/>            <see langword=\"null\" /> にすることはできません。欠損ジオメトリを示すには [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) を使用してください。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | 別のフィーチャから属性値をコピーします。 |
| [get_as_node()](#get_as_node__2) | 機能をノードとして取得します。カスタムデータに役立ちます。 |
| [get_value(attribute_name)](#get_value_attribute_name_3) | 属性の値を取得します。 |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | 属性の値を取得します。値が設定されていないか <c>null</c> の場合は、[FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) を返します。 |
| [get_values(values, default_value)](#get_values_values_default_value_5) | すべての属性の値を配列で返します。 |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | すべての属性の値を配列で返します。 |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | すべての属性の値を配列で返します。<br/>            追加のメモリ割り当てを回避するために、Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) メソッドの使用を検討してください。 |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | 属性シーケンスの値をリストとして取得します。 |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | 指定された属性が明示的に <c>null</c> 値に設定されているかどうかを判断します。 |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | この機能で属性値が設定されているかどうかをチェックします。 |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | 属性の新しい値を設定します。 |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | 属性の値を <c>null</c> に設定します。 |
| [set_values(values)](#set_values_values_13) | すべての属性に新しい値を設定します。<br/>            また、1 回の呼び出しで値設定を簡素化するために、[DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) メソッドの使用も検討してください。 |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | この機能から属性値を削除します。 |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

別のフィーチャから属性値をコピーします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | 値をコピーする元の機能です。 |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

機能をノードとして取得します。カスタムデータに役立ちます。

**Returns**

| 型 | 説明 |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | 機能への NodeLink |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

属性の値を取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| object | 属性の値。 |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

属性の値を取得します。値が設定されていないか <c>null</c> の場合は、[FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |
| default_value | object | 属性値が存在しない場合に返す値です。デフォルト値は <see langword=\"null\" /> です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| object | 属性の値。 |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

すべての属性の値を配列で返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| values | object | 属性値をコピーする配列 |
| default_value | object | 属性値が存在しない（未設定）場合に返す値です。デフォルト値は <see langword=\"null\" /> です。<br/>            '.Value' を使用して「未設定」と '<see langword=\"null\" />' の値を区別することを検討してください。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| int | コピーされた属性の数です。 |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

すべての属性の値を配列で返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| values_count | int | 値の数です。 |
| default_value | object | 属性値が存在しない（未設定）場合に返す値です。デフォルト値は <see langword=\"null\" /> です。<br/>            '.Value' を使用して「未設定」と '<see langword=\"null\" />' の値を区別することを検討してください。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| object | コピーされた属性の数です。 |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

すべての属性の値を配列で返します。<br/>            追加のメモリ割り当てを回避するために、Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) メソッドの使用を検討してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| default_value | object | 属性値が存在しない（未設定）場合に返す値です。デフォルト値は <see langword=\"null\" /> です。<br/>            '.Value' を使用して「未設定」と '<see langword=\"null\" />' の値を区別することを検討してください。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| object | 属性値をコピーするための新しい配列です。 |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

属性シーケンスの値をリストとして取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |
| separator | string | シーケンスの属性名とインデックス値を区切るために使用される文字列です。 |
| カウント | int | 返す値の数（欠損値は null で埋められます） |

**Returns**

| 型 | 説明 |
| :- | :- |
| object | シーケンスインデックス値で名前が異なる属性の値のリストです。 |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

指定された属性が明示的に <c>null</c> 値に設定されているかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> 属性値が <c>null</c> の場合; それ以外の場合は <see langword=\"false\" />。 |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

この機能で属性値が設定されているかどうかをチェックします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> 指定された属性の値が設定されている場合; それ以外の場合は <see langword=\"false\" />。 |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

属性の新しい値を設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前です。 |
| 値 | object | 属性の値です。 |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

属性の値を <c>null</c> に設定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前です。 |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

すべての属性に新しい値を設定します。<br/>            また、1 回の呼び出しで値設定を簡素化するために、[DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) メソッドの使用も検討してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| values | object | 新しい値の配列です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| int | 設定された属性値の数です。 |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

この機能から属性値を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| attribute_name | string | 属性の名前。 |

