---
title: "Point クラス"
type: docs
weight: 300
url: /ja/python-net/aspose.gis.geometries/point/
---

**Summary:** A [Point](/psd/python-net/aspose.gis.geometries/point/) represents a single location in coordinate space.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Point

**Inheritance:** IGeometry, IPoint, Geometry

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Point()](#Point__1) | 新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。 |
| [Point(other)](#Point_other_2) | 新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。 |
| [Point(x, y)](#Point_x_y_3) | 新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。 |
| [Point(x, y, z)](#Point_x_y_z_4) | 新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。 |
| [Point(x, y, z, m)](#Point_x_y_z_m_5) | 新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) の座標次元数を取得します。 |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) の位相次元を取得します。 |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | ジオメトリのタイプを取得します。 |
| has_curve_geometry | bool | r | このジオメトリが曲線（線形ではない）ジオメトリであるか、含んでいるかを示す値を取得します。 |
| has_m | bool | 読み/書き | このインスタンスが M 座標を持つかどうかを示す値を取得します。 |
| has_z | bool | 読み/書き | このインスタンスが Z 座標を持つかどうかを示す値を取得します。 |
| is_empty | bool | r | このインスタンスが空であるかどうかを示す値を取得します。 |
| is_simple | bool | r | このインスタンスが SFA の観点から単純であるかどうかを示す値を取得します。 |
| is_valid | bool | r | このインスタンスが有効かどうかを示す値を取得します。 |
| m | double | 読み/書き | m 座標の値を取得または設定します。 |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | null ジオメトリのインスタンスを取得します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | このインスタンスの SpatialReferenceSystem を取得します。<br/>            このプロパティは <see langword=\"null\" /> に設定可能で、SpatialReferenceSystem が不明な場合です。<br/>            新しい SpatialReferenceSystem を割り当てても座標変換は行われず、参照のみが変更されます。 |
| x | double | 読み/書き | x 座標の値を取得または設定します。 |
| y | double | 読み/書き | y 座標の値を取得または設定します。 |
| z | double | 読み/書き | z 座標の値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [as_binary()](#as_binary__1) | このジオメトリを Well-Known Binary 表現に変換します。 |
| [as_binary(variant)](#as_binary_variant_2) | このジオメトリを Well-Known Binary 表現に変換します。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | このジオメトリを画像表現にエクスポートします。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | このジオメトリを画像表現にエクスポートします。 |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | このジオメトリを画像表現にエクスポートします。 |
| [as_text()](#as_text__6) | このジオメトリを Well-Known Text 表現に変換します。 |
| [as_text(variant)](#as_text_variant_7) | このジオメトリを Well-Known Text 表現に変換します。 |
| [as_text(variant, format)](#as_text_variant_format_8) | このジオメトリを Well-Known Text 表現に変換します。 |
| [clone()](#clone__9) | このインスタンスをクローンします。 |
| [covered_by(other)](#covered_by_other_10) | このジオメトリが指定されたジオメトリに覆われているかどうかを判定します。 |
| [covers(other)](#covers_other_11) | このジオメトリが指定されたジオメトリを覆うかどうかを判定します。 |
| [crosses(other)](#crosses_other_12) | このジオメトリと指定されたジオメトリが交差するかどうかを判定します。 |
| [difference(other)](#difference_other_13) | このジオメトリから指定されたジオメトリを減算します。 |
| [disjoint(other)](#disjoint_other_14) | このジオメトリが指定されたジオメトリと離散であるかどうかを判定します。 |
| [from_binary(wkb)](#from_binary_wkb_15) | Well-Known Binary 表現からジオメトリを作成します。 |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_16) | Well-Known Binary 表現からジオメトリを作成します。 |
| [from_text(wkt)](#from_text_wkt_17) | Well-Known Text 表現からジオメトリを作成します。 |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_18) | Well-Known Text 表現からジオメトリを作成します。 |
| [get_area()](#get_area__19) | このジオメトリの面積を計算します。 |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_20) | このジオメトリの周囲にバッファ領域を計算します。 |
| [get_centroid()](#get_centroid__21) | このジオメトリの重心を計算します。 |
| [get_convex_hull()](#get_convex_hull__22) | このジオメトリの凸包を計算します。 |
| [get_distance_to(other)](#get_distance_to_other_23) | このジオメトリと指定されたジオメトリ間の最小距離を計算します。 |
| [get_extent()](#get_extent__24) | このジオメトリの境界範囲を計算し、返します。 |
| [get_length()](#get_length__25) | このジオメトリの長さを計算します。 |
| [intersection(other)](#intersection_other_26) | このジオメトリと指定されたジオメトリの交差を構築します。 |
| [intersects(extent)](#intersects_extent_27) | このジオメトリが指定された範囲と交差するかどうかを判定します。 |
| [intersects(other)](#intersects_other_28) | このジオメトリと指定されたジオメトリが交差するかどうかを判定します。 |
| [overlaps(other)](#overlaps_other_29) | このジオメトリが指定されたジオメトリと重なるかどうかを判定します。 |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_30) | このジオメトリと指定されたジオメトリの DE-9IM 交差行列が提供されたパターンと一致するかどうかを判定します。 |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__31) | このジオメトリのラインとして表現されたポリゴンを取得します。 |
| [round_m(digits)](#round_m_digits_32) | M 座標を指定された小数桁数に丸めます。 |
| [round_xy(digits)](#round_xy_digits_33) | X および Y 座標を指定された小数桁数に丸めます。 |
| [round_z(digits)](#round_z_digits_34) | Z 座標を指定された小数桁数に丸めます。 |
| set_empty() | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) を空にします。 |
| [spatially_contains(other)](#spatially_contains_other_35) | このジオメトリが空間的に指定されたジオメトリを含むかどうかを判定します。 |
| [spatially_equals(other)](#spatially_equals_other_36) | このジオメトリが空間的に指定されたジオメトリと等しいかどうかを判定します。 |
| [sym_difference(other)](#sym_difference_other_37) | このジオメトリと指定されたジオメトリの対称差を構築します。 |
| [to_editable()](#to_editable__38) | このジオメトリの編集可能なコピーを取得します。 |
| [to_linear_geometry()](#to_linear_geometry__39) | デフォルトの<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。 |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_40) | 指定された<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。 |
| [to_svg(extent)](#to_svg_extent_41) | このジオメトリをSvg表現に変換します。 |
| [touches(other)](#touches_other_42) | このジオメトリと指定されたジオメトリが接触しているかどうかを判定します。 |
| [union(other)](#union_other_43) | このジオメトリと指定されたジオメトリを結合します。 |
| [union(other)](#union_other_44) | このジオメトリと指定されたジオメトリを結合します。 |
| [within(extent)](#within_extent_45) | このジオメトリが指定された範囲内にあるかどうかを判定します。 |
| [within(other)](#within_other_46) | このジオメトリが指定されたジオメトリ内にあるかどうかを判定します。 |


### Constructor: Point() {#Point__1}


```
 Point() 
```

新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。

### Constructor: Point(other) {#Point_other_2}


```
 Point(other) 
```

新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | データをコピーする対象となる別の [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/)。 |

### Constructor: Point(x, y) {#Point_x_y_3}


```
 Point(x, y) 
```

新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | X 座標の値です。 |
| y | double | Y 座標の値です。 |

### Constructor: Point(x, y, z) {#Point_x_y_z_4}


```
 Point(x, y, z) 
```

新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | X 座標の値です。 |
| y | double | Y 座標の値です。 |
| z | double | Z 座標の値です。 |

### Constructor: Point(x, y, z, m) {#Point_x_y_z_m_5}


```
 Point(x, y, z, m) 
```

新しい [Point](/psd/python-net/aspose.gis.geometries/point/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double | X 座標の値です。 |
| y | double | Y 座標の値です。 |
| z | double | Z 座標の値です。 |
| m | double | M 座標の値です。 |

### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

このジオメトリを Well-Known Binary 表現に変換します。

**Returns**

| 型 | 説明 |
| :- | :- |
| byte | このジオメトリのWell-Known Binary表現。 |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

このジオメトリを Well-Known Binary 表現に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | 使用するWell-Known Binaryのバリアント。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| byte | このジオメトリのWell-Known Binary表現。 |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

このジオメトリを画像表現にエクスポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 出力画像へのパス。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの幅。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの高さ。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 使用するレンダラー。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

このジオメトリを画像表現にエクスポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| output_path | string | 出力画像へのパス。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの幅。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの高さ。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 使用するレンダラー。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

このジオメトリを画像表現にエクスポートします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの幅。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | マップの高さ。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 使用するレンダラー。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | レンダリングに使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのシンボライザーが使用されます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| _io.BufferedRandom | ストリームとしての画像 |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

このジオメトリを Well-Known Text 表現に変換します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | このジオメトリのWell-Known Text表現。 |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

このジオメトリを Well-Known Text 表現に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 使用するWell-Known Textのバリアント。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | このジオメトリのWell-Known Text表現。 |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

このジオメトリを Well-Known Text 表現に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 使用するWell-Known Textのバリアント。 |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 文字列への変換用座標フォーマットです。取得するには[NumericFormat](/psd/python-net/aspose.gis/numericformat/)をご覧ください。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | このジオメトリのWell-Known Text表現。 |


### Method: clone() {#clone__9}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | このインスタンスのクローン |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

このジオメトリが指定されたジオメトリに覆われているかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword="true" /> このジオメトリが別のジオメトリに空間的に覆われている場合。<see langword="false" /> それ以外の場合。 |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

このジオメトリが指定されたジオメトリを覆うかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword="true" /> このジオメトリが別のジオメトリを空間的にカバーしている場合。<see langword="false" /> それ以外の場合。 |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

このジオメトリと指定されたジオメトリが交差するかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword="true" /> このジオメトリが別のジオメトリと空間的に交差している場合。<see langword="false" /> それ以外の場合。 |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

このジオメトリから指定されたジオメトリを減算します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 減算するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリと引数との差分を表すジオメトリ。結果のジオメトリは<br/>            このジオメトリに存在し、引数には存在しない点集合を含みます。 |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

このジオメトリが指定されたジオメトリと離散であるかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが別のジオメトリと「空間的に非交差」場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_15}


```
 from_binary(wkb) 
```

Well-Known Binary 表現からジオメトリを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkb | byte | ジオメトリの Well-Known Binary 表現。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 引数で表現されたジオメトリ。 |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_16}


```
 from_binary(wkb, spatial_reference_system) 
```

Well-Known Binary 表現からジオメトリを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkb | byte | ジオメトリの Well-Known Binary 表現。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | ジオメトリに割り当てられる空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 引数で表現されたジオメトリ。 |


### Method: from_text(wkt)  [static] {#from_text_wkt_17}


```
 from_text(wkt) 
```

Well-Known Text 表現からジオメトリを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkt | string | ジオメトリの Well-Known Text 表現。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 引数で表現されたジオメトリ。 |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_18}


```
 from_text(wkt, spatial_reference_system) 
```

Well-Known Text 表現からジオメトリを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkt | string | ジオメトリの Well-Known Text 表現。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | ジオメトリに割り当てられる空間参照系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 引数で表現されたジオメトリ。 |


### Method: get_area() {#get_area__19}


```
 get_area() 
```

このジオメトリの面積を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| double | このジオメトリの面積。<br/>            このジオメトリが [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) の場合、要素の面積の合計。 |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_20}


```
 get_buffer(distance, quadrant_segments) 
```

このジオメトリの周囲にバッファ領域を計算します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 距離 | double | バッファ領域の幅。 |
| quadrant_segments | int | 曲率 90 度を近似するために使用されるセグメント数。<br/>            この数が大きいほど曲線の近似が精度良くなります。<br/>            デフォルトは 30。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリから指定された距離以内にあるすべての点を表すジオメトリ。<br/>            結果の型は [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)、[IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) または [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) のいずれかです。 |


### Method: get_centroid() {#get_centroid__21}


```
 get_centroid() 
```

このジオメトリの重心を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | このジオメトリの重心。ジオメトリが空の場合は空の点が返されます。<br/>            重心はこのジオメトリ内の最高次元ジオメトリの重心に等しいです<br/>            （例：ポイントとラインの両方がジオメトリに含まれる場合、ラインのみが重心に寄与します）。 |


### Method: get_convex_hull() {#get_convex_hull__22}


```
 get_convex_hull() 
```

このジオメトリの凸包を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリの凸包を表すジオメトリ。<br/>            このジオメトリにポイントがない場合、結果は [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) です。<br/>            このジオメトリにポイントが1つだけある場合、結果はそのポイントです。<br/>            このジオメトリにポイントが2つだけある場合、結果はポイントを持つ [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) です。<br/>            このジオメトリに3つ以上のポイントがある場合、結果はすべてのジオメトリポイントを囲む凸状の [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) です。 |


### Method: get_distance_to(other) {#get_distance_to_other_23}


```
 get_distance_to(other) 
```

このジオメトリと指定されたジオメトリ間の最小距離を計算します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 距離を測定するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| double | 両方のジオメトリが [Geometry.is_empty](/psd/python-net/aspose.gis.geometries/geometry/) でない場合、ジオメトリ間の最も近い点間の距離を返します。<br/>            少なくとも一方のジオメトリが空の場合は -1 が返されます。 |


### Method: get_extent() {#get_extent__24}


```
 get_extent() 
```

このジオメトリの境界範囲を計算し、返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このジオメトリの境界範囲。 |


### Method: get_length() {#get_length__25}


```
 get_length() 
```

このジオメトリの長さを計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| double | このジオメトリの長さ。<br/>            これが [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) の場合は周囲長です。<br/>            これが [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) の場合、要素の長さの合計です。 |


### Method: intersection(other) {#intersection_other_26}


```
 intersection(other) 
```

このジオメトリと指定されたジオメトリの交差を構築します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 交差を計算するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリと引数の交差を表すジオメトリ。結果のジオメトリは<br/>            このジオメトリと引数の両方に存在する点集合を含みます。 |


### Method: intersects(extent) {#intersects_extent_27}


```
 intersects(extent) 
```

このジオメトリが指定された範囲と交差するかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが範囲と交差する場合; <see langword=\"false\" /> それ以外の場合。 |


### Method: intersects(other) {#intersects_other_28}


```
 intersects(other) 
```

このジオメトリと指定されたジオメトリが交差するかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが他のジオメトリと「空間的に交差」する場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: overlaps(other) {#overlaps_other_29}


```
 overlaps(other) 
```

このジオメトリが指定されたジオメトリと重なるかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが他のジオメトリと「空間的に重なり合う」場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_30}


```
 relate(other, intersection_pattern_matrix) 
```

このジオメトリと指定されたジオメトリの DE-9IM 交差行列が提供されたパターンと一致するかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |
| intersection_pattern_matrix | string | 一致させるパターンです。<br/>            長さが9の文字列である必要があります。<br/>            文字列の各文字は交差の期待される次元を表します:<br/>            <ul><br/>            <li>文字0 - ジオメトリの内部同士の間。</li><br/>            <li>文字1 - このジオメトリの内部と他のジオメトリの境界の間。</li><br/>            <li>文字2 - このジオメトリの内部と他のジオメトリの外部の間。</li><br/>            <li>文字3 - このジオメトリの境界と他のジオメトリの内部の間。</li><br/>            <li>文字4 - ジオメトリの境界同士の間。</li><br/>            <li>文字5 - このジオメトリの境界と他のジオメトリの外部の間。</li><br/>            <li>文字6 - このジオメトリの外部と他のジオメトリの内部の間。</li><br/>            <li>文字7 - このジオメトリの外部と他のジオメトリの境界の間。</li><br/>            <li>文字8 - ジオメトリの外部同士の間。</li><br/>            </ul><br/>            各文字の可能な値は次のとおりです:<br/>            <ul><br/>            <li>* - 任意の値；</li><br/>            <li>F - 交差なし；</li><br/>            <li>T - 任意の交差；</li><br/>            <li>0 - 点の交差（例: 共有点）；</li><br/>            <li>1 - 線の交差（例: 共有線分）；</li><br/>            <li>2 - 面の交差（例: 共有ポリゴン部分）；</li><br/>            </ul><br/>            例えば、交差パターン "F0*******" は、ジオメトリの内部間に交差がなく、境界間の交差は点であることを意味します。<br/>            詳細は OpenGIS Simple Features Specification を参照してください。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> この交差マトリックスがパターンと一致する場合; <see langword=\"false\" /> それ以外の場合。 |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__31}


```
 replace_polygons_by_lines() 
```

このジオメトリのラインとして表現されたポリゴンを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ポリゴンジオメトリを持たないジオメトリです。以下の変換が適用されます:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) は線形化され<br/> ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) は [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に結合されます</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_32}


```
 round_m(digits) 
```

M 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: round_xy(digits) {#round_xy_digits_33}


```
 round_xy(digits) 
```

X および Y 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: round_z(digits) {#round_z_digits_34}


```
 round_z(digits) 
```

Z 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: spatially_contains(other) {#spatially_contains_other_35}


```
 spatially_contains(other) 
```

このジオメトリが空間的に指定されたジオメトリを含むかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが他のジオメトリを「空間的に含む」場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: spatially_equals(other) {#spatially_equals_other_36}


```
 spatially_equals(other) 
```

このジオメトリが空間的に指定されたジオメトリと等しいかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが指定されたジオメトリと「空間的に等しい」場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: sym_difference(other) {#sym_difference_other_37}


```
 sym_difference(other) 
```

このジオメトリと指定されたジオメトリの対称差を構築します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 対称差を計算するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリと引数との対称差を表すジオメトリです。結果のジオメトリは<br/>            いずれか一方のジオメトリに存在し、両方には存在しない点集合を含みます。 |


### Method: to_editable() {#to_editable__38}


```
 to_editable() 
```

このジオメトリの編集可能なコピーを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.gis.geometries/point) | このジオメトリの編集可能なコピー。 |


### Method: to_linear_geometry() {#to_linear_geometry__39}


```
 to_linear_geometry() 
```

デフォルトの<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 曲線ジオメトリを持たないジオメトリです。これは <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) を、デフォルトの <c>tolerance</c> で呼び出したものと同等です。デフォルトの <c>tolerance</c> はこのジオメトリの [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/) によって定義されます。<br/>            <ul><br/>            <li> 投影座標系 (SRS) の場合、許容誤差は 0.001 メートル (SRS の単位) です </li><br/>            <li> 地理座標系 (SRS) の場合、許容誤差は <c>1e-5</c> 度 (SRS の単位) です </li><br/>            <li> 不明な SRS の場合、許容誤差は <c>1e-5</c> です </li><br/>            </ul><br/>            適用される変換の詳細については、<DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) の仕様を参照してください。 |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_40}


```
 to_linear_geometry(tolerance) 
```

指定された<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 許容誤差 | double | 使用する <c>tolerance</c>。結果は <c>tolerance</c> 未満の誤差で曲線ジオメトリから離れることが保証されていますが、ジオメトリを直線化するために必要な点数がクアドラントごとの最大数<br/>            （現在は 10000 点）を超える場合は除きます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 曲線ジオメトリを持たないジオメトリです。以下の変換が適用されます：<br/>            <ul><br/>            <li> [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) は線形化され、指定された <paramref name=\"tolerance\" /> を使用した [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます </li><br/>            <li> [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) は <c>LineString</c> に結合されます </li><br/>            <li> [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) は [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます </li><br/>            <li> [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) は [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます </li><br/>            <li> [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/) は [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます </li><br/>            </ul><br/>            その結果、出力ジオメトリの [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) は <see langword=\"false\" /> になります。 |


### Method: to_svg(extent) {#to_svg_extent_41}


```
 to_svg(extent) 
```

このジオメトリをSvg表現に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | このジオメトリを SVG に変換するための範囲 |

**Returns**

| 型 | 説明 |
| :- | :- |
| string | SVG 表現です。 |


### Method: touches(other) {#touches_other_42}


```
 touches(other) 
```

このジオメトリと指定されたジオメトリが接触しているかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが他のジオメトリに「空間的に接触」する場合。 <see langword=\"false\" /> それ以外の場合。 |


### Method: union(other) {#union_other_43}


```
 union(other) 
```

このジオメトリと指定されたジオメトリを結合します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 結合するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリと引数の合成を表すジオメトリです。結果のジオメトリは<br/>            このジオメトリまたは引数のいずれかに存在する点集合を含みます。 |


### Method: union(other) {#union_other_44}


```
 union(other) 
```

このジオメトリと指定されたジオメトリを結合します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | 結合するジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリと引数の合成を表すジオメトリです。結果のジオメトリは<br/>            このジオメトリまたは引数のいずれかに存在する点集合を含みます。 |


### Method: within(extent) {#within_extent_45}


```
 within(extent) 
```

このジオメトリが指定された範囲内にあるかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 範囲。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが範囲内にある場合; <see langword=\"false\" /> それ以外の場合。 |


### Method: within(other) {#within_other_46}


```
 within(other) 
```

このジオメトリが指定されたジオメトリ内にあるかどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | <see langword=\"true\" /> このジオメトリが他のジオメトリの「空間的に内部」にある場合。 <see langword=\"false\" /> それ以外の場合。 |


