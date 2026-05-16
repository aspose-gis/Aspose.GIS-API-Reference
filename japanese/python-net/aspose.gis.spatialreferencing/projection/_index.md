---
title: "投影クラス"
type: docs
weight: 170
url: /ja/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 角度パラメータに使用される単位です。 |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 線形パラメータに使用される単位です。 |
| 名前 | string | r | このオブジェクトの名前。 |
| parameters_names | System.Collections.Generic.IList<string> | r | この投影に与えられたパラメータ名の列挙可能なコレクションを取得します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | この投影の指定された名前のパラメータを取得します。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 2 つの投影が等価かどうかを判断します。等価な投影は (longitude, latitude) を (x, y) に同じ方法でマッピングします。<br/>            同様に。 |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | この投影の指定された名前のパラメータを取得します。該当するパラメータがない場合は <see langword="null" /> を返します。 |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

この投影の指定された名前のパラメータを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | パラメーターの名前。 |
