---
title: "Extent クラス"
type: docs
weight: 820
url: /ja/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Extent()](#Extent__1) | 新しいインスタンスを作成します。 |
| [Extent(srs)](#Extent_srs_2) | 新しいインスタンスを作成します。 |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Extent の中心です。 |
| 高さ | double | r | Extent の高さです。 |
| is_valid | bool | r | この [Extent](/psd/python-net/aspose.gis/extent/) が有効かどうかを判断します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) がこの extent に関連付けられています。<br/>            <see langword="null" /> になる可能性があります、[Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) が不明な場合。<br/>            Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem) を使用して、異なる空間参照系間で extent を変換します。 |
| width | double | r | Extent の幅です。 |
| x_max | double | 読み/書き | X 座標の最大値です。 |
| x_min | double | 読み/書き | X 座標の最小値です。 |
| y_max | double | 読み/書き | Y座標の最大値。 |
| y_min | double | 読み/書き | Y座標の最小値。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |
| [contains(extent)](#contains_extent_2) | この範囲が引数を含むかどうかを判断します。 |
| [contains(geometry)](#contains_geometry_3) | この範囲が引数を含むかどうかを判断します。 |
| [contains(x, y)](#contains_x_y_4) | この範囲が引数で定義された座標を含むかどうかを判断します。 |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | この範囲を含む、指定された[SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)の新しい範囲を返します。 |
| [grow(extent)](#grow_extent_6) | この範囲を拡大して引数を含むようにします。 |
| [grow(x, y)](#grow_x_y_7) | この範囲を拡大して指定された点を含むようにします。 |
| [grow_x(value)](#grow_x_value_8) | X軸に沿ってこの範囲を拡大し、指定された値を含むようにします。 |
| [grow_y(value)](#grow_y_value_9) | Y軸に沿ってこの範囲を拡大し、指定された値を含むようにします。 |
| [intersects(extent)](#intersects_extent_10) | この範囲が引数と交差するかどうかを判断します。 |
| [intersects(geometry)](#intersects_geometry_11) | この範囲が引数と交差するかどうかを判断します。 |
| normalize() | もし [Extent.width](/psd/python-net/aspose.gis/extent/) が負の場合、[Extent.x_min](/psd/python-net/aspose.gis/extent/) と [Extent.x_max](/psd/python-net/aspose.gis/extent/) を入れ替え、<br/>            もし [Extent.height](/psd/python-net/aspose.gis/extent/) が負の場合、[Extent.y_min](/psd/python-net/aspose.gis/extent/) と [Extent.y_max](/psd/python-net/aspose.gis/extent/) を入れ替えます。 |
| [to_polygon()](#to_polygon__12) | この範囲をそれを表す矩形ポリゴンに変換します。 |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

新しいインスタンスを作成します。

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) はこの範囲に関連付けられます。<br/>            不明なSRSを示すために <see langword=\"null\" /> にすることができます。 |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x_min | double | Xの最小値。 |
| y_min | double | Yの最小値。 |
| x_max | double | Xの最大値。 |
| y_max | double | Yの最大値。 |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) はこの範囲に関連付けられます。<br/>            不明なSRSを示すために <see langword=\"null\" /> にすることができます。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このインスタンスのクローン。 |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

この範囲が引数を含むかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 別の範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この範囲が引数を含むかどうかを示す値。 |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

この範囲が引数を含むかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 包含テストを行うジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この範囲が引数を含むかどうかを示す値。 |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

この範囲が引数で定義された座標を含むかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | 座標のX。 |
| y | double | 座標のY。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 座標がバウンディングボックス内にあるかどうかを示す値。 |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

この範囲を含む、指定された[SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)の新しい範囲を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 変換先の[SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | この範囲を指定された SRS に変換した結果です。 |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

この範囲を拡大して引数を含むようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 他の範囲。 |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

この範囲を拡大して指定された点を含むようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | 含める X 座標。 |
| y | double | 含める Y 座標。 |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

X軸に沿ってこの範囲を拡大し、指定された値を含むようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | 含める値。 |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Y軸に沿ってこの範囲を拡大し、指定された値を含むようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | 含める値。 |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

この範囲が引数と交差するかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 別の範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この範囲が引数と交差するかどうかを示す値。 |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

この範囲が引数と交差するかどうかを判断します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 交差をテストするジオメトリ |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この範囲が引数と交差するかどうかを示す値。 |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

この範囲をそれを表す矩形ポリゴンに変換します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | この範囲を表す矩形の[Polygon](/psd/python-net/aspose.gis.geometries/polygon/)。無効な範囲の場合<br/>空のポリゴンが返されます。 |


