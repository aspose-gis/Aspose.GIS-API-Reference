---
title: "IMultiCurve Sınıfı"
type: docs
weight: 150
url: /tr/python-net/aspose.gis.geometries/imulticurve/
---

**Summary:** A [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve/) is a one-dimensional [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) <br/>            whose elements are [Curve](/psd/python-net/aspose.gis.geometries/curve/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.IMultiCurve

**Inheritance:** IGeometryCollection, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| sayım | int | r | Bu koleksiyondaki geometri sayısını alır. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Bu [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) öğesinin topolojik boyutunu alır.<br/>            Boyut bilinmiyorsa (ör. boş bir GEOMETRYCOLLECTION için) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) döndürülür. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Geometrinin tipini alır. |
| has_curve_geometry | bool | r | Bu geometrinin eğri (doğrusal olmayan) geometri içerip içermediğini gösteren bir değer alır. |
| has_m | bool | r | Bu örneğin M koordinatına sahip olup olmadığını gösteren bir değer alır. |
| has_z | bool | r | Bu örneğin Z koordinatına sahip olup olmadığını gösteren bir değer alır. |
| is_empty | bool | r | Bu örneğin boş olup olmadığını gösteren bir değer alır (boş nokta kümesini temsil eder). |
| is_simple | bool | r | Bu örneğin SFA açısından basit olup olmadığını gösteren bir değer alır. |
| is_valid | bool | r | Bu örneğin geçerli olup olmadığını gösteren bir değer alır. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Bu örneğin SpatialReferenceSystem'ini alır.<br/>            SpatialReferenceSystem bilinmiyorsa bu özellik <see langword="null" /> olabilir. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Bu geometrinin Well-Known Binary temsiline dönüştürür. |
| [as_binary(variant)](#as_binary_variant_2) | Bu geometrinin Well-Known Binary temsiline dönüştürür. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_text()](#as_text__6) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [as_text(variant)](#as_text_variant_7) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [as_text(variant, format)](#as_text_variant_format_8) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [clone()](#clone__9) | Bu örneği klonlar. |
| [covered_by(other)](#covered_by_other_10) | Bu geometrinin belirtilen bir geometri tarafından kapsanıp kapsanmadığını belirler. |
| [covers(other)](#covers_other_11) | Bu geometrinin belirtilen bir geometriyi kapsayıp kapsamadığını belirler. |
| [crosses(other)](#crosses_other_12) | Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler. |
| [difference(other)](#difference_other_13) | Bu geometriden belirtilen bir geometriyi çıkarır. |
| [disjoint(other)](#disjoint_other_14) | Bu geometrinin belirtilen bir geometriyle ayrık olup olmadığını belirler. |
| [get_area()](#get_area__15) | Bu geometrinin alanını hesaplar. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | Bu geometrinin etrafında bir tampon bölge hesaplar. |
| [get_centroid()](#get_centroid__17) | Bu geometrinin ağırlık merkezini hesaplar. |
| [get_convex_hull()](#get_convex_hull__18) | Bu geometrinin konveks kılıfını hesaplar. |
| [get_distance_to(other)](#get_distance_to_other_19) | Bu geometri ile belirtilen bir geometri arasındaki minimum mesafeyi hesaplar. |
| [get_extent()](#get_extent__20) | Bu geometrinin sınırlayıcı kapsamını hesaplar ve döndürür. |
| [get_length()](#get_length__21) | Bu geometrinin uzunluğunu hesaplar. |
| [get_point_on_surface()](#get_point_on_surface__22) | Bu koleksiyondaki yüzeylerden birinde kesin olarak bulunacak bir nokta bulur. |
| [intersection(other)](#intersection_other_23) | Bu geometri ile belirtilen bir geometri arasında bir kesişim oluşturur. |
| [intersects(extent)](#intersects_extent_24) | Bu geometrinin belirtilen bir kapsamla kesişip kesişmediğini belirler. |
| [intersects(other)](#intersects_other_25) | Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler. |
| [overlaps(other)](#overlaps_other_26) | Bu geometrinin belirtilen bir geometriyle örtüşüp örtüşmediğini belirler. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_27) | Bu geometri ve belirtilen bir geometri için DE-9IM kesişim matrisinin sağlanan desenle eşleşip eşleşmediğini belirler. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__28) | Bu geometrinin çizgi olarak temsil edilen çokgenlerini alır. |
| [spatially_contains(other)](#spatially_contains_other_29) | Bu geometrinin belirtilen bir geometriyi mekânsal olarak içerip içermediğini belirler. |
| [spatially_equals(other)](#spatially_equals_other_30) | Bu geometrinin belirtilen bir geometriye mekânsal olarak eşit olup olmadığını belirler. |
| [sym_difference(other)](#sym_difference_other_31) | Bu geometri ile belirtilen geometri arasında simetrik fark oluşturur. |
| [to_editable()](#to_editable__32) | Bu geometrinin düzenlenebilir bir kopyasını alır. |
| [to_linear_geometry()](#to_linear_geometry__33) | Bu geometrinin varsayılan <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_34) | Bu geometrinin belirtilen <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır. |
| [touches(other)](#touches_other_35) | Bu geometri ile belirtilen geometrinin temas edip etmediğini belirler. |
| [union(other)](#union_other_36) | Bu geometriyi ve belirtilen geometriyi birleştirir. |
| [union(other)](#union_other_37) | Bu geometriyi ve belirtilen geometriyi birleştirir. |
| [within(extent)](#within_extent_38) | Bu geometrinin belirtilen kapsam içinde olup olmadığını belirler. |
| [within(other)](#within_other_39) | Bu geometrinin belirtilen geometri içinde olup olmadığını belirler. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Bu geometrinin Well-Known Binary temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bu geometrinin Well-Known Binary temsili. |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

Bu geometrinin Well-Known Binary temsiline dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Kullanılacak Well-Known Binary varyantı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bu geometrinin Well-Known Binary temsili. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Bu geometriyi bir görüntü temsiline dışa aktar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı görüntüsünün yolu. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın genişliği. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın yüksekliği. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Kullanılacak renderlayıcı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Bu geometriyi bir görüntü temsiline dışa aktar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| output_path | string | Çıktı görüntüsünün yolu. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın genişliği. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın yüksekliği. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Kullanılacak renderlayıcı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

Bu geometriyi bir görüntü temsiline dışa aktar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın genişliği. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Haritanın yüksekliği. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Kullanılacak renderlayıcı. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Renderleme için kullanılacak bir sembolleyici. Eğer <see langword="null" /> ise, varsayılan sembolleyici kullanılır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | Görüntü akış olarak |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Bu geometrinin Well-Known Text temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu geometrinin Well-Known Text temsili. |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

Bu geometrinin Well-Known Text temsiline dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Kullanılacak Well-Known Text varyantı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu geometrinin Well-Known Text temsili. |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

Bu geometrinin Well-Known Text temsiline dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Kullanılacak Well-Known Text varyantı. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Koordinat biçimi, dizeye dönüştürme için. Almak için [NumericFormat](/psd/python-net/aspose.gis/numericformat/) sayfasına bakın. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu geometrinin Well-Known Text temsili. |


### Method: clone() {#clone__9}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Bu örneğin kopyası |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

Bu geometrinin belirtilen bir geometri tarafından kapsanıp kapsanmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> bu geometri başka bir geometri tarafından "spatially covered by" ise. <see langword="false" /> aksi takdirde. |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

Bu geometrinin belirtilen bir geometriyi kapsayıp kapsamadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> bu geometri başka bir geometriyi "spatially covers" ise. <see langword="false" /> aksi takdirde. |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> bu geometri başka bir geometriyi "spatially crosses" ise. <see langword="false" /> aksi takdirde. |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

Bu geometriden belirtilen bir geometriyi çıkarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Çıkarma için bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometri ile bir argüman arasındaki farkı temsil eden bir geometri. Sonuç geometri,<br/>            bu geometride bulunan ancak argümanda bulunmayan nokta kümesini içerir. |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

Bu geometrinin belirtilen bir geometriyle ayrık olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> bu geometri başka bir geometriden \"mekansal olarak ayrık\" ise. <see langword=\"false\" /> aksi takdirde. |


### Method: get_area() {#get_area__15}


```
 get_area() 
```

Bu geometrinin alanını hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Bu geometrinin alanı.<br/>            Bu geometri bir [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ise, bu geometrinin öğelerinin alanlarının toplamı. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


```
 get_buffer(distance, quadrant_segments) 
```

Bu geometrinin etrafında bir tampon bölge hesaplar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| mesafe | double | Arabellek bölgesi genişliği (Spatial Reference birimlerinde). |
| quadrant_segments | int | 90 derecelik eğriliği yaklaşık olarak temsil etmek için kullanılan segment sayısı.<br/>            Bu sayı ne kadar büyük olursa, eğrilerin o kadar iyi yaklaşıklığı elde edilir.<br/>            Varsayılan değer 30'dur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Belirtilen bir mesafe içinde olan tüm noktaları temsil eden bir geometri.<br/>            bu geometriden.<br/>            Sonuç türü ya [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ya da [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) olur. |


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

Bu geometrinin ağırlık merkezini hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Bu geometrinin ağırlık merkezi. Geometri boşsa boş bir nokta döndürülür.<br/>            Ağırlık merkezi, bu geometrideki en yüksek boyutlu geometrilerin ağırlık merkezine eşittir<br/>            (ör. geometri hem nokta hem de çizgi içeriyorsa, sadece çizgiler ağırlık merkezine katkıda bulunur). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

Bu geometrinin konveks kılıfını hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometrinin konveks kılıfını temsil eden bir geometri.<br/>            Bu geometrinin hiç noktası yoksa sonuç [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) olur.<br/>            Bu geometrinin sadece bir noktası varsa sonuç bu nokta olur.<br/>            Bu geometrinin sadece iki noktası varsa sonuç noktalarla birlikte [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) olur.<br/>            Bu geometrinin üç veya daha fazla noktası varsa sonuç tüm geometrilerin noktaları etrafında konveks bir kılıfı temsil eden [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) olur. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


```
 get_distance_to(other) 
```

Bu geometri ile belirtilen bir geometri arasındaki minimum mesafeyi hesaplar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Mesafe bulunacak bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Her iki geometri de [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) değilse - geometrilerin en yakın noktaları arasındaki mesafe.<br/>            En az bir geometri boşsa -1 döndürülür. |


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

Bu geometrinin sınırlayıcı kapsamını hesaplar ve döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu geometrinin sınırlayıcı kapsamı. |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

Bu geometrinin uzunluğunu hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Bu geometrinin uzunluğu.<br/>            Bu bir [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) ise çevresi.<br/>            Bu geometri bir [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ise öğelerinin uzunluklarının toplamı. |


### Method: get_point_on_surface() {#get_point_on_surface__22}


```
 get_point_on_surface() 
```

Bu koleksiyondaki yüzeylerden birinde kesin olarak bulunacak bir nokta bulur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Yüzeylerden birinde bir nokta. Bu koleksiyon yüzey içermiyorsa veya tüm yüzeyler boşsa boş bir nokta. |


### Method: intersection(other) {#intersection_other_23}


```
 intersection(other) 
```

Bu geometri ile belirtilen bir geometri arasında bir kesişim oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Kesişimi hesaplanacak bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometri ile bir argümanın kesişimini temsil eden bir geometri. Sonuç geometri, bu geometri ve bir argümanda ortak olan nokta kümesini içerir.<br/>             |


### Method: intersects(extent) {#intersects_extent_24}


```
 intersects(extent) 
```

Bu geometrinin belirtilen bir kapsamla kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Kapsam. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri kapsamla kesişiyorsa; <see langword=\"false\" /> aksi takdirde. |


### Method: intersects(other) {#intersects_other_25}


```
 intersects(other) 
```

Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri başka bir geometriyle \"mekânsal olarak kesişiyorsa\". <see langword=\"false\" /> aksi takdirde. |


### Method: overlaps(other) {#overlaps_other_26}


```
 overlaps(other) 
```

Bu geometrinin belirtilen bir geometriyle örtüşüp örtüşmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri başka bir geometriyle \"mekânsal olarak üst üste geliyorsa\". <see langword=\"false\" /> aksi takdirde. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_27}


```
 relate(other, intersection_pattern_matrix) 
```

Bu geometri ve belirtilen bir geometri için DE-9IM kesişim matrisinin sağlanan desenle eşleşip eşleşmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |
| intersection_pattern_matrix | string | Eşleşecek bir desen.<br/>            Bu, uzunluğu 9 olan bir dize olmalıdır.<br/>            Dizedeki her karakter, bir kesişmenin beklenen boyutunu temsil eder:<br/>            <ul><br/>            <li>character 0 - geometrilerin iç kısımları arasında.</li><br/>            <li>character 1 - bu geometrinin iç kısmı ile başka bir geometrinin sınırı arasında.</li><br/>            <li>character 2 - bu geometrinin iç kısmı ile başka bir geometrinin dış kısmı arasında.</li><br/>            <li>character 3 - bu geometrinin sınırı ile başka bir geometrinin iç kısmı arasında.</li><br/>            <li>character 4 - geometrilerin sınırları arasında.</li><br/>            <li>character 5 - bu geometrinin sınırı ile başka bir geometrinin dış kısmı arasında.</li><br/>            <li>character 6 - bu geometrinin dış kısmı ile başka bir geometrinin iç kısmı arasında.</li><br/>            <li>character 7 - bu geometrinin dış kısmı ile başka bir geometrinin sınırı arasında.</li><br/>            <li>character 8 - geometrilerin dış kısımları arasında.</li><br/>            </ul><br/>            Her karakterin olası değerleri şunlardır:<br/>            <ul><br/>            <li>* - herhangi bir değer;</li><br/>            <li>F - kesişme yok;</li><br/>            <li>T - herhangi bir kesişme;</li><br/>            <li>0 - nokta kesişmesi (örn. ortak nokta);</li><br/>            <li>1 - çizgi kesişmesi (örn. ortak çizgi segmenti);</li><br/>            <li>2 - alan kesişmesi (örn. ortak çokgen parçası);</li><br/>            </ul><br/>            Örneğin, \"F0*******\" kesişim deseni, geometrilerin iç kısımları arasında kesişme olmaması gerektiği ve geometrilerin sınırları arasındaki kesişmenin bir nokta olması gerektiği anlamına gelir.<br/>            Kesişim matrisi deseni hakkında daha fazla ayrıntı için OpenGIS Simple Features Specification bölümüne bakınız. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu kesişim matrisi desene uyuyorsa; <see langword=\"false\" /> aksi takdirde. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__28}


```
 replace_polygons_by_lines() 
```

Bu geometrinin çizgi olarak temsil edilen çokgenlerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | Poligon geometrileri olmayan bir geometri. Aşağıdaki dönüşümler uygulanır:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)ler doğrusal hale getirilir<br/>            ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)lere dönüştürülür)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)ler [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)lere birleştirilir</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_29}


```
 spatially_contains(other) 
```

Bu geometrinin belirtilen bir geometriyi mekânsal olarak içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri başka bir geometriyi \"mekânsal olarak içeriyorsa\". <see langword=\"false\" /> aksi takdirde. |


### Method: spatially_equals(other) {#spatially_equals_other_30}


```
 spatially_equals(other) 
```

Bu geometrinin belirtilen bir geometriye mekânsal olarak eşit olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri belirtilen geometriye \"mekânsal olarak eşitse\". <see langword=\"false\" /> aksi takdirde. |


### Method: sym_difference(other) {#sym_difference_other_31}


```
 sym_difference(other) 
```

Bu geometri ile belirtilen geometri arasında simetrik fark oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Simetrik farkı hesaplamak için bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometri ile bir argümanın simetrik farkını temsil eden bir geometri. Sonuç geometrisi şunu içerir<br/>            bir geometride bulunan ancak ikisinde de bulunmayan nokta kümesi. |


### Method: to_editable() {#to_editable__32}


```
 to_editable() 
```

Bu geometrinin düzenlenebilir bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve) | Bu geometrinin düzenlenebilir bir kopyası. |


### Method: to_linear_geometry() {#to_linear_geometry__33}


```
 to_linear_geometry() 
```

Bu geometrinin varsayılan <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | Bu [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) bu [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) öğesine yaklaşık veya eşdeğerdir.<br/>            Bu, <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) varsayılan <c>tolerance</c> ile eşdeğeridir.<br/>            Varsayılan <c>tolerance</c> değeri bu geometriye ait [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) tarafından belirlenir:<br/>            <ul><br/>            <li> Projeksiyonlu SRS için tolerans 0.001 metre (SRS birimlerinde) </li><br/>            <li> Coğrafi SRS için tolerans <c>1e-5</c> derece (SRS birimlerinde) </li><br/>            <li> Bilinmeyen SRS için tolerans <c>1e-5</c> </li><br/>            </ul><br/>            Uygulanan dönüşümler hakkında daha fazla ayrıntı için <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) spesifikasyonuna bakınız. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_34}


```
 to_linear_geometry(tolerance) 
```

Bu geometrinin belirtilen <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tolerans | double | Kullanılacak <c>tolerance</c>. Sonuç, <c>tolerance</c> değerinden daha az bir farkla eğri geometriden uzak olacak şekilde garantilenir,<br/>             ancak geometrinin doğrusal hale getirilmesi için gereken nokta sayısı çeyrek başına maksimum değeri, şu anda 10000 nokta olanı, aşarsa. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | Bu [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) bu [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) öğesine yaklaşık veya eşdeğerdir:<br/>             <ul><br/>             Eğer bu nesne kendisi bir [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) ise sonuç bu nesneye eşdeğerdir<br/>             Eğer bu nesne bir [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) değilse - tüm eğriler doğrusal hale getirilir ve yeni bir <c>IMultiLineString</c> oluşturulur<br/>            </ul> |


### Method: touches(other) {#touches_other_35}


```
 touches(other) 
```

Bu geometri ile belirtilen geometrinin temas edip etmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri başka bir geometriye \"mekânsal olarak dokunuyorsa\". <see langword=\"false\" /> aksi takdirde. |


### Method: union(other) {#union_other_36}


```
 union(other) 
```

Bu geometriyi ve belirtilen geometriyi birleştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Birleştirilecek bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometri ile bir argümanın birleşimini temsil eden bir geometri. Sonuç geometrisi şunu içerir<br/>            bu geometride veya bir argümanda bulunan nokta kümesi. |


### Method: union(other) {#union_other_37}


```
 union(other) 
```

Bu geometriyi ve belirtilen geometriyi birleştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Birleştirilecek bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometri ile bir argümanın birleşimini temsil eden bir geometri. Sonuç geometrisi şunu içerir<br/>            bu geometride veya bir argümanda bulunan nokta kümesi. |


### Method: within(extent) {#within_extent_38}


```
 within(extent) 
```

Bu geometrinin belirtilen kapsam içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Kapsam. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri kapsam içindeyse; <see langword=\"false\" /> aksi takdirde. |


### Method: within(other) {#within_other_39}


```
 within(other) 
```

Bu geometrinin belirtilen geometri içinde olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> eğer bu geometri başka bir geometri içinde \"mekânsal olarak\" ise. <see langword=\"false\" /> aksi takdirde. |


