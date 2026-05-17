---
title: "CurvePolygon Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.gis.geometries/curvepolygon/
---

**Summary:** A planar surface, defined by 1 exterior boundary and 0 or more interior boundaries.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.CurvePolygon

**Inheritance:** IGeometry, ISurface, ICurvePolygon, Surface

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvePolygon()](#CurvePolygon__1) | Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır. |
| [CurvePolygon(exterior_ring)](#CurvePolygon_exterior_ring_2) | Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır. |
| [CurvePolygon(exterior_ring, interior_rings)](#CurvePolygon_exterior_ring_interior_rings_3) | Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Bu [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) için koordinat boyutlarının sayısını alır. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Bu [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) için topolojik boyutu alır. |
| exterior_ring | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | r/w | Dış halkayı alır. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Geometrinin tipini alır. |
| has_curve_geometry | bool | r | Bu geometrinin eğri (doğrusal olmayan) geometri içerip içermediğini gösteren bir değer alır. |
| has_m | bool | r/w | Bu örneğin M koordinatına sahip olup olmadığını gösteren bir değer alır. |
| has_z | bool | r/w | Bu örneğin Z koordinatına sahip olup olmadığını gösteren bir değer alır. |
| interior_rings_count | int | r | İç halkaların sayısını alır. |
| is_empty | bool | r | Bu örneğin boş olup olmadığını gösteren bir değer alır. |
| is_simple | bool | r | Bu örneğin SFA açısından basit olup olmadığını gösteren bir değer alır. |
| is_valid | bool | r | Bu örneğin geçerli olup olmadığını gösteren bir değer alır. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Null geometri örneğini alır. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Bu örneğin SpatialReferenceSystem'ini alır.<br/>            Bu özellik <see langword=\"null\" /> olabilir, SpatialReferenceSystem bilinmiyordur.<br/>            Yeni bir SpatialReferenceSystem atamak herhangi bir koordinat dönüşümü yapmaz, sadece referans değişir. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_interior_ring(ring)](#add_interior_ring_ring_1) | Bir iç halka ekler. |
| [as_binary()](#as_binary__2) | Bu geometrinin Well-Known Binary temsiline dönüştürür. |
| [as_binary(variant)](#as_binary_variant_3) | Bu geometrinin Well-Known Binary temsiline dönüştürür. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_6) | Bu geometriyi bir görüntü temsiline dışa aktar. |
| [as_text()](#as_text__7) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [as_text(variant)](#as_text_variant_8) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [as_text(variant, format)](#as_text_variant_format_9) | Bu geometrinin Well-Known Text temsiline dönüştürür. |
| [clone()](#clone__10) | Bu örneği klonlar. |
| [covered_by(other)](#covered_by_other_11) | Bu geometrinin belirtilen bir geometri tarafından kapsanıp kapsanmadığını belirler. |
| [covers(other)](#covers_other_12) | Bu geometrinin belirtilen bir geometriyi kapsayıp kapsamadığını belirler. |
| [crosses(other)](#crosses_other_13) | Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler. |
| [difference(other)](#difference_other_14) | Bu geometriden belirtilen bir geometriyi çıkarır. |
| [disjoint(other)](#disjoint_other_15) | Bu geometrinin belirtilen bir geometriyle ayrık olup olmadığını belirler. |
| [from_binary(wkb)](#from_binary_wkb_16) | Bir geometrinin Well-Known Binary temsilinden bir geometri oluşturur. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_17) | Bir geometrinin Well-Known Binary temsilinden bir geometri oluşturur. |
| [from_text(wkt)](#from_text_wkt_18) | Bir geometrinin Well-Known Text temsilinden bir geometri oluşturur. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_19) | Bir geometrinin Well-Known Text temsilinden bir geometri oluşturur. |
| [get_area()](#get_area__20) | Bu geometrinin alanını hesaplar. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_21) | Bu geometrinin etrafında bir tampon bölge hesaplar. |
| [get_centroid()](#get_centroid__22) | Bu geometrinin ağırlık merkezini hesaplar. |
| [get_convex_hull()](#get_convex_hull__23) | Bu geometrinin konveks kılıfını hesaplar. |
| [get_distance_to(other)](#get_distance_to_other_24) | Bu geometri ile belirtilen bir geometri arasındaki minimum mesafeyi hesaplar. |
| [get_extent()](#get_extent__25) | Bu geometrinin sınırlayıcı kapsamını hesaplar ve döndürür. |
| [get_interior_ring(index)](#get_interior_ring_index_26) | İç halkayı indeksine göre alır. |
| [get_length()](#get_length__27) | Bu geometrinin uzunluğunu hesaplar. |
| [get_point_on_surface()](#get_point_on_surface__28) | Bu eğimli çokgenin üzerinde olması garantilenmiş bir nokta bulur. |
| [intersection(other)](#intersection_other_29) | Bu geometri ile belirtilen bir geometri arasında bir kesişim oluşturur. |
| [intersects(extent)](#intersects_extent_30) | Bu geometrinin belirtilen bir kapsamla kesişip kesişmediğini belirler. |
| [intersects(other)](#intersects_other_31) | Bu geometri ile belirtilen bir geometrinin kesişip kesişmediğini belirler. |
| [overlaps(other)](#overlaps_other_32) | Bu geometrinin belirtilen bir geometriyle örtüşüp örtüşmediğini belirler. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | Bu geometri ve belirtilen bir geometri için DE-9IM kesişim matrisinin sağlanan desenle eşleşip eşleşmediğini belirler. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__34) | Bu geometrinin çizgi olarak temsil edilen çokgenlerini alır. |
| [round_m(digits)](#round_m_digits_35) | M koordinatını belirtilen sayıda ondalık basamağa yuvarlar. |
| [round_xy(digits)](#round_xy_digits_36) | X ve Y koordinatlarını belirtilen sayıda ondalık basamağa yuvarlar. |
| [round_z(digits)](#round_z_digits_37) | Z koordinatını belirtilen sayıda ondalık basamağa yuvarlar. |
| set_empty() | Bu [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) nesnesini boş hale getirir. |
| [spatially_contains(other)](#spatially_contains_other_38) | Bu geometrinin belirtilen bir geometriyi mekânsal olarak içerip içermediğini belirler. |
| [spatially_equals(other)](#spatially_equals_other_39) | Bu geometrinin belirtilen bir geometriye mekânsal olarak eşit olup olmadığını belirler. |
| [sym_difference(other)](#sym_difference_other_40) | Bu geometri ile belirtilen geometri arasında simetrik fark oluşturur. |
| [to_editable()](#to_editable__41) | Bu geometrinin düzenlenebilir bir kopyasını alır. |
| [to_linear_geometry()](#to_linear_geometry__42) | Bu geometrinin varsayılan <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_43) | Bu geometrinin belirtilen <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır. |
| [to_svg(extent)](#to_svg_extent_44) | Bu geometriyi Svg temsiline dönüştürür. |
| [touches(other)](#touches_other_45) | Bu geometri ile belirtilen geometrinin temas edip etmediğini belirler. |
| [union(other)](#union_other_46) | Bu geometriyi ve belirtilen geometriyi birleştirir. |
| [union(other)](#union_other_47) | Bu geometriyi ve belirtilen geometriyi birleştirir. |
| [within(extent)](#within_extent_48) | Bu geometrinin belirtilen kapsam içinde olup olmadığını belirler. |
| [within(other)](#within_other_49) | Bu geometrinin belirtilen geometri içinde olup olmadığını belirler. |


### Constructor: CurvePolygon() {#CurvePolygon__1}


```
 CurvePolygon() 
```

Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır.

### Constructor: CurvePolygon(exterior_ring) {#CurvePolygon_exterior_ring_2}


```
 CurvePolygon(exterior_ring) 
```

Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exterior_ring | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | Dış halka. |

### Constructor: CurvePolygon(exterior_ring, interior_rings) {#CurvePolygon_exterior_ring_interior_rings_3}


```
 CurvePolygon(exterior_ring, interior_rings) 
```

Yeni bir [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exterior_ring | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | Dış halka. |
| iç_halkalar | System.Collections.Generic.IEnumerable<ICurve> | İç halkalar. |

### Method: add_interior_ring(ring) {#add_interior_ring_ring_1}


```
 add_interior_ring(ring) 
```

Bir iç halka ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ring | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | Eklenecek halka. |

### Method: as_binary() {#as_binary__2}


```
 as_binary() 
```

Bu geometrinin Well-Known Binary temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bu geometrinin Well-Known Binary temsili. |


### Method: as_binary(variant) {#as_binary_variant_3}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_6}


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


### Method: as_text() {#as_text__7}


```
 as_text() 
```

Bu geometrinin Well-Known Text temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu geometrinin Well-Known Text temsili. |


### Method: as_text(variant) {#as_text_variant_8}


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


### Method: as_text(variant, format) {#as_text_variant_format_9}


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


### Method: clone() {#clone__10}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Bu örneğin kopyası |


### Method: covered_by(other) {#covered_by_other_11}


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


### Method: covers(other) {#covers_other_12}


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


### Method: crosses(other) {#crosses_other_13}


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


### Method: difference(other) {#difference_other_14}


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


### Method: disjoint(other) {#disjoint_other_15}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_16}


```
 from_binary(wkb) 
```

Bir geometrinin Well-Known Binary temsilinden bir geometri oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkb | byte | Bir geometrinin Well-Known Binary temsili. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Argüman tarafından temsil edilen bir geometri. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_17}


```
 from_binary(wkb, spatial_reference_system) 
```

Bir geometrinin Well-Known Binary temsilinden bir geometri oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkb | byte | Bir geometrinin Well-Known Binary temsili. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Geometriye atanacak Uzamsal Referans Sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Argüman tarafından temsil edilen bir geometri. |


### Method: from_text(wkt)  [static] {#from_text_wkt_18}


```
 from_text(wkt) 
```

Bir geometrinin Well-Known Text temsilinden bir geometri oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkt | string | Bir geometrinin Well-Known Text temsili. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Argüman tarafından temsil edilen bir geometri. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_19}


```
 from_text(wkt, spatial_reference_system) 
```

Bir geometrinin Well-Known Text temsilinden bir geometri oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkt | string | Bir geometrinin Well-Known Text temsili. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Geometriye atanacak Uzamsal Referans Sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Argüman tarafından temsil edilen bir geometri. |


### Method: get_area() {#get_area__20}


```
 get_area() 
```

Bu geometrinin alanını hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Bu geometrinin alanı.<br/>            Bu geometri bir [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ise, bu geometrinin öğelerinin alanlarının toplamı. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_21}


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


### Method: get_centroid() {#get_centroid__22}


```
 get_centroid() 
```

Bu geometrinin ağırlık merkezini hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Bu geometrinin ağırlık merkezi. Geometri boşsa boş bir nokta döndürülür.<br/>            Ağırlık merkezi, bu geometrideki en yüksek boyutlu geometrilerin ağırlık merkezine eşittir<br/>            (ör. geometri hem nokta hem de çizgi içeriyorsa, sadece çizgiler ağırlık merkezine katkıda bulunur). |


### Method: get_convex_hull() {#get_convex_hull__23}


```
 get_convex_hull() 
```

Bu geometrinin konveks kılıfını hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Bu geometrinin konveks kılıfını temsil eden bir geometri.<br/>            Bu geometrinin hiç noktası yoksa sonuç [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) olur.<br/>            Bu geometrinin sadece bir noktası varsa sonuç bu nokta olur.<br/>            Bu geometrinin sadece iki noktası varsa sonuç noktalarla birlikte [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) olur.<br/>            Bu geometrinin üç veya daha fazla noktası varsa sonuç tüm geometrilerin noktaları etrafında konveks bir kılıfı temsil eden [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) olur. |


### Method: get_distance_to(other) {#get_distance_to_other_24}


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


### Method: get_extent() {#get_extent__25}


```
 get_extent() 
```

Bu geometrinin sınırlayıcı kapsamını hesaplar ve döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu geometrinin sınırlayıcı kapsamı. |


### Method: get_interior_ring(index) {#get_interior_ring_index_26}


```
 get_interior_ring(index) 
```

İç halkayı indeksine göre alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | İndeks. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | İç halka. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

Bu geometrinin uzunluğunu hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Bu geometrinin uzunluğu.<br/>            Bu bir [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) ise çevresi.<br/>            Bu geometri bir [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ise öğelerinin uzunluklarının toplamı. |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

Bu eğimli çokgenin üzerinde olması garantilenmiş bir nokta bulur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Bu eğimli çokgen üzerindeki bir nokta. Çokgenin içi yoksa boş bir nokta. |


### Method: intersection(other) {#intersection_other_29}


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


### Method: intersects(extent) {#intersects_extent_30}


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


### Method: intersects(other) {#intersects_other_31}


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


### Method: overlaps(other) {#overlaps_other_32}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__34}


```
 replace_polygons_by_lines() 
```

Bu geometrinin çizgi olarak temsil edilen çokgenlerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Poligon geometrileri olmayan bir geometri. Aşağıdaki dönüşümler uygulanır:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)ler doğrusal hale getirilir<br/>            ( [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)lere dönüştürülür)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)ler [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)lere birleştirilir</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_35}


```
 round_m(digits) 
```

M koordinatını belirtilen sayıda ondalık basamağa yuvarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| basamaklar | int | Kesirli basamak sayısı. |

### Method: round_xy(digits) {#round_xy_digits_36}


```
 round_xy(digits) 
```

X ve Y koordinatlarını belirtilen sayıda ondalık basamağa yuvarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| basamaklar | int | Kesirli basamak sayısı. |

### Method: round_z(digits) {#round_z_digits_37}


```
 round_z(digits) 
```

Z koordinatını belirtilen sayıda ondalık basamağa yuvarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| basamaklar | int | Kesirli basamak sayısı. |

### Method: spatially_contains(other) {#spatially_contains_other_38}


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


### Method: spatially_equals(other) {#spatially_equals_other_39}


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


### Method: sym_difference(other) {#sym_difference_other_40}


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


### Method: to_editable() {#to_editable__41}


```
 to_editable() 
```

Bu geometrinin düzenlenebilir bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurvePolygon](/psd/python-net/aspose.gis.geometries/curvepolygon) | Bu geometrinin düzenlenebilir bir kopyası. |


### Method: to_linear_geometry() {#to_linear_geometry__42}


```
 to_linear_geometry() 
```

Bu geometrinin varsayılan <c>tolerance</c> kullanılarak yaklaşık veya eşdeğer eğri olmayan sürümünü alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Bu <c>ISurface</c>e yaklaşık veya eşdeğer bir [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/).<br/>            Bu, <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float) ile varsayılan <c>tolerance</c> kullanılarak eşdeğerdir.<br/>            Varsayılan <c>tolerance</c> değeri, bu geometrinin [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) bağlıdır:<br/>            <ul><br/>            <li> Projeksiyonlu SRS için Tolerans 0.001 metre (SRS birimlerinde) </li><br/>            <li> Coğrafi SRS için Tolerans <c>1e-5</c> derece (SRS birimlerinde) </li><br/>            <li> Bilinmeyen SRS için Tolerans <c>1e-5</c> </li><br/>            </ul><br/>            Uygulanan dönüşümler hakkında daha fazla ayrıntı için <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float) spesifikasyonuna bakınız. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_43}


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
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Bu <c>ISurface</c>e yaklaşık veya eşdeğer bir [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/):<br/>             <ul><br/>             Eğer bu nesne kendisi bir [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ise sonuç bu nesneye eşittir<br/>             Eğer bu nesne bir [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) değilse, doğrusal hale getirilir ve bir [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) oluşturulur<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_44}


```
 to_svg(extent) 
```

Bu geometriyi Svg temsiline dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Bu geometrinin Svg'ye dönüştürülmesi için kapsam |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Svg temsili. |


### Method: touches(other) {#touches_other_45}


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


### Method: union(other) {#union_other_46}


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


### Method: union(other) {#union_other_47}


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


### Method: within(extent) {#within_extent_48}


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


### Method: within(other) {#within_other_49}


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


