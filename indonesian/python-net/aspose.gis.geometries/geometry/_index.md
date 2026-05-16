---
title: "Kelas Geometry"
type: docs
weight: 50
url: /id/python-net/aspose.gis.geometries/geometry/
---

**Summary:** The abstract root class of the geometries hierarchy.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Geometry

**Inheritance:** IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Mendapatkan jumlah dimensi koordinat untuk [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Mendapatkan dimensi topologi dari [Geometry](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Jika dimensi tidak diketahui (misalnya untuk GEOMETRYCOLLECTION kosong) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) dikembalikan. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Mendapatkan tipe geometri. |
| has_curve_geometry | bool | r | Mendapatkan nilai yang menunjukkan apakah geometri ini adalah atau mengandung geometri kurva (bukan linear). |
| has_m | bool | r/w | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki koordinat M. |
| has_z | bool | r/w | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki koordinat Z. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini kosong. |
| is_simple | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini sederhana dari sudut pandang SFA. |
| is_valid | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini valid. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Mendapatkan sebuah instance geometri null. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Mendapatkan SpatialReferenceSystem dari instance ini.<br/>            Properti ini dapat berupa <see langword="null" />, jika SpatialReferenceSystem tidak diketahui.<br/>            Menetapkan SpatialReferenceSystem baru tidak akan melakukan transformasi koordinat, hanya referensi yang akan berubah. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [as_binary()](#as_binary__1) | Menerjemahkan geometri ini ke representasi Well-Known Binary-nya. |
| [as_binary(variant)](#as_binary_variant_2) | Menerjemahkan geometri ini ke representasi Well-Known Binary-nya. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Ekspor geometri ini ke representasi gambar. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Ekspor geometri ini ke representasi gambar. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Ekspor geometri ini ke representasi gambar. |
| [as_text()](#as_text__6) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [as_text(variant)](#as_text_variant_7) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [as_text(variant, format)](#as_text_variant_format_8) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [clone()](#clone__9) | Menggandakan instance ini. |
| [covered_by(other)](#covered_by_other_10) | Menentukan apakah geometri ini ditutupi oleh geometri yang ditentukan. |
| [covers(other)](#covers_other_11) | Menentukan apakah geometri ini menutupi geometri yang ditentukan. |
| [crosses(other)](#crosses_other_12) | Menentukan apakah geometri ini dan geometri yang ditentukan saling memotong. |
| [difference(other)](#difference_other_13) | Mengurangi geometri yang ditentukan dari geometri ini. |
| [disjoint(other)](#disjoint_other_14) | Menentukan apakah geometri ini terpisah dari geometri yang ditentukan. |
| [from_binary(wkb)](#from_binary_wkb_15) | Membuat geometri dari representasi Well-Known Binary-nya. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_16) | Membuat geometri dari representasi Well-Known Binary-nya. |
| [from_text(wkt)](#from_text_wkt_17) | Membuat geometri dari representasi Well-Known Text-nya. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_18) | Membuat geometri dari representasi Well-Known Text-nya. |
| [get_area()](#get_area__19) | Menghitung area geometri ini. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_20) | Menghitung wilayah buffer di sekitar geometri ini. |
| [get_centroid()](#get_centroid__21) | Menghitung centroid geometri ini. |
| [get_convex_hull()](#get_convex_hull__22) | Menghitung convex hull geometri ini. |
| [get_distance_to(other)](#get_distance_to_other_23) | Menghitung jarak minimum antara geometri ini dan geometri yang ditentukan. |
| [get_extent()](#get_extent__24) | Menghitung dan mengembalikan batas wilayah geometri ini. |
| [get_length()](#get_length__25) | Menghitung panjang geometri ini. |
| [intersection(other)](#intersection_other_26) | Membangun irisan antara geometri ini dan geometri yang ditentukan. |
| [intersects(extent)](#intersects_extent_27) | Menentukan apakah geometri ini beririsan dengan batas yang ditentukan. |
| [intersects(other)](#intersects_other_28) | Menentukan apakah geometri ini dan geometri yang ditentukan beririsan. |
| [overlaps(other)](#overlaps_other_29) | Menentukan apakah geometri ini tumpang tindih dengan geometri yang ditentukan. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_30) | Menentukan apakah matriks irisan DE-9IM dari geometri ini dan geometri yang ditentukan cocok dengan pola yang diberikan. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__31) | Mendapatkan poligon yang direpresentasikan sebagai garis dari geometri ini. |
| [round_m(digits)](#round_m_digits_32) | Membulatkan koordinat M ke sejumlah digit desimal yang ditentukan. |
| [round_xy(digits)](#round_xy_digits_33) | Membulatkan koordinat X dan Y ke sejumlah digit desimal yang ditentukan. |
| [round_z(digits)](#round_z_digits_34) | Membulatkan koordinat Z ke sejumlah digit desimal yang ditentukan. |
| set_empty() | Membuat [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) ini kosong. |
| [spatially_contains(other)](#spatially_contains_other_35) | Menentukan apakah geometri ini secara spasial mengandung geometri yang ditentukan. |
| [spatially_equals(other)](#spatially_equals_other_36) | Menentukan apakah geometri ini secara spasial sama dengan geometri yang ditentukan. |
| [sym_difference(other)](#sym_difference_other_37) | Membangun selisih simetris antara geometri ini dan geometri yang ditentukan. |
| [to_editable()](#to_editable__38) | Mendapatkan salinan yang dapat diedit dari geometri ini. |
| [to_linear_geometry()](#to_linear_geometry__39) | Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> default. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_40) | Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> yang ditentukan. |
| [to_svg(extent)](#to_svg_extent_41) | Menerjemahkan geometri ini ke representasi Svg. |
| [touches(other)](#touches_other_42) | Menentukan apakah geometri ini dan geometri yang ditentukan bersentuhan. |
| [union(other)](#union_other_43) | Menggabungkan geometri ini dengan geometri yang ditentukan. |
| [union(other)](#union_other_44) | Menggabungkan geometri ini dengan geometri yang ditentukan. |
| [within(extent)](#within_extent_45) | Menentukan apakah geometri ini berada dalam batas yang ditentukan. |
| [within(other)](#within_other_46) | Menentukan apakah geometri ini berada dalam geometri yang ditentukan. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Menerjemahkan geometri ini ke representasi Well-Known Binary-nya.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Representasi Well-Known Binary dari geometri ini. |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

Menerjemahkan geometri ini ke representasi Well-Known Binary-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Varian Well-Known Binary yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Representasi Well-Known Binary dari geometri ini. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Ekspor geometri ini ke representasi gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke gambar output. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Lebar peta. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Tinggi peta. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer yang akan digunakan. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Ekspor geometri ini ke representasi gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_path | string | Jalur ke gambar output. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Lebar peta. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Tinggi peta. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer yang akan digunakan. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

Ekspor geometri ini ke representasi gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Lebar peta. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Tinggi peta. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer yang akan digunakan. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Symbolizer yang akan digunakan untuk rendering. Jika <see langword=\"null\" />, symbolizer default akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| _io.BufferedRandom | Gambar sebagai aliran |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Menerjemahkan geometri ini ke representasi Well-Known Text-nya.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi Well-Known Text dari geometri ini. |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

Menerjemahkan geometri ini ke representasi Well-Known Text-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Varian Well-Known Text yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi Well-Known Text dari geometri ini. |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

Menerjemahkan geometri ini ke representasi Well-Known Text-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Varian Well-Known Text yang akan digunakan. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Format koordinat untuk konversi ke string. Lihat [NumericFormat](/psd/python-net/aspose.gis/numericformat/) untuk mendapatkannya. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi Well-Known Text dari geometri ini. |


### Method: clone() {#clone__9}


```
 clone() 
```

Menggandakan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Klon dari instance ini |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

Menentukan apakah geometri ini ditutupi oleh geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini \"spatially covered by\" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

Menentukan apakah geometri ini menutupi geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini \"spatially covers\" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

Menentukan apakah geometri ini dan geometri yang ditentukan saling memotong.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini \"spatially crosses\" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

Mengurangi geometri yang ditentukan dari geometri ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri untuk dikurangkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili selisih antara geometri ini dan sebuah argumen. Geometri hasil berisi<br/>            himpunan titik yang ada di geometri ini tetapi tidak ada di argumen. |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

Menentukan apakah geometri ini terpisah dari geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword="true" /> jika geometri ini "spatially disjoint" dari geometri lain. <see langword="false" /> sebaliknya. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_15}


```
 from_binary(wkb) 
```

Membuat geometri dari representasi Well-Known Binary-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkb | byte | Representasi Well-Known Binary dari sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang direpresentasikan oleh argumen. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_16}


```
 from_binary(wkb, spatial_reference_system) 
```

Membuat geometri dari representasi Well-Known Binary-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkb | byte | Representasi Well-Known Binary dari sebuah geometri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem Referensi Spasial yang akan diberikan ke geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang direpresentasikan oleh argumen. |


### Method: from_text(wkt)  [static] {#from_text_wkt_17}


```
 from_text(wkt) 
```

Membuat geometri dari representasi Well-Known Text-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkt | string | Representasi Well-Known Text dari sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang direpresentasikan oleh argumen. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_18}


```
 from_text(wkt, spatial_reference_system) 
```

Membuat geometri dari representasi Well-Known Text-nya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| wkt | string | Representasi Well-Known Text dari sebuah geometri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem Referensi Spasial yang akan diberikan ke geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang direpresentasikan oleh argumen. |


### Method: get_area() {#get_area__19}


```
 get_area() 
```

Menghitung area geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Luas geometri ini.<br/>            Jumlah luas elemen-elemen geometri ini jika geometri ini adalah [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_20}


```
 get_buffer(distance, quadrant_segments) 
```

Menghitung wilayah buffer di sekitar geometri ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jarak | double | Lebar wilayah buffer. |
| quadrant_segments | int | Jumlah segmen yang digunakan untuk mendekati kelengkungan 90 derajat.<br/>            Semakin besar angka ini, semakin baik pendekatan kurva yang dihasilkan.<br/>            Default adalah 30. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili semua titik yang berada dalam jarak tertentu dari<br/>            geometri ini.<br/>            Tipe hasilnya adalah salah satu dari [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) atau [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__21}


```
 get_centroid() 
```

Menghitung centroid geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Centroid dari geometri ini. Jika geometri ini kosong, sebuah titik kosong dikembalikan.<br/>            Centroid sama dengan centroid geometri dengan dimensi tertinggi dalam geometri ini<br/>            (misalnya jika baik titik maupun garis terdapat dalam geometri, hanya garis yang berkontribusi pada centroid). |


### Method: get_convex_hull() {#get_convex_hull__22}


```
 get_convex_hull() 
```

Menghitung convex hull geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili convex hull dari geometri ini.<br/>            Jika geometri ini tidak memiliki titik maka hasilnya adalah [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Jika geometri ini hanya memiliki satu titik maka hasilnya adalah titik tersebut.<br/>            Jika geometri ini hanya memiliki dua titik maka hasilnya adalah [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) dengan titik-titik tersebut.<br/>            Jika geometri ini memiliki tiga atau lebih titik maka hasilnya adalah [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) yang mewakili convex<br/>            hull di sekitar semua titik geometri. |


### Method: get_distance_to(other) {#get_distance_to_other_23}


```
 get_distance_to(other) 
```

Menghitung jarak minimum antara geometri ini dan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri untuk menemukan jarak ke. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Jika kedua geometri tidak [Geometry.is_empty](/psd/python-net/aspose.gis.geometries/geometry/), maka jarak antara titik terdekat dari geometri-geometri tersebut.<br/>            Jika setidaknya satu geometri kosong, -1 dikembalikan. |


### Method: get_extent() {#get_extent__24}


```
 get_extent() 
```

Menghitung dan mengembalikan batas wilayah geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Rentang batas dari geometri ini. |


### Method: get_length() {#get_length__25}


```
 get_length() 
```

Menghitung panjang geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Panjang geometri ini.<br/>            Keliling jika ini adalah [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Jumlah panjang elemen-elemen geometri ini jika geometri ini adalah [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_26}


```
 intersection(other) 
```

Membangun irisan antara geometri ini dan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri untuk menghitung irisan dengan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili irisan antara geometri ini dan sebuah argumen. Geometri hasil berisi<br/>            himpunan titik yang ada di kedua geometri ini dan argumen. |


### Method: intersects(extent) {#intersects_extent_27}


```
 intersects(extent) 
```

Menentukan apakah geometri ini beririsan dengan batas yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Rentang. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini memotong batas; <see langword=\"false\" /> sebaliknya. |


### Method: intersects(other) {#intersects_other_28}


```
 intersects(other) 
```

Menentukan apakah geometri ini dan geometri yang ditentukan beririsan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially intersects" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: overlaps(other) {#overlaps_other_29}


```
 overlaps(other) 
```

Menentukan apakah geometri ini tumpang tindih dengan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially overlaps" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_30}


```
 relate(other, intersection_pattern_matrix) 
```

Menentukan apakah matriks irisan DE-9IM dari geometri ini dan geometri yang ditentukan cocok dengan pola yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |
| intersection_pattern_matrix | string | Pola untuk dicocokkan.<br/>            Ini harus berupa string dengan panjang 9.<br/>            Setiap karakter dalam string mewakili dimensi yang diharapkan dari sebuah perpotongan:<br/>            <ul><br/>            <li>karakter 0 - antara interior geometri.</li><br/>            <li>karakter 1 - antara interior geometri ini dan batas geometri lain.</li><br/>            <li>karakter 2 - antara interior geometri ini dan eksterior geometri lain.</li><br/>            <li>karakter 3 - antara batas geometri ini dan interior geometri lain.</li><br/>            <li>karakter 4 - antara batas-batas geometri.</li><br/>            <li>karakter 5 - antara batas geometri ini dan eksterior geometri lain.</li><br/>            <li>karakter 6 - antara eksterior geometri ini dan interior geometri lain.</li><br/>            <li>karakter 7 - antara eksterior geometri ini dan batas geometri lain.</li><br/>            <li>karakter 8 - antara eksterior geometri.</li><br/>            </ul><br/>            Nilai yang mungkin untuk setiap karakter adalah:<br/>            <ul><br/>            <li>* - nilai apa saja;</li><br/>            <li>F - tidak ada perpotongan;</li><br/>            <li>T - ada perpotongan;</li><br/>            <li>0 - perpotongan titik (mis. titik bersama);</li><br/>            <li>1 - perpotongan garis (mis. segmen garis bersama);</li><br/>            <li>2 - perpotongan area (mis. bagian poligon bersama);</li><br/>            </ul><br/>            Sebagai contoh, pola perpotongan "F0*******" berarti tidak boleh ada perpotongan antara interior geometri dan perpotongan antara batas geometri harus berupa titik.<br/>            Lihat OpenGIS Simple Features Specification untuk detail lebih lanjut tentang pola matriks perpotongan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika matriks perpotongan ini cocok dengan pola; <see langword=\"false\" /> sebaliknya. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__31}


```
 replace_polygons_by_lines() 
```

Mendapatkan poligon yang direpresentasikan sebagai garis dari geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang tidak memiliki geometri poligon. Transformasi berikut diterapkan:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) di‑linear-kan<br/>            (diubah menjadi [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) digabungkan menjadi [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_32}


```
 round_m(digits) 
```

Membulatkan koordinat M ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: round_xy(digits) {#round_xy_digits_33}


```
 round_xy(digits) 
```

Membulatkan koordinat X dan Y ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: round_z(digits) {#round_z_digits_34}


```
 round_z(digits) 
```

Membulatkan koordinat Z ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: spatially_contains(other) {#spatially_contains_other_35}


```
 spatially_contains(other) 
```

Menentukan apakah geometri ini secara spasial mengandung geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially contains" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: spatially_equals(other) {#spatially_equals_other_36}


```
 spatially_equals(other) 
```

Menentukan apakah geometri ini secara spasial sama dengan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially equals" geometri yang ditentukan. <see langword=\"false\" /> sebaliknya. |


### Method: sym_difference(other) {#sym_difference_other_37}


```
 sym_difference(other) 
```

Membangun selisih simetris antara geometri ini dan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri untuk menghitung selisih simetris dengan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang mewakili selisih simetris antara geometri ini dan argumen. Geometri hasil berisi<br/>            himpunan titik yang ada pada salah satu geometri tetapi tidak ada pada keduanya. |


### Method: to_editable() {#to_editable__38}


```
 to_editable() 
```

Mendapatkan salinan yang dapat diedit dari geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Salinan yang dapat diedit dari geometri ini. |


### Method: to_linear_geometry() {#to_linear_geometry__39}


```
 to_linear_geometry() 
```

Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> default.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang tidak memiliki geometri kurva. Ini setara dengan <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) dengan<br/>            toleransi default <c>tolerance</c>. Toleransi default <c>tolerance</c> ditentukan oleh [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            dari geometri ini:<br/>            <ul><br/>            <li> Untuk SRS terproyeksi, Toleransi adalah 0.001 meter (dalam satuan SRS) </li><br/>            <li> Untuk SRS geografis, Toleransi adalah <c>1e-5</c> derajat (dalam satuan SRS) </li><br/>            <li> Untuk SRS tidak diketahui, Toleransi adalah <c>1e-5</c> </li><br/>            </ul><br/>            Untuk detail lebih lanjut tentang transformasi yang diterapkan, lihat spesifikasi <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_40}


```
 to_linear_geometry(tolerance) 
```

Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tolerance | double | <c>tolerance</c> yang akan digunakan. Hasil dijamin kurang dari <c>tolerance</c> dari geometri melengkung,<br/>            kecuali jumlah titik yang diperlukan untuk melineariskan geometri melebihi maksimum per-kuadran<br/>            yang saat ini sama dengan 10000 titik. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang tidak memiliki geometri kurva. Transformasi berikut diterapkan:<br/>            <ul><br/>            <li> [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) di-linear-kan<br/>            (diubah menjadi [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) dengan <paramref name="tolerance" /> yang ditentukan) </li><br/>            <li> [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) digabung menjadi <c>LineString</c> </li><br/>            <li> [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) diubah menjadi [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            <li> [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) diubah menjadi [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            <li> [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/) diubah menjadi [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            </ul><br/>            Sebagai hasilnya, [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) dari geometri output adalah <see langword="false" />. |


### Method: to_svg(extent) {#to_svg_extent_41}


```
 to_svg(extent) 
```

Menerjemahkan geometri ini ke representasi Svg.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Batas untuk mentranslasi geometri ini ke Svg |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi Svg. |


### Method: touches(other) {#touches_other_42}


```
 touches(other) 
```

Menentukan apakah geometri ini dan geometri yang ditentukan bersentuhan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially touches" geometri lain. <see langword=\"false\" /> sebaliknya. |


### Method: union(other) {#union_other_43}


```
 union(other) 
```

Menggabungkan geometri ini dengan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri untuk digabungkan dengan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang mewakili gabungan antara geometri ini dan argumen. Geometri hasil berisi<br/>            himpunan titik yang ada di geometri ini atau di argumen. |


### Method: union(other) {#union_other_44}


```
 union(other) 
```

Menggabungkan geometri ini dengan geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri untuk digabungkan dengan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang mewakili gabungan antara geometri ini dan argumen. Geometri hasil berisi<br/>            himpunan titik yang ada di geometri ini atau di argumen. |


### Method: within(extent) {#within_extent_45}


```
 within(extent) 
```

Menentukan apakah geometri ini berada dalam batas yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Rentang. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini berada dalam batas; <see langword=\"false\" /> sebaliknya. |


### Method: within(other) {#within_other_46}


```
 within(other) 
```

Menentukan apakah geometri ini berada dalam geometri yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika geometri ini "spatially within" geometri lain. <see langword=\"false\" /> sebaliknya. |


