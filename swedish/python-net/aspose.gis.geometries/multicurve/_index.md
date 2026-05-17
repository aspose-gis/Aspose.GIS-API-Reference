---
title: "MultiCurve-klass"
type: docs
weight: 250
url: /sv/python-net/aspose.gis.geometries/multicurve/
---

**Summary:** A [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve/) is a one-dimensional [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) <br/>            whose elements are [Curve](/psd/python-net/aspose.gis.geometries/curve/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.MultiCurve

**Inheritance:** IGeometry, IGeometryCollection, IMultiCurve, GeometryCollection

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MultiCurve()](#MultiCurve__1) | Initierar en ny instans av klassen [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve/) |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Hämtar antalet koordinatdimensioner för detta [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| antal | int | r | Hämtar antalet geometrier i denna samling. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Hämtar den topologiska dimensionen för detta [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Hämtar geometrins typ. |
| has_curve_geometry | bool | r | Hämtar ett värde som indikerar om denna geometri är eller innehåller kurvgeometri (inte linjär). |
| has_m | bool | läs/skriv | Hämtar ett värde som indikerar om detta objekt har M-koordinat. |
| has_z | bool | läs/skriv | Hämtar ett värde som indikerar om detta objekt har Z-koordinat. |
| is_closed | bool | r | Bestämmer om denna kurva är sluten. |
| is_empty | bool | r | Hämtar ett värde som indikerar om detta objekt är tomt. |
| is_simple | bool | r | Hämtar ett värde som indikerar om detta objekt är enkelt ur SFA:s synvinkel. |
| is_valid | bool | r | Hämtar ett värde som indikerar om detta objekt är giltigt. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Hämtar en instans av null-geometri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Hämtar SpatialReferenceSystem för detta objekt.<br/>            Denna egenskap kan vara <see langword=\"null\" />, om SpatialReferenceSystem är okänt.<br/>            Tilldelning av ett nytt SpatialReferenceSystem kommer inte att utföra någon koordinattransformation, endast referensen kommer att ändras. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(geometry)](#add_geometry_1) | Lägger till den angivna geometrin i samlingen. |
| [add_range(geometries)](#add_range_geometries_2) | Lägger till de angivna geometrierna i samlingen. |
| [as_binary()](#as_binary__3) | Översätter denna geometri till dess Well-Known Binary-representation. |
| [as_binary(variant)](#as_binary_variant_4) | Översätter denna geometri till dess Well-Known Binary-representation. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Exporterar denna geometri till en bildrepresentation. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_6) | Exporterar denna geometri till en bildrepresentation. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_7) | Exporterar denna geometri till en bildrepresentation. |
| [as_text()](#as_text__8) | Översätter denna geometri till dess Well-Known Text-representation. |
| [as_text(variant)](#as_text_variant_9) | Översätter denna geometri till dess Well-Known Text-representation. |
| [as_text(variant, format)](#as_text_variant_format_10) | Översätter denna geometri till dess Well-Known Text-representation. |
| [clone()](#clone__11) | Klonar detta objekt. |
| [covered_by(other)](#covered_by_other_12) | Bestämmer om denna geometri täcks av en specificerad geometri. |
| [covers(other)](#covers_other_13) | Bestämmer om denna geometri täcker en specificerad geometri. |
| [crosses(other)](#crosses_other_14) | Bestämmer om denna geometri och en specificerad geometri korsar. |
| [difference(other)](#difference_other_15) | Subtraherar en specificerad geometri från denna geometri. |
| [disjoint(other)](#disjoint_other_16) | Bestämmer om denna geometri är disjunkt från en specificerad geometri. |
| [from_binary(wkb)](#from_binary_wkb_17) | Skapar en geometri från dess Well-Known Binary-representation. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_18) | Skapar en geometri från dess Well-Known Binary-representation. |
| [from_text(wkt)](#from_text_wkt_19) | Skapar en geometri från dess Well-Known Text-representation. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_20) | Skapar en geometri från dess Well-Known Text-representation. |
| [get_area()](#get_area__21) | Beräknar arean av denna geometri. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_22) | Beräknar ett buffertområde runt denna geometri. |
| [get_centroid()](#get_centroid__23) | Beräknar centroiden för denna geometri. |
| [get_convex_hull()](#get_convex_hull__24) | Beräknar den konvexa höljet för denna geometri. |
| [get_distance_to(other)](#get_distance_to_other_25) | Beräknar det minsta avståndet mellan denna geometri och en specificerad geometri. |
| [get_extent()](#get_extent__26) | Beräknar och returnerar en omgivande utbredning av denna geometri. |
| [get_length()](#get_length__27) | Beräknar längden på denna geometri. |
| [get_point_on_surface()](#get_point_on_surface__28) | Hittar en punkt som garanterat ligger på en av ytorna i denna samling. |
| [intersection(other)](#intersection_other_29) | Bygger en skärning mellan denna geometri och en specificerad geometri. |
| [intersects(extent)](#intersects_extent_30) | Bestämmer om denna geometri skär ett specificerat område. |
| [intersects(other)](#intersects_other_31) | Bestämmer om denna geometri och en specificerad geometri skär varandra. |
| [overlaps(other)](#overlaps_other_32) | Bestämmer om denna geometri överlappar med en specificerad geometri. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | Bestämmer om DE-9IM-skärningsmatrisen för denna geometri och en specificerad geometri matchar det angivna mönstret. |
| [remove_at(index)](#remove_at_index_34) | Tar bort den angivna geometrin från samlingen. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | Hämtar polygoner som representeras som linjer i denna geometri. |
| [round_m(digits)](#round_m_digits_36) | Avrundar M-koordinaten till ett specificerat antal decimaler. |
| [round_xy(digits)](#round_xy_digits_37) | Avrundar X- och Y-koordinaterna till ett specificerat antal decimaler. |
| [round_z(digits)](#round_z_digits_38) | Avrundar Z-koordinaten till ett specificerat antal decimaler. |
| set_empty() | Gör denna [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) tom. |
| [spatially_contains(other)](#spatially_contains_other_39) | Bestämmer om denna geometri rumsligt innehåller en specificerad geometri. |
| [spatially_equals(other)](#spatially_equals_other_40) | Bestämmer om denna geometri är rumsligt lika med en specificerad geometri. |
| [sym_difference(other)](#sym_difference_other_41) | Skapar en symmetrisk differens mellan denna geometri och en specificerad geometri. |
| [to_editable()](#to_editable__42) | Hämtar en redigerbar kopia av denna geometri. |
| [to_linear_geometry()](#to_linear_geometry__43) | Hämtar en ungefärlig eller motsvarande icke-kurv version av denna geometri med standard <c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | Hämtar en ungefärlig eller motsvarande icke-kurv version av denna geometri med den angivna <c>tolerance</c>. |
| [to_svg(extent)](#to_svg_extent_45) | Översätter denna geometri till Svg-representation. |
| [touches(other)](#touches_other_46) | Bestämmer om denna geometri och en specificerad geometri rör varandra. |
| [union(other)](#union_other_47) | Förenar denna geometri och en specificerad geometri. |
| [union(other)](#union_other_48) | Förenar denna geometri och en specificerad geometri. |
| [within(extent)](#within_extent_49) | Bestämmer om denna geometri ligger inom ett specificerat omfång. |
| [within(other)](#within_other_50) | Bestämmer om denna geometri ligger inom en specificerad geometri. |


### Constructor: MultiCurve() {#MultiCurve__1}


```
 MultiCurve() 
```

Initierar en ny instans av klassen [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve/)

### Method: add(geometry) {#add_geometry_1}


```
 add(geometry) 
```

Lägger till den angivna geometrin i samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Geometrin att lägga till. |

### Method: add_range(geometries) {#add_range_geometries_2}


```
 add_range(geometries) 
```

Lägger till de angivna geometrierna i samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometries | System.Collections.Generic.IEnumerable<IGeometry> | Geometrierna att lägga till. |

### Method: as_binary() {#as_binary__3}


```
 as_binary() 
```

Översätter denna geometri till dess Well-Known Binary-representation.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Well-Known Binary-representation av denna geometri. |


### Method: as_binary(variant) {#as_binary_variant_4}


```
 as_binary(variant) 
```

Översätter denna geometri till dess Well-Known Binary-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Well-Known Binary-variant att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Well-Known Binary-representation av denna geometri. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporterar denna geometri till en bildrepresentation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdata bilden. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Bredd på kartan. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höjd på kartan. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderare att använda. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_6}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporterar denna geometri till en bildrepresentation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| utdata_sökväg | string | Sökväg till utdata bilden. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Bredd på kartan. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höjd på kartan. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderare att använda. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_7}


```
 as_image(width, height, renderer, symbolizer) 
```

Exporterar denna geometri till en bildrepresentation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Bredd på kartan. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höjd på kartan. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderare att använda. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | En symbolizer att använda för rendering. Om <see langword="null" />, används standard symbolizer. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | Bilden som ström |


### Method: as_text() {#as_text__8}


```
 as_text() 
```

Översätter denna geometri till dess Well-Known Text-representation.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Well-Known Text-representation av denna geometri. |


### Method: as_text(variant) {#as_text_variant_9}


```
 as_text(variant) 
```

Översätter denna geometri till dess Well-Known Text-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known Text-variant att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Well-Known Text-representation av denna geometri. |


### Method: as_text(variant, format) {#as_text_variant_format_10}


```
 as_text(variant, format) 
```

Översätter denna geometri till dess Well-Known Text-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known Text-variant att använda. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Koordinatformat för konvertering till sträng. Se [NumericFormat](/psd/python-net/aspose.gis/numericformat/) för att få det. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Well-Known Text-representation av denna geometri. |


### Method: clone() {#clone__11}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Klona av detta objekt |


### Method: covered_by(other) {#covered_by_other_12}


```
 covered_by(other) 
```

Bestämmer om denna geometri täcks av en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om denna geometri är "spatially covered by" en annan geometri. <see langword="false" /> annars. |


### Method: covers(other) {#covers_other_13}


```
 covers(other) 
```

Bestämmer om denna geometri täcker en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om denna geometri "spatially covers" en annan geometri. <see langword="false" /> annars. |


### Method: crosses(other) {#crosses_other_14}


```
 crosses(other) 
```

Bestämmer om denna geometri och en specificerad geometri korsar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om denna geometri "spatially crosses" en annan geometri. <see langword="false" /> annars. |


### Method: difference(other) {#difference_other_15}


```
 difference(other) 
```

Subtraherar en specificerad geometri från denna geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att subtrahera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar skillnaden mellan denna geometri och ett argument. Resultatgeometrin innehåller<br/>            punktmängd som finns i denna geometri men inte i ett argument. |


### Method: disjoint(other) {#disjoint_other_16}


```
 disjoint(other) 
```

Bestämmer om denna geometri är disjunkt från en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri är \"rumsligt åtskild\" från en annan geometri. <see langword=\"false\" /> annars. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_17}


```
 from_binary(wkb) 
```

Skapar en geometri från dess Well-Known Binary-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-representation av en geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri representerad av argumentet. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_18}


```
 from_binary(wkb, spatial_reference_system) 
```

Skapar en geometri från dess Well-Known Binary-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-representation av en geometri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem som ska tilldelas geometrin. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri representerad av argumentet. |


### Method: from_text(wkt)  [static] {#from_text_wkt_19}


```
 from_text(wkt) 
```

Skapar en geometri från dess Well-Known Text-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkt | string | Well-Known Text-representation av en geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri representerad av argumentet. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_20}


```
 from_text(wkt, spatial_reference_system) 
```

Skapar en geometri från dess Well-Known Text-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkt | string | Well-Known Text-representation av en geometri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem som ska tilldelas geometrin. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri representerad av argumentet. |


### Method: get_area() {#get_area__21}


```
 get_area() 
```

Beräknar arean av denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Arean av denna geometri.<br/>            Summan av områdena för element i denna geometri om denna geometri är en [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_22}


```
 get_buffer(distance, quadrant_segments) 
```

Beräknar ett buffertområde runt denna geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| avstånd | double | Bredden på buffertområdet (i Spatial Reference-enheter). |
| quadrant_segments | int | Antal segment som används för att approximera en 90-graders kurvatur.<br/>            Ju större detta tal är, desto bättre blir kurvaproximationen.<br/>            Standardvärdet är 30. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar alla punkter som ligger inom ett specificerat avstånd från<br/>            denna geometri.<br/>            Resultattypen är antingen [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) eller [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__23}


```
 get_centroid() 
```

Beräknar centroiden för denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Centroiden för denna geometri. Om denna geometri är tom returneras en tom punkt.<br/>            Centroiden är lika med centroiden för de geometriska objekt med högst dimension i denna geometri<br/>            (t.ex. om både punkter och linjer finns i geometrin, bidrar endast linjer till centroiden). |


### Method: get_convex_hull() {#get_convex_hull__24}


```
 get_convex_hull() 
```

Beräknar den konvexa höljet för denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar ett konvext hölje för denna geometri.<br/>            Om denna geometri saknar punkter är resultatet [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Om denna geometri har endast en punkt är resultatet den punkten.<br/>            Om denna geometri har två punkter är resultatet ett [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) med punkterna.<br/>            Om denna geometri har tre eller fler punkter är resultatet ett [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) som representerar ett konvext<br/>            hölje runt alla geometripunkter. |


### Method: get_distance_to(other) {#get_distance_to_other_25}


```
 get_distance_to(other) 
```

Beräknar det minsta avståndet mellan denna geometri och en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att hitta avstånd till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Om båda geometrierna inte är [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - ett avstånd mellan de närmaste punkterna i geometrierna.<br/>            Om minst en geometri är tom returneras -1. |


### Method: get_extent() {#get_extent__26}


```
 get_extent() 
```

Beräknar och returnerar en omgivande utbredning av denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | En avgränsande omfattning av denna geometri. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

Beräknar längden på denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Längden på denna geometri.<br/>            Perimeter om detta är en [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Summan av längderna för element i denna geometri om denna geometri är en [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

Hittar en punkt som garanterat ligger på en av ytorna i denna samling.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | En punkt på en av ytorna. En tom punkt om denna samling inte innehåller ytor eller alla ytor är tomma. |


### Method: intersection(other) {#intersection_other_29}


```
 intersection(other) 
```

Bygger en skärning mellan denna geometri och en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att beräkna skärning med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar en skärning av denna geometri och ett argument. Resultatgeometrin innehåller<br/>            punktmängd som finns i både denna geometri och ett argument. |


### Method: intersects(extent) {#intersects_extent_30}


```
 intersects(extent) 
```

Bestämmer om denna geometri skär ett specificerat område.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Omfattningen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri skär avgränsningen; <see langword=\"false\" /> annars. |


### Method: intersects(other) {#intersects_other_31}


```
 intersects(other) 
```

Bestämmer om denna geometri och en specificerad geometri skär varandra.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt skär\" en annan geometri. <see langword=\"false\" /> annars. |


### Method: overlaps(other) {#overlaps_other_32}


```
 overlaps(other) 
```

Bestämmer om denna geometri överlappar med en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt överlappar\" en annan geometri. <see langword=\"false\" /> annars. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


```
 relate(other, intersection_pattern_matrix) 
```

Bestämmer om DE-9IM-skärningsmatrisen för denna geometri och en specificerad geometri matchar det angivna mönstret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |
| intersection_pattern_matrix | string | Ett mönster att matcha mot.<br/> Detta bör vara en sträng med längd lika med 9.<br/> Varje tecken i strängen representerar förväntad dimension av en skärning:<ul><br/><li>character 0 - mellan interiörerna hos geometrierna.</li><br/><li>character 1 - mellan interiören av denna geometri och gränsen av en annan geometri.</li><br/><li>character 2 - mellan interiören av denna geometri och exteriören av en annan geometri.</li><br/><li>character 3 - mellan gränsen av denna geometri och interiören av en annan geometri.</li><br/><li>character 4 - mellan gränserna hos geometrierna.</li><br/><li>character 5 - mellan gränsen av denna geometri och exteriören av en annan geometri.</li><br/><li>character 6 - mellan exteriören av denna geometri och interiören av en annan geometri.</li><br/><li>character 7 - mellan exteriören av denna geometri och gränsen av en annan geometri.</li><br/><li>character 8 - mellan exteriörerna hos geometrierna.</li><br/></ul><br/> Möjliga värden för varje tecken är:<ul><br/><li>* - vilket värde som helst;</li><br/><li>F - ingen skärning;</li><br/><li>T - någon skärning;</li><br/><li>0 - punktskärning (t.ex. gemensam punkt);</li><br/><li>1 - linjeskärning (t.ex. gemensamt linjesegment);</li><br/><li>2 - områdesskärning (t.ex. gemensam del av polygon);</li><br/></ul><br/> Till exempel betyder ett skärningsmönster \"F0*******\" att det inte får finnas någon skärning mellan geometriernas interiörer och att skärningen mellan geometriernas gränser måste vara en punkt. Se OpenGIS Simple Features Specification för mer detaljer om skärningsmatrisens mönster. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna skärningsmatris matchar mönstret; <see langword=\"false\" /> annars. |


### Method: remove_at(index) {#remove_at_index_34}


```
 remove_at(index) 
```

Tar bort den angivna geometrin från samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för geometrin som ska tas bort. |

### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

Hämtar polygoner som representeras som linjer i denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | En geometri som saknar polygongeometrier. Följande transformationer tillämpas:<br/> <ul><br/><li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s linjäriseras<br/> (omvandlas till [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/><li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s slås samman till [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/></ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

Avrundar M-koordinaten till ett specificerat antal decimaler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| siffror | int | Antal decimaler. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

Avrundar X- och Y-koordinaterna till ett specificerat antal decimaler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| siffror | int | Antal decimaler. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Avrundar Z-koordinaten till ett specificerat antal decimaler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| siffror | int | Antal decimaler. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

Bestämmer om denna geometri rumsligt innehåller en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt innehåller\" en annan geometri. <see langword=\"false\" /> annars. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

Bestämmer om denna geometri är rumsligt lika med en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt är lika med\" den angivna geometrin. <see langword=\"false\" /> annars. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

Skapar en symmetrisk differens mellan denna geometri och en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att beräkna symmetrisk differens med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar en symmetrisk differens av denna geometri och ett argument. Resultatgeometrin innehåller<br/> en punktmängd som finns i en av geometrierna men inte i båda. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

Hämtar en redigerbar kopia av denna geometri.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [MultiCurve](/psd/python-net/aspose.gis.geometries/multicurve) | En redigerbar kopia av denna geometri. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

Hämtar en ungefärlig eller motsvarande icke-kurv version av denna geometri med standard <c>tolerance</c>.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | En [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) som approximerar eller är motsvarande detta [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/).<br/>            Detta är motsvarigheten till <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) med<br/>            standard <c>tolerance</c>. Standardvärdet för <c>tolerance</c> beror på [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            av denna geometri:<br/>            <ul><br/>            <li> För projicerade SRS är toleransen 0.001 meter (i SRS-enheter) </li><br/>            <li> För geografiska SRS är toleransen <c>1e-5</c> grader (i SRS-enheter) </li><br/>            <li> För okända SRS är toleransen <c>1e-5</c> </li><br/>            </ul><br/>            För mer detaljer om vilka transformationer som tillämpas, se <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) specifikation. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

Hämtar en ungefärlig eller motsvarande icke-kurv version av denna geometri med den angivna <c>tolerance</c>.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tolerans | double | Den <c>tolerance</c> som ska användas. Resultatet garanteras vara mindre än <c>tolerance</c> från den<br/> kurviga geometrin, såvida inte antalet punkter som behövs för att linjärisera geometrin överstiger per‑kvadrant‑maximaltalet,<br/> som för närvarande är 10000 punkter. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | En [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) som approximerar eller är motsvarande detta [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/):<br/>             <ul><br/>             Om detta objekt är [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) själv är resultatet motsvarande detta objekt<br/>             Om detta objekt inte är [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/) - alla kurvor linjäriseras och en ny <c>IMultiLineString</c> skapas<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

Översätter denna geometri till Svg-representation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Omfång för översättning av denna geometri till Svg |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Svg-representationen. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

Bestämmer om denna geometri och en specificerad geometri rör varandra.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt rör\" en annan geometri. <see langword=\"false\" /> annars. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Förenar denna geometri och en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att förena med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar en union av denna geometri och ett argument. Resultatgeometrin innehåller<br/> en punktmängd som finns i denna geometri eller i ett argument. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

Förenar denna geometri och en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri att förena med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri som representerar en union av denna geometri och ett argument. Resultatgeometrin innehåller<br/> en punktmängd som finns i denna geometri eller i ett argument. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

Bestämmer om denna geometri ligger inom ett specificerat omfång.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Omfattningen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri är inom omfånget; <see langword=\"false\" /> annars. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

Bestämmer om denna geometri ligger inom en specificerad geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | En geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om denna geometri \"rumsligt ligger inom\" en annan geometri. <see langword=\"false\" /> annars. |


