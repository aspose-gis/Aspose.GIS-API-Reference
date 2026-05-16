---
title: "楕円体クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | 新しい楕円体を作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | エアリー楕円体。 |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980 楕円体。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| inverse_flattening | double | r | 楕円体の逆平坦率。球体の場合は 0。 |
| is_sphere | bool | r | この楕円体が球体かどうかを検出します。 |
| is_valid | bool | r | 楕円体が有効かどうかを検出します：長半径が 0 より大きく、逆平坦率が正または 0 であること。 |
| 名前 | string | r | このオブジェクトの名前。 |
| semi_major_axis | double | r | 楕円体の長半径。 |
| semi_minor_axis | double | r | 楕円体の短半径。球体の場合は長半径と等しくなります。 |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72 楕円体。 |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84 楕円体。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | 2つの楕円体が等価かどうかを判断します。<br/>            楕円体 A が楕円体 B と等価である場合、長半径と逆平坦率が同じです。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 2つの楕円体が等価かどうかを判断します。<br/>            楕円体 A が楕円体 B と等価である場合、長半径と逆平坦率が同じです。 |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

新しい楕円体を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 楕円体の名前。 |
| semi_major_axis | double | 楕円体の長半径。 |
| inverse_flattening | double | 楕円体の逆平坦率。楕円体を作成するには 0 にする必要があります。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 楕円体の識別子。 |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

2つの楕円体が等価かどうかを判断します。<br/>            楕円体 A が楕円体 B と等価である場合、長半径と逆平坦率が同じです。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 最初の楕円体。 |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 第二の楕円体。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | bool 値で、2つの楕円体が等価かどうかを示します。 |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

2つの楕円体が等価かどうかを判断します。<br/>            楕円体 A が楕円体 B と等価である場合、長半径と逆平坦率が同じです。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | その他の楕円体。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | bool 値で、2つの楕円体が等価かどうかを示します。 |


