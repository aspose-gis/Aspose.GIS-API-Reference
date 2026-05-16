---
title: "Surface-klasse"
type: docs
weight: 320
url: /nl/python-net/aspose.gis.geometries/surface/
---

**Summary:** A [Surface](/psd/python-net/aspose.gis.geometries/surface/) is a two-dimensional geometric object.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Surface

**Inheritance:** IGeometry, ISurface, Geometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Haalt het aantal coördinaatdimensies op voor deze [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Haalt de topologische dimensie op van deze [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Haalt het type van de geometrie op. |
| has_curve_geometry | bool | r | Haalt een waarde op die aangeeft of deze geometrie curve (niet lineaire) geometrie is of bevat. |
| has_m | bool | r/w | Haalt een waarde op die aangeeft of deze instantie een M-coördinaat heeft. |
| has_z | bool | r/w | Haalt een waarde op die aangeeft of deze instantie een Z-coördinaat heeft. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze instantie leeg is. |
| is_simple | bool | r | Haalt een waarde op die aangeeft of deze instantie simpel is vanuit SFA-perspectief. |
| is_valid | bool | r | Haalt een waarde op die aangeeft of deze instantie geldig is. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Haalt een instantie van een null-geometry op. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Haalt SpatialReferenceSystem op van deze instantie.<br/>            Deze eigenschap kan <see langword=\"null\" /> zijn, als SpatialReferenceSystem onbekend is.<br/>            Het toewijzen van een nieuw SpatialReferenceSystem zal geen coördinatentransformatie uitvoeren, alleen de referentie wijzigen. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [as_binary()](#as_binary__1) | Vertaal deze geometrie naar zijn Well-Known Binary-representatie. |
| [as_binary(variant)](#as_binary_variant_2) | Vertaal deze geometrie naar zijn Well-Known Binary-representatie. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Exporteer deze geometrie naar een afbeeldingsrepresentatie. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Exporteer deze geometrie naar een afbeeldingsrepresentatie. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Exporteer deze geometrie naar een afbeeldingsrepresentatie. |
| [as_text()](#as_text__6) | Vertaal deze geometrie naar zijn Well-Known Text-representatie. |
| [as_text(variant)](#as_text_variant_7) | Vertaal deze geometrie naar zijn Well-Known Text-representatie. |
| [as_text(variant, format)](#as_text_variant_format_8) | Vertaal deze geometrie naar zijn Well-Known Text-representatie. |
| [clone()](#clone__9) | Kloont deze instantie. |
| [covered_by(other)](#covered_by_other_10) | Bepaalt of deze geometrie wordt gedekt door een opgegeven geometrie. |
| [covers(other)](#covers_other_11) | Bepaalt of deze geometrie een opgegeven geometrie dekt. |
| [crosses(other)](#crosses_other_12) | Bepaalt of deze geometrie en een opgegeven geometrie elkaar kruisen. |
| [difference(other)](#difference_other_13) | Trek een opgegeven geometrie af van deze geometrie. |
| [disjoint(other)](#disjoint_other_14) | Bepaalt of deze geometrie losstaat van een opgegeven geometrie. |
| [from_binary(wkb)](#from_binary_wkb_15) | Maakt een geometrie aan vanuit de Well-Known Binary-representatie. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_16) | Maakt een geometrie aan vanuit de Well-Known Binary-representatie. |
| [from_text(wkt)](#from_text_wkt_17) | Maakt een geometrie aan vanuit de Well-Known Text-representatie. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_18) | Maakt een geometrie aan vanuit de Well-Known Text-representatie. |
| [get_area()](#get_area__19) | Berekent de oppervlakte van deze geometrie. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_20) | Berekent een buffergebied rond deze geometrie. |
| [get_centroid()](#get_centroid__21) | Berekent het zwaartepunt van deze geometrie. |
| [get_convex_hull()](#get_convex_hull__22) | Berekent de convexe omhulling van deze geometrie. |
| [get_distance_to(other)](#get_distance_to_other_23) | Berekent de minimale afstand tussen deze geometrie en een opgegeven geometrie. |
| [get_extent()](#get_extent__24) | Berekent en retourneert een begrenzende extent van deze geometrie. |
| [get_length()](#get_length__25) | Berekent de lengte van deze geometrie. |
| [get_point_on_surface()](#get_point_on_surface__26) | Vindt een punt dat gegarandeerd op dit oppervlak ligt. |
| [intersection(other)](#intersection_other_27) | Bouwt een intersectie tussen deze geometrie en een opgegeven geometrie. |
| [intersects(extent)](#intersects_extent_28) | Bepaalt of deze geometrie een opgegeven extent intersecteert. |
| [intersects(other)](#intersects_other_29) | Bepaalt of deze geometrie en een opgegeven geometrie elkaar intersecteren. |
| [overlaps(other)](#overlaps_other_30) | Bepaalt of deze geometrie overlapt met een opgegeven geometrie. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_31) | Bepaalt of de DE-9IM-intersectiematrix van deze geometrie en een opgegeven geometrie overeenkomt met het opgegeven patroon. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__32) | Haalt polygonen op die als lijnen van deze geometrie worden weergegeven. |
| [round_m(digits)](#round_m_digits_33) | Rondt de M-coördinaat af naar een opgegeven aantal decimale cijfers. |
| [round_xy(digits)](#round_xy_digits_34) | Rondt de X- en Y-coördinaten af naar een opgegeven aantal decimale cijfers. |
| [round_z(digits)](#round_z_digits_35) | Rondt de Z-coördinaat af naar een opgegeven aantal decimale cijfers. |
| set_empty() | Maakt deze [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) leeg. |
| [spatially_contains(other)](#spatially_contains_other_36) | Bepaalt of deze geometrie ruimtelijk een opgegeven geometrie bevat. |
| [spatially_equals(other)](#spatially_equals_other_37) | Bepaalt of deze geometrie ruimtelijk gelijk is aan een opgegeven geometrie. |
| [sym_difference(other)](#sym_difference_other_38) | Bouwt een symmetrisch verschil tussen deze geometrie en een gespecificeerde geometrie. |
| [to_editable()](#to_editable__39) | Haalt een bewerkbare kopie van deze geometrie op. |
| [to_linear_geometry()](#to_linear_geometry__40) | Haalt een benaderende of equivalente niet-curve versie van deze geometrie op met de standaard <c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_41) | Haalt een benaderende of equivalente niet-curve versie van deze geometrie op met de opgegeven <c>tolerance</c>. |
| [to_svg(extent)](#to_svg_extent_42) | Zet deze geometrie om naar een Svg-representatie. |
| [touches(other)](#touches_other_43) | Bepaalt of deze geometrie en een gespecificeerde geometrie elkaar raken. |
| [union(other)](#union_other_44) | Voegt deze geometrie en een gespecificeerde geometrie samen. |
| [union(other)](#union_other_45) | Voegt deze geometrie en een gespecificeerde geometrie samen. |
| [within(extent)](#within_extent_46) | Bepaalt of deze geometrie zich binnen een gespecificeerde omvang bevindt. |
| [within(other)](#within_other_47) | Bepaalt of deze geometrie zich binnen een gespecificeerde geometrie bevindt. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Vertaal deze geometrie naar zijn Well-Known Binary-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Well-Known Binary-representatie van deze geometrie. |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

Vertaal deze geometrie naar zijn Well-Known Binary-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Well-Known Binary-variant om te gebruiken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Well-Known Binary-representatie van deze geometrie. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporteer deze geometrie naar een afbeeldingsrepresentatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de uitvoerafbeelding. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breedte van de kaart. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hoogte van de kaart. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer om te gebruiken. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporteer deze geometrie naar een afbeeldingsrepresentatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| output_pad | string | Pad naar de uitvoerafbeelding. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breedte van de kaart. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hoogte van de kaart. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer om te gebruiken. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

Exporteer deze geometrie naar een afbeeldingsrepresentatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breedte van de kaart. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hoogte van de kaart. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer om te gebruiken. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Een symbolizer om te gebruiken voor rendering. Als <see langword=\"null\" />, wordt de standaard symbolizer gebruikt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| _io.BufferedRandom | De afbeelding als stream |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Vertaal deze geometrie naar zijn Well-Known Text-representatie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Well-Known Text-representatie van deze geometrie. |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

Vertaal deze geometrie naar zijn Well-Known Text-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known Text-variant om te gebruiken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Well-Known Text-representatie van deze geometrie. |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

Vertaal deze geometrie naar zijn Well-Known Text-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known Text-variant om te gebruiken. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Coördinatenformaat voor conversie naar string. Zie de [NumericFormat](/psd/python-net/aspose.gis/numericformat/) voor meer informatie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Well-Known Text-representatie van deze geometrie. |


### Method: clone() {#clone__9}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | De kloon van deze instantie |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

Bepaalt of deze geometrie wordt gedekt door een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword=\"true\" /> als deze geometrie "ruimtelijk gedekt wordt door" een andere geometrie. <see langword=\"false\" /> anders. |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

Bepaalt of deze geometrie een opgegeven geometrie dekt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword=\"true\" /> als deze geometrie "ruimtelijk dekt" een andere geometrie. <see langword=\"false\" /> anders. |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

Bepaalt of deze geometrie en een opgegeven geometrie elkaar kruisen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword=\"true\" /> als deze geometrie "ruimtelijk kruist" een andere geometrie. <see langword=\"false\" /> anders. |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

Trek een opgegeven geometrie af van deze geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om af te trekken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die een verschil weergeeft tussen deze geometrie en een argument. De resulterende geometrie bevat<br/>            een puntenset die aanwezig is in deze geometrie maar niet aanwezig in een argument. |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

Bepaalt of deze geometrie losstaat van een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "ruimtelijk gescheiden" is van een andere geometrie. <see langword="false" /> anders. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_15}


```
 from_binary(wkb) 
```

Maakt een geometrie aan vanuit de Well-Known Binary-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-representatie van een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die wordt weergegeven door het argument. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_16}


```
 from_binary(wkb, spatial_reference_system) 
```

Maakt een geometrie aan vanuit de Well-Known Binary-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-representatie van een geometrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatial Reference System dat aan de geometrie moet worden toegewezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die wordt weergegeven door het argument. |


### Method: from_text(wkt)  [static] {#from_text_wkt_17}


```
 from_text(wkt) 
```

Maakt een geometrie aan vanuit de Well-Known Text-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkt | string | Well-Known Text-representatie van een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die wordt weergegeven door het argument. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_18}


```
 from_text(wkt, spatial_reference_system) 
```

Maakt een geometrie aan vanuit de Well-Known Text-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkt | string | Well-Known Text-representatie van een geometrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatial Reference System dat aan de geometrie moet worden toegewezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die wordt weergegeven door het argument. |


### Method: get_area() {#get_area__19}


```
 get_area() 
```

Berekent de oppervlakte van deze geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De oppervlakte van deze geometrie.<br/>            Som van de oppervlakten van de elementen van deze geometrie als deze geometrie een [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) is. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_20}


```
 get_buffer(distance, quadrant_segments) 
```

Berekent een buffergebied rond deze geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| afstand | double | De breedte van de bufferzone. |
| quadrant_segments | int | Aantal segmenten dat wordt gebruikt om een boog van 90 graden te benaderen.<br/>            Hoe groter dit aantal, hoe beter de benadering van de krommen.<br/>            Standaard is 30. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die alle punten weergeeft die zich binnen een gespecificeerde afstand van<br/>            deze geometrie bevinden.<br/>            Het type resultaat is ofwel [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) of [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__21}


```
 get_centroid() 
```

Berekent het zwaartepunt van deze geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Het zwaartepunt van deze geometrie. Als deze geometrie leeg is, wordt een leeg punt geretourneerd.<br/>            Het zwaartepunt is gelijk aan het zwaartepunt van de geometrieën met de hoogste dimensie in deze geometrie<br/>            (bijv. als zowel punten als lijnen in de geometrie aanwezig zijn, dragen alleen lijnen bij aan het zwaartepunt). |


### Method: get_convex_hull() {#get_convex_hull__22}


```
 get_convex_hull() 
```

Berekent de convexe omhulling van deze geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die de convexe omhulling van deze geometrie weergeeft.<br/>            Als deze geometrie geen punten heeft, is het resultaat [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Als deze geometrie slechts één punt heeft, is het resultaat dat punt.<br/>            Als deze geometrie slechts twee punten heeft, is het resultaat een [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) met die punten.<br/>            Als deze geometrie drie of meer punten heeft, is het resultaat een [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) dat een convexe<br/>            omhulling rond alle punten van de geometrieën vertegenwoordigt. |


### Method: get_distance_to(other) {#get_distance_to_other_23}


```
 get_distance_to(other) 
```

Berekent de minimale afstand tussen deze geometrie en een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om de afstand tot te vinden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | Als beide geometrieën niet [Geometry.is_empty](/psd/python-net/aspose.gis.geometries/geometry/) zijn - een afstand tussen de dichtstbijzijnde punten van de geometrieën.<br/>            Als ten minste één geometrie leeg is, wordt -1 geretourneerd. |


### Method: get_extent() {#get_extent__24}


```
 get_extent() 
```

Berekent en retourneert een begrenzende extent van deze geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Een begrenzende omvang van deze geometrie. |


### Method: get_length() {#get_length__25}


```
 get_length() 
```

Berekent de lengte van deze geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De lengte van deze geometrie.<br/>            Omtrek als dit een [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) is.<br/>            Som van de lengtes van de elementen van deze geometrie als deze geometrie een [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) is. |


### Method: get_point_on_surface() {#get_point_on_surface__26}


```
 get_point_on_surface() 
```

Vindt een punt dat gegarandeerd op dit oppervlak ligt.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Een punt op dit oppervlak. Een leeg punt als dit oppervlak geen binnenkant heeft. |


### Method: intersection(other) {#intersection_other_27}


```
 intersection(other) 
```

Bouwt een intersectie tussen deze geometrie en een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om een intersectie mee te berekenen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die een intersectie van deze geometrie en een argument weergeeft. De resulterende geometrie bevat<br/>            een puntenset die aanwezig is in zowel deze geometrie als een argument. |


### Method: intersects(extent) {#intersects_extent_28}


```
 intersects(extent) 
```

Bepaalt of deze geometrie een opgegeven extent intersecteert.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | De omvang. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie het gebied kruist; <see langword="false" /> anders. |


### Method: intersects(other) {#intersects_other_29}


```
 intersects(other) 
```

Bepaalt of deze geometrie en een opgegeven geometrie elkaar intersecteren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially intersects" een andere geometrie. <see langword="false" /> anders. |


### Method: overlaps(other) {#overlaps_other_30}


```
 overlaps(other) 
```

Bepaalt of deze geometrie overlapt met een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially overlaps" een andere geometrie. <see langword="false" /> anders. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_31}


```
 relate(other, intersection_pattern_matrix) 
```

Bepaalt of de DE-9IM-intersectiematrix van deze geometrie en een opgegeven geometrie overeenkomt met het opgegeven patroon.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |
| intersection_pattern_matrix | string | Een patroon om mee te vergelijken.<br/>            Dit moet een tekenreeks zijn met een lengte van 9.<br/>            Elk teken van de reeks vertegenwoordigt de verwachte dimensie van een intersectie:<br/>            <ul><br/>            <li>teken 0 - tussen de interieurs van de geometrieën.</li><br/>            <li>teken 1 - tussen het interieur van deze geometrie en de grens van een andere geometrie.</li><br/>            <li>teken 2 - tussen het interieur van deze geometrie en de buitenkant van een andere geometrie.</li><br/>            <li>teken 3 - tussen de grens van deze geometrie en het interieur van een andere geometrie.</li><br/>            <li>teken 4 - tussen de grenzen van de geometrieën.</li><br/>            <li>teken 5 - tussen de grens van deze geometrie en de buitenkant van een andere geometrie.</li><br/>            <li>teken 6 - tussen de buitenkant van deze geometrie en het interieur van een andere geometrie.</li><br/>            <li>teken 7 - tussen de buitenkant van deze geometrie en de grens van een andere geometrie.</li><br/>            <li>teken 8 - tussen de buitenkanten van de geometrieën.</li><br/>            </ul><br/>            Mogelijke waarden voor elk teken zijn:<br/>            <ul><br/>            <li>* - elke waarde;</li><br/>            <li>F - geen intersectie;</li><br/>            <li>T - elke intersectie;</li><br/>            <li>0 - puntintersectie (bijv. gedeeld punt);</li><br/>            <li>1 - lijnintersectie (bijv. gedeeld lijnsegment);</li><br/>            <li>2 - gebiedsintersectie (bijv. gedeeld deel van polygoon);</li><br/>            </ul><br/>            Bijvoorbeeld, een intersectiepatroon "F0*******" betekent dat er geen intersectie mag zijn tussen de interieurs van de geometrieën en dat intersectie tussen de grenzen van de geometrieën een punt moet zijn.<br/>            Zie de OpenGIS Simple Features Specification voor meer details over het intersectiematrixpatroon. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze intersectiematrix overeenkomt met het patroon; <see langword="false" /> anders. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__32}


```
 replace_polygons_by_lines() 
```

Haalt polygonen op die als lijnen van deze geometrie worden weergegeven.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die geen polygongeometrieën bevat. De volgende transformaties worden toegepast:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s worden gelineariseerd<br/>            (omgezet naar [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s worden samengevoegd tot [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_33}


```
 round_m(digits) 
```

Rondt de M-coördinaat af naar een opgegeven aantal decimale cijfers.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cijfers | int | Aantal fractionele cijfers. |

### Method: round_xy(digits) {#round_xy_digits_34}


```
 round_xy(digits) 
```

Rondt de X- en Y-coördinaten af naar een opgegeven aantal decimale cijfers.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cijfers | int | Aantal fractionele cijfers. |

### Method: round_z(digits) {#round_z_digits_35}


```
 round_z(digits) 
```

Rondt de Z-coördinaat af naar een opgegeven aantal decimale cijfers.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cijfers | int | Aantal fractionele cijfers. |

### Method: spatially_contains(other) {#spatially_contains_other_36}


```
 spatially_contains(other) 
```

Bepaalt of deze geometrie ruimtelijk een opgegeven geometrie bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially contains" een andere geometrie. <see langword="false" /> anders. |


### Method: spatially_equals(other) {#spatially_equals_other_37}


```
 spatially_equals(other) 
```

Bepaalt of deze geometrie ruimtelijk gelijk is aan een opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially equals" aan de opgegeven geometrie. <see langword="false" /> anders. |


### Method: sym_difference(other) {#sym_difference_other_38}


```
 sym_difference(other) 
```

Bouwt een symmetrisch verschil tussen deze geometrie en een gespecificeerde geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om de symmetrische verschil mee te berekenen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die een symmetrisch verschil van deze geometrie en een argument vertegenwoordigt. De resulterende geometrie bevat<br/>            een puntenset die aanwezig is in één van de geometrieën maar niet in beide. |


### Method: to_editable() {#to_editable__39}


```
 to_editable() 
```

Haalt een bewerkbare kopie van deze geometrie op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Surface](/psd/python-net/aspose.gis.geometries/surface) | Een bewerkbare kopie van deze geometrie. |


### Method: to_linear_geometry() {#to_linear_geometry__40}


```
 to_linear_geometry() 
```

Haalt een benaderende of equivalente niet-curve versie van deze geometrie op met de standaard <c>tolerance</c>.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Een [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) die een benadering of equivalent is van deze <c>ISurface</c>.<br/>            Dit is het equivalent van <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float) met<br/>            standaard <c>tolerance</c>. De standaardwaarde van <c>tolerance</c> is afhankelijk van [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) van deze geometrie:<br/>            <ul><br/>            <li> Voor een geprojecteerd SRS is de tolerantie 0.001 meter (in SRS-eenheden) </li><br/>            <li> Voor een geografisch SRS is de tolerantie <c>1e-5</c> graden (in SRS-eenheden) </li><br/>            <li> Voor een onbekend SRS is de tolerantie <c>1e-5</c> </li><br/>            </ul><br/>            Voor meer details over welke transformaties worden toegepast, zie de specificatie van <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_41}


```
 to_linear_geometry(tolerance) 
```

Haalt een benaderende of equivalente niet-curve versie van deze geometrie op met de opgegeven <c>tolerance</c>.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tolerantie | double | De <c>tolerance</c> die gebruikt moet worden. Het resultaat is gegarandeerd minder dan <c>tolerance</c> verwijderd van de<br/>             gebogen geometrie, tenzij het aantal punten dat nodig is om de geometrie te lineariseren het per‑kwadrant maximum overschrijdt,<br/>             momenteel gelijk aan 10000 punten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Een [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) die een benadering of equivalent is van deze <c>ISurface</c>:<br/>             <ul><br/>             Als dit object zelf een [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) is, is het resultaat equivalent aan dit object<br/>             Als dit object geen [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) is, wordt het gelineariseerd en wordt een [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) gecreëerd<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_42}


```
 to_svg(extent) 
```

Zet deze geometrie om naar een Svg-representatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Omvang voor het vertalen van deze geometrie naar Svg |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De Svg-representatie. |


### Method: touches(other) {#touches_other_43}


```
 touches(other) 
```

Bepaalt of deze geometrie en een gespecificeerde geometrie elkaar raken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially touches" een andere geometrie. <see langword="false" /> anders. |


### Method: union(other) {#union_other_44}


```
 union(other) 
```

Voegt deze geometrie en een gespecificeerde geometrie samen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om mee te verenigen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die een unie van deze geometrie en een argument vertegenwoordigt. De resulterende geometrie bevat<br/>            een puntenset die aanwezig is in deze geometrie of in een argument. |


### Method: union(other) {#union_other_45}


```
 union(other) 
```

Voegt deze geometrie en een gespecificeerde geometrie samen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie om mee te verenigen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie die een unie van deze geometrie en een argument vertegenwoordigt. De resulterende geometrie bevat<br/>            een puntenset die aanwezig is in deze geometrie of in een argument. |


### Method: within(extent) {#within_extent_46}


```
 within(extent) 
```

Bepaalt of deze geometrie zich binnen een gespecificeerde omvang bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | De omvang. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie binnen het gebied ligt; <see langword="false" /> anders. |


### Method: within(other) {#within_other_47}


```
 within(other) 
```

Bepaalt of deze geometrie zich binnen een gespecificeerde geometrie bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Een geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als deze geometrie "spatially within" een andere geometrie. <see langword="false" /> anders. |


