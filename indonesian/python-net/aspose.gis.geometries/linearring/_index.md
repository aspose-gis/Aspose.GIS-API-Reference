---
title: "Kelas LinearRing"
type: docs
weight: 240
url: /id/python-net/aspose.gis.geometries/linearring/
---

**Summary:** A [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) is a [LineString](/psd/python-net/aspose.gis.geometries/linestring/) that is both closed and simple.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.LinearRing

**Inheritance:** IGeometry, ICurve, ILineString, ILinearRing, LineString

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LinearRing()](#LinearRing__1) | Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
| [LinearRing(collection)](#LinearRing_collection_2) | Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
| [LinearRing(other)](#LinearRing_other_3) | Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Mendapatkan jumlah dimensi koordinat untuk [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Mendapatkan dimensi topologi dari [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            Jika dimensi tidak diketahui (misalnya untuk GEOMETRYCOLLECTION kosong) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) dikembalikan. |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Mengembalikan salinan titik akhir kurva. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Mendapatkan tipe geometri. |
| has_curve_geometry | bool | r | Mendapatkan nilai yang menunjukkan apakah geometri ini adalah atau mengandung geometri kurva (bukan linear). |
| has_m | bool | r/w | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki koordinat M. |
| has_z | bool | r/w | Mendapatkan nilai yang menunjukkan apakah instance ini memiliki koordinat Z. |
| is_closed | bool | r | Mendapatkan nilai yang menunjukkan apakah sebuah kurva tertutup.<br/>            Sebuah kurva tertutup jika titik awalnya sama dengan titik akhirnya. |
| is_empty | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini kosong. |
| is_simple | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini sederhana dari sudut pandang SFA. |
| is_valid | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini valid. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Mendapatkan sebuah instance geometri null. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Mendapatkan SpatialReferenceSystem dari instance ini.<br/>            Properti ini dapat berupa <see langword=\"null\" />, jika SpatialReferenceSystem belum diatur.<br/>            Menetapkan SpatialReferenceSystem baru tidak akan melakukan transformasi koordinat, hanya referensi yang akan berubah. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Mengembalikan salinan titik mulai kurva. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | Menambahkan sebuah titik ke akhir garis. |
| [add_point(x, y)](#add_point_x_y_2) | Menambahkan sebuah titik ke akhir garis. |
| [add_point(x, y, z)](#add_point_x_y_z_3) | Menambahkan sebuah titik ke akhir garis. |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | Menambahkan sebuah titik ke akhir garis. |
| [as_binary()](#as_binary__5) | Menerjemahkan geometri ini ke representasi Well-Known Binary-nya. |
| [as_binary(variant)](#as_binary_variant_6) | Menerjemahkan geometri ini ke representasi Well-Known Binary-nya. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | Ekspor geometri ini ke representasi gambar. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | Ekspor geometri ini ke representasi gambar. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | Ekspor geometri ini ke representasi gambar. |
| [as_text()](#as_text__10) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [as_text(variant)](#as_text_variant_11) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [as_text(variant, format)](#as_text_variant_format_12) | Menerjemahkan geometri ini ke representasi Well-Known Text-nya. |
| [clone()](#clone__13) | Menggandakan instance ini. |
| [covered_by(other)](#covered_by_other_14) | Menentukan apakah geometri ini ditutupi oleh geometri yang ditentukan. |
| [covers(other)](#covers_other_15) | Menentukan apakah geometri ini menutupi geometri yang ditentukan. |
| [crosses(other)](#crosses_other_16) | Menentukan apakah geometri ini dan geometri yang ditentukan saling memotong. |
| [difference(other)](#difference_other_17) | Mengurangi geometri yang ditentukan dari geometri ini. |
| [disjoint(other)](#disjoint_other_18) | Menentukan apakah geometri ini terpisah dari geometri yang ditentukan. |
| [from_binary(wkb)](#from_binary_wkb_19) | Membuat geometri dari representasi Well-Known Binary-nya. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | Membuat geometri dari representasi Well-Known Binary-nya. |
| [from_text(wkt)](#from_text_wkt_21) | Membuat geometri dari representasi Well-Known Text-nya. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | Membuat geometri dari representasi Well-Known Text-nya. |
| [get_area()](#get_area__23) | Menghitung area geometri ini. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | Menghitung wilayah buffer di sekitar geometri ini. |
| [get_centroid()](#get_centroid__25) | Menghitung centroid geometri ini. |
| [get_convex_hull()](#get_convex_hull__26) | Menghitung convex hull geometri ini. |
| [get_distance_to(other)](#get_distance_to_other_27) | Menghitung jarak minimum antara geometri ini dan geometri yang ditentukan. |
| [get_extent()](#get_extent__28) | Menghitung dan mengembalikan batas wilayah geometri ini. |
| [get_length()](#get_length__29) | Menghitung panjang geometri ini. |
| [intersection(other)](#intersection_other_30) | Membangun irisan antara geometri ini dan geometri yang ditentukan. |
| [intersects(extent)](#intersects_extent_31) | Menentukan apakah geometri ini beririsan dengan batas yang ditentukan. |
| [intersects(other)](#intersects_other_32) | Menentukan apakah geometri ini dan geometri yang ditentukan beririsan. |
| [is_clockwise()](#is_clockwise__33) | Menentukan apakah cincin memiliki lilitan searah jarum jam. |
| [overlaps(other)](#overlaps_other_34) | Menentukan apakah geometri ini tumpang tindih dengan geometri yang ditentukan. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_35) | Menentukan apakah matriks irisan DE-9IM dari geometri ini dan geometri yang ditentukan cocok dengan pola yang diberikan. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__36) | Mendapatkan poligon yang direpresentasikan sebagai garis dari geometri ini. |
| reverse() | Membalik urutan titik dalam [LineString](/psd/python-net/aspose.gis.geometries/linestring/). |
| [round_m(digits)](#round_m_digits_37) | Membulatkan koordinat M ke sejumlah digit desimal yang ditentukan. |
| [round_xy(digits)](#round_xy_digits_38) | Membulatkan koordinat X dan Y ke sejumlah digit desimal yang ditentukan. |
| [round_z(digits)](#round_z_digits_39) | Membulatkan koordinat Z ke sejumlah digit desimal yang ditentukan. |
| set_empty() | Membuat [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) ini kosong. |
| [spatially_contains(other)](#spatially_contains_other_40) | Menentukan apakah geometri ini secara spasial mengandung geometri yang ditentukan. |
| [spatially_equals(other)](#spatially_equals_other_41) | Menentukan apakah geometri ini secara spasial sama dengan geometri yang ditentukan. |
| [sym_difference(other)](#sym_difference_other_42) | Membangun selisih simetris antara geometri ini dan geometri yang ditentukan. |
| [to_editable()](#to_editable__43) | Mendapatkan salinan yang dapat diedit dari geometri ini. |
| [to_linear_geometry()](#to_linear_geometry__44) | Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> default. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_45) | Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> yang ditentukan. |
| [to_svg(extent)](#to_svg_extent_46) | Menerjemahkan geometri ini ke representasi Svg. |
| [touches(other)](#touches_other_47) | Menentukan apakah geometri ini dan geometri yang ditentukan bersentuhan. |
| [union(other)](#union_other_48) | Menggabungkan geometri ini dengan geometri yang ditentukan. |
| [union(other)](#union_other_49) | Menggabungkan geometri ini dengan geometri yang ditentukan. |
| [within(extent)](#within_extent_50) | Menentukan apakah geometri ini berada dalam batas yang ditentukan. |
| [within(other)](#within_other_51) | Menentukan apakah geometri ini berada dalam geometri yang ditentukan. |


### Constructor: LinearRing() {#LinearRing__1}


```
 LinearRing() 
```

Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

### Constructor: LinearRing(collection) {#LinearRing_collection_2}


```
 LinearRing(collection) 
```

Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| koleksi | System.Collections.Generic.IEnumerable<IPoint> | Koleksi titik. |

### Constructor: LinearRing(other) {#LinearRing_other_3}


```
 LinearRing(other) 
```

Menginisialisasi sebuah instance baru dari kelas [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Garis lain untuk menyalin data darinya. |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

Menambahkan sebuah titik ke akhir garis.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Titik yang akan ditambahkan. |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

Menambahkan sebuah titik ke akhir garis.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | Nilai untuk koordinat X. |
| y | double | Nilai untuk koordinat Y. |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

Menambahkan sebuah titik ke akhir garis.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | Nilai untuk koordinat X. |
| y | double | Nilai untuk koordinat Y. |
| z | double | Nilai untuk koordinat Z. |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

Menambahkan sebuah titik ke akhir garis.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | Nilai untuk koordinat X. |
| y | double | Nilai untuk koordinat Y. |
| z | double | Nilai untuk koordinat Z. |
| m | double | Nilai untuk koordinat M. |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

Menerjemahkan geometri ini ke representasi Well-Known Binary-nya.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Representasi Well-Known Binary dari geometri ini. |


### Method: as_binary(variant) {#as_binary_variant_6}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


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


### Method: as_text() {#as_text__10}


```
 as_text() 
```

Menerjemahkan geometri ini ke representasi Well-Known Text-nya.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Representasi Well-Known Text dari geometri ini. |


### Method: as_text(variant) {#as_text_variant_11}


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


### Method: as_text(variant, format) {#as_text_variant_format_12}


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


### Method: clone() {#clone__13}


```
 clone() 
```

Menggandakan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Klon dari instance ini |


### Method: covered_by(other) {#covered_by_other_14}


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


### Method: covers(other) {#covers_other_15}


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


### Method: crosses(other) {#crosses_other_16}


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


### Method: difference(other) {#difference_other_17}


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


### Method: disjoint(other) {#disjoint_other_18}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


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


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


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


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


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


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


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


### Method: get_area() {#get_area__23}


```
 get_area() 
```

Menghitung area geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Luas geometri ini.<br/>            Jumlah luas elemen-elemen geometri ini jika geometri ini adalah [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


```
 get_buffer(distance, quadrant_segments) 
```

Menghitung wilayah buffer di sekitar geometri ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jarak | double | Lebar wilayah buffer (dalam satuan Spatial Reference). |
| quadrant_segments | int | Jumlah segmen yang digunakan untuk mendekati kelengkungan 90 derajat.<br/>            Semakin besar angka ini, semakin baik pendekatan kurva yang dihasilkan.<br/>            Default adalah 30. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili semua titik yang berada dalam jarak tertentu dari<br/>            geometri ini.<br/>            Tipe hasilnya adalah salah satu dari [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) atau [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

Menghitung centroid geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Centroid dari geometri ini. Jika geometri ini kosong, sebuah titik kosong dikembalikan.<br/>            Centroid sama dengan centroid geometri dengan dimensi tertinggi dalam geometri ini<br/>            (misalnya jika baik titik maupun garis terdapat dalam geometri, hanya garis yang berkontribusi pada centroid). |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

Menghitung convex hull geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Sebuah geometri yang mewakili convex hull dari geometri ini.<br/>            Jika geometri ini tidak memiliki titik maka hasilnya adalah [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Jika geometri ini hanya memiliki satu titik maka hasilnya adalah titik tersebut.<br/>            Jika geometri ini hanya memiliki dua titik maka hasilnya adalah [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) dengan titik-titik tersebut.<br/>            Jika geometri ini memiliki tiga atau lebih titik maka hasilnya adalah [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) yang mewakili convex<br/>            hull di sekitar semua titik geometri. |


### Method: get_distance_to(other) {#get_distance_to_other_27}


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
| double | Jika kedua geometri tidak [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - jarak antara titik terdekat dari geometri.<br/>            Jika setidaknya satu geometri kosong, -1 dikembalikan. |


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

Menghitung dan mengembalikan batas wilayah geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Rentang batas dari geometri ini. |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

Menghitung panjang geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Panjang geometri ini.<br/>            Keliling jika ini adalah [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Jumlah panjang elemen-elemen geometri ini jika geometri ini adalah [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_30}


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


### Method: intersects(extent) {#intersects_extent_31}


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


### Method: intersects(other) {#intersects_other_32}


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


### Method: is_clockwise() {#is_clockwise__33}


```
 is_clockwise() 
```

Menentukan apakah cincin memiliki lilitan searah jarum jam.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword="true" /> jika searah jarum jam; selain itu <see langword="false" />. |


### Method: overlaps(other) {#overlaps_other_34}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_35}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__36}


```
 replace_polygons_by_lines() 
```

Mendapatkan poligon yang direpresentasikan sebagai garis dari geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometri yang tidak memiliki geometri poligon. Transformasi berikut diterapkan:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) di‑linear-kan<br/>            (diubah menjadi [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) digabungkan menjadi [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_37}


```
 round_m(digits) 
```

Membulatkan koordinat M ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: round_xy(digits) {#round_xy_digits_38}


```
 round_xy(digits) 
```

Membulatkan koordinat X dan Y ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: round_z(digits) {#round_z_digits_39}


```
 round_z(digits) 
```

Membulatkan koordinat Z ke sejumlah digit desimal yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| digits | int | Jumlah digit desimal. |

### Method: spatially_contains(other) {#spatially_contains_other_40}


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


### Method: spatially_equals(other) {#spatially_equals_other_41}


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


### Method: sym_difference(other) {#sym_difference_other_42}


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


### Method: to_editable() {#to_editable__43}


```
 to_editable() 
```

Mendapatkan salinan yang dapat diedit dari geometri ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LinearRing](/psd/python-net/aspose.gis.geometries/linearring) | Salinan yang dapat diedit dari geometri ini. |


### Method: to_linear_geometry() {#to_linear_geometry__44}


```
 to_linear_geometry() 
```

Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> default.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Sebuah [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) yang mendekati atau setara dengan kurva ini.<br/>            Ini adalah setara dengan <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) dengan<br/>            <c>tolerance</c> default. Nilai default <c>tolerance</c> bergantung pada [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            dari geometri ini:<br/>            <ul><br/>            <li> Untuk SRS terproyeksi Toleransi adalah 0.001 meter (dalam satuan SRS) </li><br/>            <li> Untuk SRS geografis Toleransi adalah <c>1e-5</c> derajat (dalam satuan SRS) </li><br/>            <li> Untuk SRS tidak diketahui Toleransi adalah <c>1e-5</c> </li><br/>            </ul><br/>            Untuk detail lebih lanjut tentang transformasi yang diterapkan, lihat spesifikasi <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_45}


```
 to_linear_geometry(tolerance) 
```

Mendapatkan versi non-kurva yang kira-kira atau setara dari geometri ini menggunakan <c>tolerance</c> yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tolerance | double | The <c>tolerance</c> yang digunakan. Hasil dijamin kurang dari <c>tolerance</c> dari geometri melengkung,<br/>             kecuali jumlah titik yang diperlukan untuk melinierkan geometri melebihi maksimum per kuadran,<br/>             saat ini sebesar 10000 titik. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Sebuah [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) yang mendekati atau setara dengan kurva ini:<br/>             <ul><br/>             Jika objek ini adalah [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) itu sendiri, hasilnya setara dengan objek ini<br/>             Jika objek ini adalah [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) hasilnya adalah string melingkar yang dilineariskan dengan <paramref name=\"tolerance\" /> yang ditentukan<br/>             Jika objek ini adalah [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) - semua kurva darinya dilineariskan dan kemudian digabung menjadi [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_46}


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


### Method: touches(other) {#touches_other_47}


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


### Method: union(other) {#union_other_48}


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


### Method: union(other) {#union_other_49}


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


### Method: within(extent) {#within_extent_50}


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


### Method: within(other) {#within_other_51}


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


