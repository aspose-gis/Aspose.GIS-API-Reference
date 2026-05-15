---
title: "ICurve Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.gis.geometries/icurve/
---

**Summary:** An interface for ICurve type [ICurve](/psd/python-net/aspose.gis.geometries/icurve/) is a sequence of points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.ICurve

**Inheritance:** IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Gibt die topologische Dimension dieses [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) zurück.<br/>            Wenn die Dimension unbekannt ist (z. B. für eine leere GEOMETRYCOLLECTION) wird [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) zurückgegeben. |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Gibt eine Kopie des Endpunkts der Kurve zurück. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Gibt den Typ der Geometrie zurück. |
| has_curve_geometry | bool | r | Gibt einen Wert zurück, der angibt, ob diese Geometrie Kurvengeometrie (nicht linear) enthält oder ist. |
| has_m | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz eine M-Koordinate hat. |
| has_z | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz eine Z-Koordinate hat. |
| is_closed | bool | r | Gibt einen Wert zurück, der angibt, ob eine Kurve geschlossen ist.<br/>            Eine Kurve ist geschlossen, wenn ihr Startpunkt dem Endpunkt entspricht. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz leer ist (repräsentiert die leere Punktmenge). |
| is_simple | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz aus Sicht von SFA einfach ist. |
| is_valid | bool | r | Gibt einen Wert zurück, der angibt, ob diese Instanz gültig ist. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Gibt das SpatialReferenceSystem dieser Instanz zurück.<br/>            Diese Eigenschaft kann <see langword=\"null\" /> sein, wenn das SpatialReferenceSystem unbekannt ist. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Gibt eine Kopie des Startpunkts der Kurve zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [as_binary()](#as_binary__1) | Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung. |
| [as_binary(variant)](#as_binary_variant_2) | Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Exportiert diese Geometrie in eine Bilddarstellung. |
| [as_text()](#as_text__6) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [as_text(variant)](#as_text_variant_7) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [as_text(variant, format)](#as_text_variant_format_8) | Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung. |
| [clone()](#clone__9) | Klont diese Instanz. |
| [covered_by(other)](#covered_by_other_10) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie überdeckt wird. |
| [covers(other)](#covers_other_11) | Bestimmt, ob diese Geometrie eine angegebene Geometrie überdeckt. |
| [crosses(other)](#crosses_other_12) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich kreuzen. |
| [difference(other)](#difference_other_13) | Subtrahiert eine angegebene Geometrie von dieser Geometrie. |
| [disjoint(other)](#disjoint_other_14) | Bestimmt, ob diese Geometrie von einer angegebenen Geometrie disjunkt ist. |
| [get_area()](#get_area__15) | Berechnet die Fläche dieser Geometrie. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | Berechnet einen Pufferbereich um diese Geometrie. |
| [get_centroid()](#get_centroid__17) | Berechnet den Schwerpunkt dieser Geometrie. |
| [get_convex_hull()](#get_convex_hull__18) | Berechnet die konvexe Hülle dieser Geometrie. |
| [get_distance_to(other)](#get_distance_to_other_19) | Berechnet den minimalen Abstand zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [get_extent()](#get_extent__20) | Berechnet und gibt den begrenzenden Umfang dieser Geometrie zurück. |
| [get_length()](#get_length__21) | Berechnet die Länge dieser Geometrie. |
| [intersection(other)](#intersection_other_22) | Erstellt eine Schnittmenge zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [intersects(extent)](#intersects_extent_23) | Bestimmt, ob diese Geometrie einen angegebenen Umfang schneidet. |
| [intersects(other)](#intersects_other_24) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich schneiden. |
| [overlaps(other)](#overlaps_other_25) | Bestimmt, ob diese Geometrie mit einer angegebenen Geometrie überlappt. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_26) | Bestimmt, ob die DE-9IM-Schnittmatrix dieser Geometrie und einer angegebenen Geometrie dem bereitgestellten Muster entspricht. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__27) | Erhält Polygone, die als Linien dieser Geometrie dargestellt werden. |
| [spatially_contains(other)](#spatially_contains_other_28) | Bestimmt, ob diese Geometrie räumlich eine angegebene Geometrie enthält. |
| [spatially_equals(other)](#spatially_equals_other_29) | Bestimmt, ob diese Geometrie räumlich einer angegebenen Geometrie gleich ist. |
| [sym_difference(other)](#sym_difference_other_30) | Erstellt die symmetrische Differenz zwischen dieser Geometrie und einer angegebenen Geometrie. |
| [to_editable()](#to_editable__31) | Erhält eine editierbare Kopie dieser Geometrie. |
| [to_linear_geometry()](#to_linear_geometry__32) | Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der Standard-<c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_33) | Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der angegebenen <c>tolerance</c>. |
| [touches(other)](#touches_other_34) | Bestimmt, ob diese Geometrie und eine angegebene Geometrie sich berühren. |
| [union(other)](#union_other_35) | Vereint diese Geometrie mit einer angegebenen Geometrie. |
| [union(other)](#union_other_36) | Vereint diese Geometrie mit einer angegebenen Geometrie. |
| [within(extent)](#within_extent_37) | Bestimmt, ob diese Geometrie innerhalb eines angegebenen Ausdehnungsbereichs liegt. |
| [within(other)](#within_other_38) | Bestimmt, ob diese Geometrie innerhalb einer angegebenen Geometrie liegt. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Übersetzt diese Geometrie in ihre Well-Known Binary-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Well-Known-Binary-Darstellung dieser Geometrie. |


### Method: as_binary(variant) {#as_binary_variant_2}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


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


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Übersetzt diese Geometrie in ihre Well-Known Text-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Well-Known-Text-Darstellung dieser Geometrie. |


### Method: as_text(variant) {#as_text_variant_7}


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


### Method: as_text(variant, format) {#as_text_variant_format_8}


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


### Method: clone() {#clone__9}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Die Kopie dieser Instanz |


### Method: covered_by(other) {#covered_by_other_10}


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


### Method: covers(other) {#covers_other_11}


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


### Method: crosses(other) {#crosses_other_12}


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


### Method: difference(other) {#difference_other_13}


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


### Method: disjoint(other) {#disjoint_other_14}


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


### Method: get_area() {#get_area__15}


```
 get_area() 
```

Berechnet die Fläche dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Die Fläche dieser Geometrie.<br/>            Summe der Flächen der Elemente dieser Geometrie, wenn diese Geometrie eine [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ist. |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


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


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

Berechnet den Schwerpunkt dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Der Schwerpunkt dieser Geometrie. Wenn diese Geometrie leer ist, wird ein leerer Punkt zurückgegeben.<br/>            Der Schwerpunkt entspricht dem Schwerpunkt der geometrischen Objekte höchster Dimension in dieser Geometrie<br/>            (z. B. wenn sowohl Punkte als auch Linien in der Geometrie enthalten sind, tragen nur Linien zum Schwerpunkt bei). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

Berechnet die konvexe Hülle dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die die konvexe Hülle dieser Geometrie darstellt.<br/>            Wenn diese Geometrie keine Punkte hat, ist das Ergebnis [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Wenn diese Geometrie nur einen Punkt hat, ist das Ergebnis dieser Punkt.<br/>            Wenn diese Geometrie nur zwei Punkte hat, ist das Ergebnis ein [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) mit den Punkten.<br/>            Wenn diese Geometrie drei oder mehr Punkte hat, ist das Ergebnis ein [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/), das eine konvexe<br/>            Hülle um alle Punkte der Geometrie darstellt. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


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


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

Berechnet und gibt den begrenzenden Umfang dieser Geometrie zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein begrenzender Umfang dieser Geometrie. |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

Berechnet die Länge dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Die Länge dieser Geometrie.<br/>            Umfang, wenn dies ein [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) ist.<br/>            Summe der Längen der Elemente dieser Geometrie, wenn diese Geometrie eine [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) ist. |


### Method: intersection(other) {#intersection_other_22}


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


### Method: intersects(extent) {#intersects_extent_23}


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


### Method: intersects(other) {#intersects_other_24}


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


### Method: overlaps(other) {#overlaps_other_25}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_26}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__27}


```
 replace_polygons_by_lines() 
```

Erhält Polygone, die als Linien dieser Geometrie dargestellt werden.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Eine Geometrie, die keine Polygon‑Geometrien enthält. Die folgenden Transformationen werden angewendet:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s werden linearisiert<br/> (umgewandelt in [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s werden zu [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s zusammengeführt</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_28}


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


### Method: spatially_equals(other) {#spatially_equals_other_29}


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


### Method: sym_difference(other) {#sym_difference_other_30}


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


### Method: to_editable() {#to_editable__31}


```
 to_editable() 
```

Erhält eine editierbare Kopie dieser Geometrie.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Curve](/psd/python-net/aspose.gis.geometries/curve) | Eine editierbare Kopie dieser Geometrie. |


### Method: to_linear_geometry() {#to_linear_geometry__32}


```
 to_linear_geometry() 
```

Erhält eine approximative oder äquivalente nicht gekrümmte Version dieser Geometrie unter Verwendung der Standard-<c>tolerance</c>.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Ein [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) das approximiert oder gleichwertig zu dieser Kurve ist.<br/>            Dies ist das Äquivalent zu <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) mit<br/>            standardmäßig <c>tolerance</c>. Der Standardwert von <c>tolerance</c> ist abhängig von [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            dieser Geometrie:<br/>            <ul><br/>            <li> Für projizierte SRS beträgt die Toleranz 0,001 Meter (in SRS-Einheiten) </li><br/>            <li> Für geografische SRS beträgt die Toleranz <c>1e-5</c> Grad (in SRS-Einheiten) </li><br/>            <li> Für unbekannte SRS beträgt die Toleranz <c>1e-5</c> </li><br/>            </ul><br/>            Weitere Details zu den angewendeten Transformationen finden Sie in der Spezifikation von <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_33}


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
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Ein [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) das dieser Kurve approximiert oder äquivalent ist:<br/>             <ul><br/>             Wenn dieses Objekt selbst ein [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) ist, ist das Ergebnis äquivalent zu diesem Objekt<br/>             Wenn dieses Objekt ein [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) ist, ist das Ergebnis die mit dem angegebenen <paramref name=\"tolerance\" /> linearisierte Kreislinie<br/>             Wenn dieses Objekt ein [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) ist – werden alle Kurven daraus linearisiert und dann zu einem [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) zusammengeführt<br/>            </ul> |


### Method: touches(other) {#touches_other_34}


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


### Method: union(other) {#union_other_35}


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


### Method: union(other) {#union_other_36}


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


### Method: within(extent) {#within_extent_37}


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


### Method: within(other) {#within_other_38}


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


