---
title: "Polygon Klasse"
type: docs
weight: 310
url: /de/python-net/aspose.gis.geometries/polygon/
---

**Summary:** A [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) is a planar surface,<br/>            defined by 1 exterior boundary and 0 or more interior boundaries.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Polygon

**Inheritance:** IGeometry, ISurface, IPolygon, ICurvePolygon, Surface

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Polygon()](#Polygon__1) | Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse. |
| [Polygon(exterior_ring)](#Polygon_exterior_ring_2) | Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse. |
| [Polygon(exterior_ring, interior_rings)](#Polygon_exterior_ring_interior_rings_3) | Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Gibt die Anzahl der Koordinatendimensionen für diese [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) zurück. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Gibt die topologische Dimension dieser [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) zurück. |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | r/w | Liefert den äußeren Ring. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Gibt den Typ der Geometrie zurück. |
| has_curve_geometry | bool | r | Gibt einen Wert zurück, der angibt, ob diese Geometrie Kurvengeometrie (nicht linear) enthält oder ist. |
| has_m | bool | r/w | Gibt einen Wert zurück, der angibt, ob diese Instanz eine M-Koordinate hat. |
| has_z | bool | r/w | Gibt einen Wert zurück, der angibt, ob diese Instanz eine Z-Koordinate hat. |
| interior_rings_count | int | r | Liefert die Anzahl der inneren Ringe. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz leer ist. |
| is_simple | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz aus Sicht von SFA einfach ist. |
| is_valid | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz gültig ist. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Gibt eine Instanz einer Null-Geometrie zurück. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Gibt das SpatialReferenceSystem dieser Instanz zurück.<br/>            Diese Eigenschaft kann <see langword="null" /> sein, wenn das SpatialReferenceSystem unbekannt ist.<br/>            Das Zuweisen eines neuen SpatialReferenceSystem führt keine Koordinatentransformation durch, nur die Referenz wird geändert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_interior_ring(ring)](#add_interior_ring_ring_1) | Fügt einen inneren Ring hinzu. |
| [as_binary()](#as_binary__2) | Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung. |
| [as_binary(variant)](#as_binary_variant_3) | Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_6) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_text()](#as_text__7) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [as_text(variant)](#as_text_variant_8) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [as_text(variant, format)](#as_text_variant_format_9) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [clone()](#clone__10) | Klont diese Instanz. |
| [covered_by(other)](#covered_by_other_11) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie überdeckt wird. |
| [covers(other)](#covers_other_12) | Bestimmt, ob diese Geometrie eine angegebene Geometrie überdeckt. |
| [crosses(other)](#crosses_other_13) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich kreuzen. |
| [difference(other)](#difference_other_14) | Subtrahiert eine angegebene Geometrie von dieser Geometrie. |
| [disjoint(other)](#disjoint_other_15) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie disjunkt ist. |
| [from_binary(wkb)](#from_binary_wkb_16) | Erstellt eine Geometrie aus ihrer Well-Known-Binary-Darstellung. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_17) | Erstellt eine Geometrie aus ihrer Well-Known-Binary-Darstellung. |
| [from_text(wkt)](#from_text_wkt_18) | Erstellt eine Geometrie aus ihrer Well-Known-Text-Darstellung. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_19) | Erstellt eine Geometrie aus ihrer Well-Known-Text-Darstellung. |
| [get_area()](#get_area__20) | Berechnet die Fläche dieser Geometrie. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_21) | Berechnet einen Pufferbereich um diese Geometrie. |
| [get_centroid()](#get_centroid__22) | Berechnet den Schwerpunkt dieser Geometrie. |
| [get_convex_hull()](#get_convex_hull__23) | Berechnet die konvexe Hülle dieser Geometrie. |
| [get_distance_to(other)](#get_distance_to_other_24) | Berechnet den minimalen Abstand zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [get_extent()](#get_extent__25) | Berechnet und gibt den begrenzenden Umfang dieser Geometrie zurück. |
| [get_interior_ring(index)](#get_interior_ring_index_26) | Liefert den inneren Ring anhand seines Index. |
| [get_length()](#get_length__27) | Berechnet die Länge dieser Geometrie. |
| [get_point_on_surface()](#get_point_on_surface__28) | Findet einen Punkt, der garantiert auf diesem Polygon liegt. |
| [intersection(other)](#intersection_other_29) | Erstellt eine Schnittmenge zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [intersects(extent)](#intersects_extent_30) | Bestimmt, ob diese Geometrie einen angegebenen Umfang schneidet. |
| [intersects(other)](#intersects_other_31) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich schneiden. |
| [overlaps(other)](#overlaps_other_32) | Bestimmt, ob diese Geometrie mit einer angegebenen Geometrie überlappt. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | Bestimmt, ob die DE-9IM-Schnittmatrix dieser Geometrie und einer angegebenen Geometrie dem bereitgestellten Muster entspricht. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__34) | Erhält Polygone, die als Linien dieser Geometrie dargestellt werden. |
| [round_m(digits)](#round_m_digits_35) | Rundet die M-Koordinate auf eine angegebene Anzahl von Nachkommastellen. |
| [round_xy(digits)](#round_xy_digits_36) | Rundet die X- und Y-Koordinaten auf eine angegebene Anzahl von Nachkommastellen. |
| [round_z(digits)](#round_z_digits_37) | Rundet die Z-Koordinate auf eine angegebene Anzahl von Nachkommastellen. |
| set_empty() | Macht diese [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) leer. |
| [spatially_contains(other)](#spatially_contains_other_38) | Bestimmt, ob diese Geometrie räumlich eine angegebene Geometrie enthält. |
| [spatially_equals(other)](#spatially_equals_other_39) | Bestimmt, ob diese Geometrie räumlich einer angegebenen Geometrie gleich ist. |
| [sym_difference(other)](#sym_difference_other_40) | Erstellt die symmetrische Differenz zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [to_editable()](#to_editable__41) | Erhält eine editierbare Kopie dieser Geometrie. |
| [to_linear_geometry()](#to_linear_geometry__42) | Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der Standard-<c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_43) | Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der angegebenen <c>tolerance</c>. |
| [to_svg(extent)](#to_svg_extent_44) | Übersetzt diese Geometrie in eine Svg-Darstellung. |
| [touches(other)](#touches_other_45) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich berühren. |
| [union(other)](#union_other_46) | Vereint diese Geometrie mit einer angegebenen Geometrie. |
| [union(other)](#union_other_47) | Vereint diese Geometrie mit einer angegebenen Geometrie. |
| [within(extent)](#within_extent_48) | Bestimmt, ob diese Geometrie innerhalb eines angegebenen Ausdehnungsbereichs liegt. |
| [within(other)](#within_other_49) | Bestimmt, ob diese Geometrie innerhalb einer angegebenen Geometrie liegt. |


### Constructor: Polygon() {#Polygon__1}


```
 Polygon() 
```

Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse.

### Constructor: Polygon(exterior_ring) {#Polygon_exterior_ring_2}


```
 Polygon(exterior_ring) 
```

Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | Der äußere Ring. |

### Constructor: Polygon(exterior_ring, interior_rings) {#Polygon_exterior_ring_interior_rings_3}


```
 Polygon(exterior_ring, interior_rings) 
```

Initialisiert eine neue Instanz der [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | Der äußere Ring. |
| interior_rings | System.Collections.Generic.IEnumerable<ILinearRing> | Die inneren Ringe. |

### Method: add_interior_ring(ring) {#add_interior_ring_ring_1}


```
 add_interior_ring(ring) 
```

Fügt einen inneren Ring hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | Der hinzuzufügende Ring. |

### Method: as_binary() {#as_binary__2}


```
 as_binary() 
```

Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Well-Known-Binary-Darstellung dieser Geometrie. |


### Method: as_binary(variant) {#as_binary_variant_3}


```
 as_binary(variant) 
```

Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Well-Known-Binary-Variante zur Verwendung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Well-Known-Binary-Darstellung dieser Geometrie. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exportiert diese Geometrie in eine Bilddarstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Ausgabebild. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breite der Karte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höhe der Karte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer zur Verwendung. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exportiert diese Geometrie in eine Bilddarstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output_path | string | Pfad zum Ausgabebild. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breite der Karte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höhe der Karte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer zur Verwendung. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_6}


```
 as_image(width, height, renderer, symbolizer) 
```

Exportiert diese Geometrie in eine Bilddarstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Breite der Karte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Höhe der Karte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer zur Verwendung. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ein Symbolisierer zur Verwendung beim Rendern. Wenn <see langword=\"null\" />, wird der Standardsymbolisierer verwendet. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Das Bild als Stream |


### Method: as_text() {#as_text__7}


```
 as_text() 
```

Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Well-Known-Text-Darstellung dieser Geometrie. |


### Method: as_text(variant) {#as_text_variant_8}


```
 as_text(variant) 
```

Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known-Text-Variante zur Verwendung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Well-Known-Text-Darstellung dieser Geometrie. |


### Method: as_text(variant, format) {#as_text_variant_format_9}


```
 as_text(variant, format) 
```

Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Well-Known-Text-Variante zur Verwendung. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Koordinatenformat für die Umwandlung in einen String. Siehe [NumericFormat](/psd/python-net/aspose.gis/numericformat/) für weitere Informationen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Well-Known-Text-Darstellung dieser Geometrie. |


### Method: clone() {#clone__10}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Die Kopie dieser Instanz |


### Method: covered_by(other) {#covered_by_other_11}


```
 covered_by(other) 
```

Bestimmt, ob diese Geometrie von einer angegebenen Geometrie überdeckt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie von einer anderen Geometrie \"räumlich bedeckt\" wird. <see langword=\"false\" /> sonst. |


### Method: covers(other) {#covers_other_12}


```
 covers(other) 
```

Bestimmt, ob diese Geometrie eine angegebene Geometrie überdeckt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich abdeckt\". <see langword=\"false\" /> sonst. |


### Method: crosses(other) {#crosses_other_13}


```
 crosses(other) 
```

Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich kreuzen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich kreuzt\". <see langword=\"false\" /> sonst. |


### Method: difference(other) {#difference_other_14}


```
 difference(other) 
```

Subtrahiert eine angegebene Geometrie von dieser Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie zum Subtrahieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die Differenz dieser Geometrie und eines Arguments darstellt. Die Ergebnisgeometrie enthält<br/>            Punktmenge, die in dieser Geometrie, aber nicht in einem Argument vorkommt. |


### Method: disjoint(other) {#disjoint_other_15}


```
 disjoint(other) 
```

Bestimmt, ob diese Geometrie von einer angegebenen Geometrie disjunkt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie von einer anderen Geometrie \"räumlich disjunkt\" ist. <see langword=\"false\" /> andernfalls. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_16}


```
 from_binary(wkb) 
```

Erstellt eine Geometrie aus ihrer Well-Known-Binary-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-Darstellung einer Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die durch das Argument dargestellt wird. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_17}


```
 from_binary(wkb, spatial_reference_system) 
```

Erstellt eine Geometrie aus ihrer Well-Known-Binary-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkb | byte | Well-Known Binary-Darstellung einer Geometrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem, das der Geometrie zugewiesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die durch das Argument dargestellt wird. |


### Method: from_text(wkt)  [static] {#from_text_wkt_18}


```
 from_text(wkt) 
```

Erstellt eine Geometrie aus ihrer Well-Known-Text-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkt | string | Well-Known Text-Darstellung einer Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die durch das Argument dargestellt wird. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_19}


```
 from_text(wkt, spatial_reference_system) 
```

Erstellt eine Geometrie aus ihrer Well-Known-Text-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkt | string | Well-Known Text-Darstellung einer Geometrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem, das der Geometrie zugewiesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die durch das Argument dargestellt wird. |


### Method: get_area() {#get_area__20}


```
 get_area() 
```

Berechnet die Fläche dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Die Fläche dieser Geometrie.<br/>            Summe der Flächen der Elemente dieser Geometrie, wenn diese Geometrie eine [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ist. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_21}


```
 get_buffer(distance, quadrant_segments) 
```

Berechnet einen Pufferbereich um diese Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| distance | double | Die Breite des Pufferbereichs (in Spatial-Reference-Einheiten). |
| quadrant_segments | int | Anzahl der Segmente, die zur Annäherung einer 90-Grad-Krümmung verwendet werden.<br/>            Je größer diese Zahl ist, desto besser wird die Annäherung von Kurven erzeugt.<br/>            Standardwert ist 30. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die alle Punkte darstellt, die innerhalb einer angegebenen Entfernung von<br/>            dieser Geometrie liegen.<br/>            Der Typ des Ergebnisses ist entweder [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) oder [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__22}


```
 get_centroid() 
```

Berechnet den Schwerpunkt dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Der Schwerpunkt dieser Geometrie. Wenn diese Geometrie leer ist, wird ein leerer Punkt zurückgegeben.<br/>            Der Schwerpunkt entspricht dem Schwerpunkt der geometrischen Objekte höchster Dimension in dieser Geometrie<br/>            (z. B. wenn sowohl Punkte als auch Linien in der Geometrie enthalten sind, tragen nur Linien zum Schwerpunkt bei). |


### Method: get_convex_hull() {#get_convex_hull__23}


```
 get_convex_hull() 
```

Berechnet die konvexe Hülle dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die konvexe Hülle dieser Geometrie darstellt.<br/>            Wenn diese Geometrie keine Punkte hat, ist das Ergebnis [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Wenn diese Geometrie nur einen Punkt hat, ist das Ergebnis dieser Punkt.<br/>            Wenn diese Geometrie nur zwei Punkte hat, ist das Ergebnis ein [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) mit den Punkten.<br/>            Wenn diese Geometrie drei oder mehr Punkte hat, ist das Ergebnis ein [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/), das eine konvexe<br/>            Hülle um alle Punkte der Geometrie darstellt. |


### Method: get_distance_to(other) {#get_distance_to_other_24}


```
 get_distance_to(other) 
```

Berechnet den minimalen Abstand zwischen dieser Geometrie und einer angegebenen Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, zu der die Entfernung ermittelt werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Wenn beide Geometrien nicht [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) sind – ein Abstand zwischen den nächsten Punkten der Geometrien.<br/>            Wenn mindestens eine Geometrie leer ist, wird -1 zurückgegeben. |


### Method: get_extent() {#get_extent__25}


```
 get_extent() 
```

Berechnet und gibt den begrenzenden Umfang dieser Geometrie zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein begrenzender Umfang dieser Geometrie. |


### Method: get_interior_ring(index) {#get_interior_ring_index_26}


```
 get_interior_ring(index) 
```

Liefert den inneren Ring anhand seines Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | Der innere Ring. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

Berechnet die Länge dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Die Länge dieser Geometrie.<br/>            Umfang, wenn dies ein [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) ist.<br/>            Summe der Längen der Elemente dieser Geometrie, wenn diese Geometrie eine [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ist. |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

Findet einen Punkt, der garantiert auf diesem Polygon liegt.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Ein Punkt auf diesem Polygon. Ein leerer Punkt, wenn dieses Polygon kein Inneres hat. |


### Method: intersection(other) {#intersection_other_29}


```
 intersection(other) 
```

Erstellt eine Schnittmenge zwischen dieser Geometrie und einer angegebenen Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, mit der die Schnittmenge berechnet werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die Schnittmenge dieser Geometrie und eines Arguments darstellt. Die Ergebnisgeometrie enthält<br/>            Punktmenge, die sowohl in dieser Geometrie als auch im Argument vorkommt. |


### Method: intersects(extent) {#intersects_extent_30}


```
 intersects(extent) 
```

Bestimmt, ob diese Geometrie einen angegebenen Umfang schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Der Umfang. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie den Umfang schneidet; <see langword=\"false\" /> sonst. |


### Method: intersects(other) {#intersects_other_31}


```
 intersects(other) 
```

Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich schneiden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich schneidet\". <see langword=\"false\" /> sonst. |


### Method: overlaps(other) {#overlaps_other_32}


```
 overlaps(other) 
```

Bestimmt, ob diese Geometrie mit einer angegebenen Geometrie überlappt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich überlappt\". <see langword=\"false\" /> sonst. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


```
 relate(other, intersection_pattern_matrix) 
```

Bestimmt, ob die DE-9IM-Schnittmatrix dieser Geometrie und einer angegebenen Geometrie dem bereitgestellten Muster entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |
| intersection_pattern_matrix | string | Ein Muster zum Abgleichen.<br/>            Dies sollte ein String mit einer Länge von 9 sein.<br/>            Jedes Zeichen des Strings stellt die erwartete Dimension einer Schnittstelle dar:<br/>            <ul><br/>            <li>Zeichen 0 – zwischen den Innenräumen der Geometrien.</li><br/>            <li>Zeichen 1 – zwischen dem Innenraum dieser Geometrie und der Grenze einer anderen Geometrie.</li><br/>            <li>Zeichen 2 – zwischen dem Innenraum dieser Geometrie und dem Äußeren einer anderen Geometrie.</li><br/>            <li>Zeichen 3 – zwischen der Grenze dieser Geometrie und dem Innenraum einer anderen Geometrie.</li><br/>            <li>Zeichen 4 – zwischen den Grenzen der Geometrien.</li><br/>            <li>Zeichen 5 – zwischen der Grenze dieser Geometrie und dem Äußeren einer anderen Geometrie.</li><br/>            <li>Zeichen 6 – zwischen dem Äußeren dieser Geometrie und dem Innenraum einer anderen Geometrie.</li><br/>            <li>Zeichen 7 – zwischen dem Äußeren dieser Geometrie und der Grenze einer anderen Geometrie.</li><br/>            <li>Zeichen 8 – zwischen den Äußeren der Geometrien.</li><br/>            </ul><br/>            Mögliche Werte jedes Zeichens sind:<br/>            <ul><br/>            <li>* – beliebiger Wert;</li><br/>            <li>F – keine Schnittstelle;</li><br/>            <li>T – irgendeine Schnittstelle;</li><br/>            <li>0 – Punkt‑Schnittstelle (z. B. gemeinsamer Punkt);</li><br/>            <li>1 – Linien‑Schnittstelle (z. B. gemeinsames Liniensegment);</li><br/>            <li>2 – Flächen‑Schnittstelle (z. B. gemeinsamer Teil eines Polygons);</li><br/>            </ul><br/>            Zum Beispiel bedeutet das Schnittmuster \"F0*******\", dass es keine Schnittstelle zwischen den Innenräumen der Geometrien geben darf<br/>            und die Schnittstelle zwischen den Grenzen der Geometrien ein Punkt sein muss.<br/>            Siehe die OpenGIS Simple Features Specification für weitere Details zum Muster der Schnittmatrix. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Schnittmatrix dem Muster entspricht; <see langword=\"false\" /> sonst. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__34}


```
 replace_polygons_by_lines() 
```

Erhält Polygone, die als Linien dieser Geometrie dargestellt werden.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die keine Polygon‑Geometrien enthält. Die folgenden Transformationen werden angewendet:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s werden linearisiert<br/> (umgewandelt in [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s werden zu [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s zusammengeführt</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_35}


```
 round_m(digits) 
```

Rundet die M-Koordinate auf eine angegebene Anzahl von Nachkommastellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Ziffern | int | Anzahl der Nachkommastellen. |

### Method: round_xy(digits) {#round_xy_digits_36}


```
 round_xy(digits) 
```

Rundet die X- und Y-Koordinaten auf eine angegebene Anzahl von Nachkommastellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Ziffern | int | Anzahl der Nachkommastellen. |

### Method: round_z(digits) {#round_z_digits_37}


```
 round_z(digits) 
```

Rundet die Z-Koordinate auf eine angegebene Anzahl von Nachkommastellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Ziffern | int | Anzahl der Nachkommastellen. |

### Method: spatially_contains(other) {#spatially_contains_other_38}


```
 spatially_contains(other) 
```

Bestimmt, ob diese Geometrie räumlich eine angegebene Geometrie enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich enthält\". <see langword=\"false\" /> sonst. |


### Method: spatially_equals(other) {#spatially_equals_other_39}


```
 spatially_equals(other) 
```

Bestimmt, ob diese Geometrie räumlich einer angegebenen Geometrie gleich ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie der angegebenen Geometrie \"räumlich entspricht\". <see langword=\"false\" /> sonst. |


### Method: sym_difference(other) {#sym_difference_other_40}


```
 sym_difference(other) 
```

Erstellt die symmetrische Differenz zwischen dieser Geometrie und einer angegebenen Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, mit der die symmetrische Differenz berechnet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die symmetrische Differenz dieser Geometrie und eines Arguments darstellt. Die Ergebnisgeometrie enthält<br/>            Punktmenge, die in einer der Geometrien, aber nicht in beiden vorhanden ist. |


### Method: to_editable() {#to_editable__41}


```
 to_editable() 
```

Erhält eine editierbare Kopie dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon) | Eine editierbare Kopie dieser Geometrie. |


### Method: to_linear_geometry() {#to_linear_geometry__42}


```
 to_linear_geometry() 
```

Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der Standard-<c>tolerance</c>.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Ein [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/), das diesem <c>ISurface</c> approximiert oder entspricht.<br/>            Dies entspricht <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float) mit<br/>            dem Standard-<c>tolerance</c>. Der Standardwert von <c>tolerance</c> hängt ab von [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            dieser Geometrie:<br/>            <ul><br/>            <li> Für projizierte SRS beträgt die Toleranz 0,001 Meter (in SRS‑Einheiten) </li><br/>            <li> Für geografische SRS beträgt die Toleranz <c>1e-5</c> Grad (in SRS‑Einheiten) </li><br/>            <li> Für unbekannte SRS beträgt die Toleranz <c>1e-5</c> </li><br/>            </ul><br/>            Weitere Details zu den angewandten Transformationen finden Sie in der Spezifikation von <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_43}


```
 to_linear_geometry(tolerance) 
```

Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der angegebenen <c>tolerance</c>.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Toleranz | double | Die zu verwendende <c>tolerance</c>. Das Ergebnis ist garantiert weniger als <c>tolerance</c> vom<br/>             gekrümmten Objekt entfernt, es sei denn, die zum Linearieren der Geometrie benötigte Punktzahl überschreitet das pro Quadrant‑Maximum,<br/>             das derzeit 10.000 Punkte beträgt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Ein [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/), das diesem <c>ISurface</c> approximiert oder entspricht:<br/>             <ul><br/>             Wenn dieses Objekt selbst ein [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ist, ist das Ergebnis diesem Objekt äquivalent<br/>             Wenn dieses Objekt kein [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ist, wird es linearisiert und ein [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) erstellt<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_44}


```
 to_svg(extent) 
```

Übersetzt diese Geometrie in eine Svg-Darstellung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Umfang für die Übersetzung dieser Geometrie nach SVG |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Die SVG-Darstellung. |


### Method: touches(other) {#touches_other_45}


```
 touches(other) 
```

Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich berühren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie eine andere Geometrie \"räumlich berührt\". <see langword=\"false\" /> sonst. |


### Method: union(other) {#union_other_46}


```
 union(other) 
```

Vereint diese Geometrie mit einer angegebenen Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, mit der vereinigt werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die Vereinigung dieser Geometrie und eines Arguments darstellt. Die Ergebnisgeometrie enthält<br/>            Punktmenge, die in dieser Geometrie oder in einem Argument vorhanden ist. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Vereint diese Geometrie mit einer angegebenen Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, mit der vereinigt werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die Vereinigung dieser Geometrie und eines Arguments darstellt. Die Ergebnisgeometrie enthält<br/>            Punktmenge, die in dieser Geometrie oder in einem Argument vorhanden ist. |


### Method: within(extent) {#within_extent_48}


```
 within(extent) 
```

Bestimmt, ob diese Geometrie innerhalb eines angegebenen Ausdehnungsbereichs liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Der Umfang. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie innerhalb des Umfangs liegt; <see langword=\"false\" /> sonst. |


### Method: within(other) {#within_other_49}


```
 within(other) 
```

Bestimmt, ob diese Geometrie innerhalb einer angegebenen Geometrie liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn diese Geometrie \"räumlich innerhalb\" einer anderen Geometrie liegt. <see langword=\"false\" /> sonst. |


