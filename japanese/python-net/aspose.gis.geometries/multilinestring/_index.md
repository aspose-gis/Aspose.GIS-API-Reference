---
title: "MultiLineString クラス"
type: docs
weight: 260
url: /ja/python-net/aspose.gis.geometries/multilinestring/
---

**Summary:** A [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) is a one-dimensional [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) <br/>            whose elements are [LineString](/psd/python-net/aspose.gis.geometries/linestring/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.MultiLineString

**Inheritance:** IGeometry, IGeometryCollection, IMultiCurve, IMultiLineString, MultiCurve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MultiLineString()](#MultiLineString__1) | 新しい [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) の座標次元数を取得します。 |
| カウント | int | r | このコレクション内のジオメトリの数を取得します。 |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) の位相次元を取得します。 |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | ジオメトリのタイプを取得します。 |
| has_curve_geometry | bool | r | このジオメトリが曲線（線形ではない）ジオメトリであるか、含んでいるかを示す値を取得します。 |
| has_m | bool | 読み/書き | このインスタンスが M 座標を持つかどうかを示す値を取得します。 |
| has_z | bool | 読み/書き | このインスタンスが Z 座標を持つかどうかを示す値を取得します。 |
| is_closed | bool | r | この曲線が閉じているかどうかを判断します。 |
| is_empty | bool | r | このインスタンスが空であるか（空の点集合を表すか）を示す値を取得します。 |
| is_simple | bool | r | このインスタンスが SFA の観点から単純であるかどうかを示す値を取得します。 |
| is_valid | bool | r | このインスタンスが有効かどうかを示す値を取得します。 |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | null ジオメトリのインスタンスを取得します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | このインスタンスの SpatialReferenceSystem を取得します。<br/>            SpatialReferenceSystem が不明な場合、このプロパティは <see langword=\"null\" /> になる可能性があります。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(geometry)](#add_geometry_1) | 指定されたジオメトリをコレクションに追加します。 |
| [add_range(geometries)](#add_range_geometries_2) | 指定されたジオメトリ群をコレクションに追加します。 |
| [as_binary()](#as_binary__3) | このジオメトリを Well-Known Binary 表現に変換します。 |
| [as_binary(variant)](#as_binary_variant_4) | このジオメトリを Well-Known Binary 表現に変換します。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | このジオメトリを画像表現にエクスポートします。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_6) | このジオメトリを画像表現にエクスポートします。 |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_7) | このジオメトリを画像表現にエクスポートします。 |
| [as_text()](#as_text__8) | このジオメトリを Well-Known Text 表現に変換します。 |
| [as_text(variant)](#as_text_variant_9) | このジオメトリを Well-Known Text 表現に変換します。 |
| [as_text(variant, format)](#as_text_variant_format_10) | このジオメトリを Well-Known Text 表現に変換します。 |
| [clone()](#clone__11) | このインスタンスをクローンします。 |
| [covered_by(other)](#covered_by_other_12) | このジオメトリが指定されたジオメトリに覆われているかどうかを判定します。 |
| [covers(other)](#covers_other_13) | このジオメトリが指定されたジオメトリを覆うかどうかを判定します。 |
| [crosses(other)](#crosses_other_14) | このジオメトリと指定されたジオメトリが交差するかどうかを判定します。 |
| [difference(other)](#difference_other_15) | このジオメトリから指定されたジオメトリを減算します。 |
| [disjoint(other)](#disjoint_other_16) | このジオメトリが指定されたジオメトリと離散であるかどうかを判定します。 |
| [from_binary(wkb)](#from_binary_wkb_17) | Well-Known Binary 表現からジオメトリを作成します。 |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_18) | Well-Known Binary 表現からジオメトリを作成します。 |
| [from_text(wkt)](#from_text_wkt_19) | Well-Known Text 表現からジオメトリを作成します。 |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_20) | Well-Known Text 表現からジオメトリを作成します。 |
| [get_area()](#get_area__21) | このジオメトリの面積を計算します。 |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_22) | このジオメトリの周囲にバッファ領域を計算します。 |
| [get_centroid()](#get_centroid__23) | このジオメトリの重心を計算します。 |
| [get_convex_hull()](#get_convex_hull__24) | このジオメトリの凸包を計算します。 |
| [get_distance_to(other)](#get_distance_to_other_25) | このジオメトリと指定されたジオメトリ間の最小距離を計算します。 |
| [get_extent()](#get_extent__26) | このジオメトリの境界範囲を計算し、返します。 |
| [get_length()](#get_length__27) | このジオメトリの長さを計算します。 |
| [get_point_on_surface()](#get_point_on_surface__28) | このコレクション内のいずれかのサーフェス上に必ず存在する点を検索します。 |
| [intersection(other)](#intersection_other_29) | このジオメトリと指定されたジオメトリの交差を構築します。 |
| [intersects(extent)](#intersects_extent_30) | このジオメトリが指定された範囲と交差するかどうかを判定します。 |
| [intersects(other)](#intersects_other_31) | このジオメトリと指定されたジオメトリが交差するかどうかを判定します。 |
| [overlaps(other)](#overlaps_other_32) | このジオメトリが指定されたジオメトリと重なるかどうかを判定します。 |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | このジオメトリと指定されたジオメトリの DE-9IM 交差行列が提供されたパターンと一致するかどうかを判定します。 |
| [remove_at(index)](#remove_at_index_34) | 指定されたジオメトリをコレクションから削除します。 |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | このジオメトリのラインとして表現されたポリゴンを取得します。 |
| [round_m(digits)](#round_m_digits_36) | M 座標を指定された小数桁数に丸めます。 |
| [round_xy(digits)](#round_xy_digits_37) | X および Y 座標を指定された小数桁数に丸めます。 |
| [round_z(digits)](#round_z_digits_38) | Z 座標を指定された小数桁数に丸めます。 |
| set_empty() | この [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) を空にします。 |
| [spatially_contains(other)](#spatially_contains_other_39) | このジオメトリが空間的に指定されたジオメトリを含むかどうかを判定します。 |
| [spatially_equals(other)](#spatially_equals_other_40) | このジオメトリが空間的に指定されたジオメトリと等しいかどうかを判定します。 |
| [sym_difference(other)](#sym_difference_other_41) | このジオメトリと指定されたジオメトリの対称差を構築します。 |
| [to_editable()](#to_editable__42) | このジオメトリの編集可能なコピーを取得します。 |
| [to_linear_geometry()](#to_linear_geometry__43) | デフォルトの<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。 |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | 指定された<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。 |
| [to_svg(extent)](#to_svg_extent_45) | このジオメトリをSvg表現に変換します。 |
| [touches(other)](#touches_other_46) | このジオメトリと指定されたジオメトリが接触しているかどうかを判定します。 |
| [union(other)](#union_other_47) | このジオメトリと指定されたジオメトリを結合します。 |
| [union(other)](#union_other_48) | このジオメトリと指定されたジオメトリを結合します。 |
| [within(extent)](#within_extent_49) | このジオメトリが指定された範囲内にあるかどうかを判定します。 |
| [within(other)](#within_other_50) | このジオメトリが指定されたジオメトリ内にあるかどうかを判定します。 |


### Constructor: MultiLineString() {#MultiLineString__1}


```
 MultiLineString() 
```

新しい [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) クラスのインスタンスを初期化します。

### Method: add(geometry) {#add_geometry_1}


```
 add(geometry) 
```

指定されたジオメトリをコレクションに追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 追加するジオメトリ。 |

### Method: add_range(geometries) {#add_range_geometries_2}


```
 add_range(geometries) 
```

指定されたジオメトリ群をコレクションに追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ジオメトリ | System.Collections.Generic.IEnumerable<IGeometry> | 追加するジオメトリ群。 |

### Method: as_binary() {#as_binary__3}


```
 as_binary() 
```

このジオメトリを Well-Known Binary 表現に変換します。

**Returns**

| 型 | 説明 |
| :- | :- |
| byte | このジオメトリのWell-Known Binary表現。 |


### Method: as_binary(variant) {#as_binary_variant_4}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_6}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_7}


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


### Method: as_text() {#as_text__8}


```
 as_text() 
```

このジオメトリを Well-Known Text 表現に変換します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | このジオメトリのWell-Known Text表現。 |


### Method: as_text(variant) {#as_text_variant_9}


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


### Method: as_text(variant, format) {#as_text_variant_format_10}


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


### Method: clone() {#clone__11}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | このインスタンスのクローン |


### Method: covered_by(other) {#covered_by_other_12}


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


### Method: covers(other) {#covers_other_13}


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


### Method: crosses(other) {#crosses_other_14}


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


### Method: difference(other) {#difference_other_15}


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


### Method: disjoint(other) {#disjoint_other_16}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_17}


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


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_18}


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


### Method: from_text(wkt)  [static] {#from_text_wkt_19}


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


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_20}


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


### Method: get_area() {#get_area__21}


```
 get_area() 
```

このジオメトリの面積を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| double | このジオメトリの面積。<br/>            このジオメトリが [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) の場合、要素の面積の合計。 |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_22}


```
 get_buffer(distance, quadrant_segments) 
```

このジオメトリの周囲にバッファ領域を計算します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 距離 | double | バッファ領域の幅（Spatial Reference の単位）。 |
| quadrant_segments | int | 曲率 90 度を近似するために使用されるセグメント数。<br/>            この数が大きいほど曲線の近似が精度良くなります。<br/>            デフォルトは 30。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリから指定された距離以内にあるすべての点を表すジオメトリ。<br/>            結果の型は [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)、[IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) または [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) のいずれかです。 |


### Method: get_centroid() {#get_centroid__23}


```
 get_centroid() 
```

このジオメトリの重心を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | このジオメトリの重心。ジオメトリが空の場合は空の点が返されます。<br/>            重心はこのジオメトリ内の最高次元ジオメトリの重心に等しいです<br/>            （例：ポイントとラインの両方がジオメトリに含まれる場合、ラインのみが重心に寄与します）。 |


### Method: get_convex_hull() {#get_convex_hull__24}


```
 get_convex_hull() 
```

このジオメトリの凸包を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | このジオメトリの凸包を表すジオメトリ。<br/>            このジオメトリにポイントがない場合、結果は [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) です。<br/>            このジオメトリにポイントが1つだけある場合、結果はそのポイントです。<br/>            このジオメトリにポイントが2つだけある場合、結果はポイントを持つ [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) です。<br/>            このジオメトリに3つ以上のポイントがある場合、結果はすべてのジオメトリポイントを囲む凸状の [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) です。 |


### Method: get_distance_to(other) {#get_distance_to_other_25}


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
| double | 両方のジオメトリが [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) でない場合、ジオメトリ間の最も近い点同士の距離が返されます。<br/>            いずれかのジオメトリが空の場合は -1 が返されます。 |


### Method: get_extent() {#get_extent__26}


```
 get_extent() 
```

このジオメトリの境界範囲を計算し、返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このジオメトリの境界範囲。 |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

このジオメトリの長さを計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| double | このジオメトリの長さ。<br/>            これが [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) の場合は周囲長です。<br/>            これが [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) の場合、要素の長さの合計です。 |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

このコレクション内のいずれかのサーフェス上に必ず存在する点を検索します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | サーフェスのいずれか上の点。コレクションにサーフェスが含まれていない、またはすべてのサーフェスが空の場合は空の点が返されます。 |


### Method: intersection(other) {#intersection_other_29}


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


### Method: intersects(extent) {#intersects_extent_30}


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


### Method: intersects(other) {#intersects_other_31}


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


### Method: overlaps(other) {#overlaps_other_32}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


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


### Method: remove_at(index) {#remove_at_index_34}


```
 remove_at(index) 
```

指定されたジオメトリをコレクションから削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | 削除するジオメトリのインデックス。 |

### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

このジオメトリのラインとして表現されたポリゴンを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | ポリゴンジオメトリを持たないジオメトリです。以下の変換が適用されます:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) は線形化され<br/> ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に変換されます)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) は [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) に結合されます</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

M 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

X および Y 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Z 座標を指定された小数桁数に丸めます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 桁数 | int | 小数部の桁数です。 |

### Method: spatially_contains(other) {#spatially_contains_other_39}


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


### Method: spatially_equals(other) {#spatially_equals_other_40}


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


### Method: sym_difference(other) {#sym_difference_other_41}


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


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

このジオメトリの編集可能なコピーを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring) | このジオメトリの編集可能なコピー。 |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

デフォルトの<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | この [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) は、この [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) に近似または同等です。<br/>            これは <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) の同等で、デフォルトの <c>tolerance</c> を使用します。デフォルトの <c>tolerance</c> の値は、[SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) に依存します。<br/>            このジオメトリの:<br/>            <ul><br/>            <li> 投影 SRS の場合、許容誤差は 0.001 メートル（SRS の単位）です </li><br/>            <li> 地理 SRS の場合、許容誤差は <c>1e-5</c> 度（SRS の単位）です </li><br/>            <li> 不明な SRS の場合、許容誤差は <c>1e-5</c> です </li><br/>            </ul><br/>            適用される変換の詳細については、<DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) の仕様を参照してください。 |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

指定された<c>tolerance</c>を使用して、このジオメトリの近似または同等の非曲線バージョンを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 許容誤差 | double | 使用する <c>tolerance</c>。結果は <c>tolerance</c> 未満の誤差で曲線ジオメトリから離れることが保証されますが、<br/>ジオメトリを線形化するために必要な点数が四分割ごとの最大数（現在は 10000 点）を超える場合は除きます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | この [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) は、この [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) に近似または同等です:<br/>             <ul><br/>             このオブジェクトが [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) 自身である場合、結果はこのオブジェクトと同等です<br/>             このオブジェクトが [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) でない場合、すべての曲線が直線化され、新しい <c>IMultiLineString</c> が作成されます<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


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


### Method: touches(other) {#touches_other_46}


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


### Method: union(other) {#union_other_47}


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


### Method: union(other) {#union_other_48}


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


### Method: within(extent) {#within_extent_49}


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


### Method: within(other) {#within_other_50}


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


