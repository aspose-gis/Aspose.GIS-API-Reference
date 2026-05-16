---
title: "MultiPoint Classe"
type: docs
weight: 270
url: /it/python-net/aspose.gis.geometries/multipoint/
---

**Summary:** A [MultiPoint](/psd/python-net/aspose.gis.geometries/multipoint/) is a one-dimensional [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)<br/>            whose elements are [Point](/psd/python-net/aspose.gis.geometries/point/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.MultiPoint

**Inheritance:** IGeometry, IGeometryCollection, IMultiPoint, GeometryCollection

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [MultiPoint()](#MultiPoint__1) | Inizializza una nuova istanza della classe [MultiPoint](/psd/python-net/aspose.gis.geometries/multipoint/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Restituisce il numero di dimensioni coordinate per questo [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| conteggio | int | r | Restituisce il numero di geometrie in questa collezione. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Restituisce la dimensione topologica di questo [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Restituisce il tipo della geometria. |
| has_curve_geometry | bool | r | Restituisce un valore che indica se questa geometria è o contiene geometria curva (non lineare). |
| has_m | bool | r/w | Restituisce un valore che indica se questa istanza ha la coordinata M. |
| has_z | bool | r/w | Restituisce un valore che indica se questa istanza ha la coordinata Z. |
| is_empty | bool | r | Restituisce un valore che indica se questa istanza è vuota. |
| is_simple | bool | r | Restituisce un valore che indica se questa istanza è semplice dal punto di vista SFA. |
| is_valid | bool | r | Restituisce un valore che indica se questa istanza è valida. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Restituisce un'istanza di geometria nulla. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Restituisce lo SpatialReferenceSystem di questa istanza.<br/>            Questa proprietà può essere <see langword=\"null\" />, se lo SpatialReferenceSystem è sconosciuto.<br/>            L'assegnazione di un nuovo SpatialReferenceSystem non eseguirà alcuna trasformazione delle coordinate, cambierà solo il riferimento. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(geometry)](#add_geometry_1) | Aggiunge la geometria specificata alla collezione. |
| [add_range(geometries)](#add_range_geometries_2) | Aggiunge le geometrie specificate alla collezione. |
| [as_binary()](#as_binary__3) | Traduce questa geometria nella sua rappresentazione Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_4) | Traduce questa geometria nella sua rappresentazione Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Esporta questa geometria in una rappresentazione immagine. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_6) | Esporta questa geometria in una rappresentazione immagine. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_7) | Esporta questa geometria in una rappresentazione immagine. |
| [as_text()](#as_text__8) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [as_text(variant)](#as_text_variant_9) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_10) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [clone()](#clone__11) | Clona questa istanza. |
| [covered_by(other)](#covered_by_other_12) | Determina se questa geometria è coperta da una geometria specificata. |
| [covers(other)](#covers_other_13) | Determina se questa geometria copre una geometria specificata. |
| [crosses(other)](#crosses_other_14) | Determina se questa geometria e una geometria specificata si incrociano. |
| [difference(other)](#difference_other_15) | Sottrae una geometria specificata da questa geometria. |
| [disjoint(other)](#disjoint_other_16) | Determina se questa geometria è disgiunta da una geometria specificata. |
| [from_binary(wkb)](#from_binary_wkb_17) | Crea una geometria dalla sua rappresentazione Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_18) | Crea una geometria dalla sua rappresentazione Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_19) | Crea una geometria dalla sua rappresentazione Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_20) | Crea una geometria dalla sua rappresentazione Well-Known Text. |
| [get_area()](#get_area__21) | Calcola l'area di questa geometria. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_22) | Calcola una zona di buffer attorno a questa geometria. |
| [get_centroid()](#get_centroid__23) | Calcola il centroide di questa geometria. |
| [get_convex_hull()](#get_convex_hull__24) | Calcola l'involucro convesso di questa geometria. |
| [get_distance_to(other)](#get_distance_to_other_25) | Calcola la distanza minima tra questa geometria e una geometria specificata. |
| [get_extent()](#get_extent__26) | Calcola e restituisce l'estensione di delimitazione di questa geometria. |
| [get_length()](#get_length__27) | Calcola la lunghezza di questa geometria. |
| [get_point_on_surface()](#get_point_on_surface__28) | Trova un punto che è garantito essere su una delle superfici in questa collezione. |
| [intersection(other)](#intersection_other_29) | Costruisce un'intersezione tra questa geometria e una geometria specificata. |
| [intersects(extent)](#intersects_extent_30) | Determina se questa geometria interseca un'estensione specificata. |
| [intersects(other)](#intersects_other_31) | Determina se questa geometria e una geometria specificata si intersecano. |
| [overlaps(other)](#overlaps_other_32) | Determina se questa geometria si sovrappone a una geometria specificata. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | Determina se la matrice di intersezione DE-9IM di questa geometria e una geometria specificata corrisponde al modello fornito. |
| [remove_at(index)](#remove_at_index_34) | Rimuove la geometria specificata dalla collezione. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | Ottiene i poligoni rappresentati come linee di questa geometria. |
| [round_m(digits)](#round_m_digits_36) | Arrotonda la coordinata M a un numero specificato di cifre frazionarie. |
| [round_xy(digits)](#round_xy_digits_37) | Arrotonda le coordinate X e Y a un numero specificato di cifre frazionarie. |
| [round_z(digits)](#round_z_digits_38) | Arrotonda la coordinata Z a un numero specificato di cifre frazionarie. |
| set_empty() | Rende vuota questa [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| [spatially_contains(other)](#spatially_contains_other_39) | Determina se questa geometria contiene spazialmente una geometria specificata. |
| [spatially_equals(other)](#spatially_equals_other_40) | Determina se questa geometria è spazialmente uguale a una geometria specificata. |
| [sym_difference(other)](#sym_difference_other_41) | Costruisce una differenza simmetrica tra questa geometria e una geometria specificata. |
| [to_editable()](#to_editable__42) | Ottiene una copia modificabile di questa geometria. |
| [to_linear_geometry()](#to_linear_geometry__43) | Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> predefinita. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> specificata. |
| [to_svg(extent)](#to_svg_extent_45) | Traduce questa geometria nella rappresentazione Svg. |
| [touches(other)](#touches_other_46) | Determina se questa geometria e una geometria specificata si toccano. |
| [union(other)](#union_other_47) | Unisce questa geometria e una geometria specificata. |
| [union(other)](#union_other_48) | Unisce questa geometria e una geometria specificata. |
| [within(extent)](#within_extent_49) | Determina se questa geometria è all'interno di un'estensione specificata. |
| [within(other)](#within_other_50) | Determina se questa geometria è all'interno di una geometria specificata. |


### Constructor: MultiPoint() {#MultiPoint__1}


```
 MultiPoint() 
```

Inizializza una nuova istanza della classe [MultiPoint](/psd/python-net/aspose.gis.geometries/multipoint/).

### Method: add(geometry) {#add_geometry_1}


```
 add(geometry) 
```

Aggiunge la geometria specificata alla collezione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | La geometria da aggiungere. |

### Method: add_range(geometries) {#add_range_geometries_2}


```
 add_range(geometries) 
```

Aggiunge le geometrie specificate alla collezione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometrie | System.Collections.Generic.IEnumerable<IGeometry> | Le geometrie da aggiungere. |

### Method: as_binary() {#as_binary__3}


```
 as_binary() 
```

Traduce questa geometria nella sua rappresentazione Well-Known Binary.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Rappresentazione Well-Known Binary di questa geometria. |


### Method: as_binary(variant) {#as_binary_variant_4}


```
 as_binary(variant) 
```

Traduce questa geometria nella sua rappresentazione Well-Known Binary.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Variante Well-Known Binary da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Rappresentazione Well-Known Binary di questa geometria. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Esporta questa geometria in una rappresentazione immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso dell'immagine di output. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Larghezza della mappa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altezza della mappa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer da utilizzare. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_6}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Esporta questa geometria in una rappresentazione immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| output_path | string | Percorso dell'immagine di output. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Larghezza della mappa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altezza della mappa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer da utilizzare. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_7}


```
 as_image(width, height, renderer, symbolizer) 
```

Esporta questa geometria in una rappresentazione immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Larghezza della mappa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altezza della mappa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer da utilizzare. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizzatore da utilizzare per il rendering. Se <see langword=\"null\" />, viene utilizzato il simbolizzatore predefinito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | L'immagine come stream |


### Method: as_text() {#as_text__8}


```
 as_text() 
```

Traduce questa geometria nella sua rappresentazione Well-Known Text.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Rappresentazione Well-Known Text di questa geometria. |


### Method: as_text(variant) {#as_text_variant_9}


```
 as_text(variant) 
```

Traduce questa geometria nella sua rappresentazione Well-Known Text.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Rappresentazione Well-Known Text di questa geometria. |


### Method: as_text(variant, format) {#as_text_variant_format_10}


```
 as_text(variant, format) 
```

Traduce questa geometria nella sua rappresentazione Well-Known Text.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text da utilizzare. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Formato delle coordinate per la conversione in stringa. Vedi il [NumericFormat](/psd/python-net/aspose.gis/numericformat/) per ottenerlo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Rappresentazione Well-Known Text di questa geometria. |


### Method: clone() {#clone__11}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Il clone di questa istanza |


### Method: covered_by(other) {#covered_by_other_12}


```
 covered_by(other) 
```

Determina se questa geometria è coperta da una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se questa geometria è \"spatially covered by\" un'altra geometria. <see langword=\"false\" /> altrimenti. |


### Method: covers(other) {#covers_other_13}


```
 covers(other) 
```

Determina se questa geometria copre una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se questa geometria è \"spatially covers\" un'altra geometria. <see langword=\"false\" /> altrimenti. |


### Method: crosses(other) {#crosses_other_14}


```
 crosses(other) 
```

Determina se questa geometria e una geometria specificata si incrociano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se questa geometria è \"spatially crosses\" un'altra geometria. <see langword=\"false\" /> altrimenti. |


### Method: difference(other) {#difference_other_15}


```
 difference(other) 
```

Sottrae una geometria specificata da questa geometria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria da sottrarre. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta la differenza tra questa geometria e un argomento. La geometria risultante contiene<br/>            l'insieme di punti presenti in questa geometria ma non presenti in un argomento. |


### Method: disjoint(other) {#disjoint_other_16}


```
 disjoint(other) 
```

Determina se questa geometria è disgiunta da una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se questa geometria è \"spazialmente disgiunta\" da un'altra geometria. <see langword=\"false\" /> altrimenti. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_17}


```
 from_binary(wkb) 
```

Crea una geometria dalla sua rappresentazione Well-Known Binary.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkb | byte | Rappresentazione Well-Known Binary di una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria rappresentata dall'argomento. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_18}


```
 from_binary(wkb, spatial_reference_system) 
```

Crea una geometria dalla sua rappresentazione Well-Known Binary.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkb | byte | Rappresentazione Well-Known Binary di una geometria. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale da assegnare alla geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria rappresentata dall'argomento. |


### Method: from_text(wkt)  [static] {#from_text_wkt_19}


```
 from_text(wkt) 
```

Crea una geometria dalla sua rappresentazione Well-Known Text.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkt | string | Rappresentazione Well-Known Text di una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria rappresentata dall'argomento. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_20}


```
 from_text(wkt, spatial_reference_system) 
```

Crea una geometria dalla sua rappresentazione Well-Known Text.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkt | string | Rappresentazione Well-Known Text di una geometria. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale da assegnare alla geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria rappresentata dall'argomento. |


### Method: get_area() {#get_area__21}


```
 get_area() 
```

Calcola l'area di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | L'area di questa geometria.<br/>            Somma delle aree degli elementi di questa geometria se questa geometria è una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_22}


```
 get_buffer(distance, quadrant_segments) 
```

Calcola una zona di buffer attorno a questa geometria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| distanza | double | La larghezza della zona di buffer (in unità di Riferimento Spaziale). |
| quadrant_segments | int | Numero di segmenti usati per approssimare una curvatura di 90 gradi.<br/>            Più grande è questo numero, migliore è l'approssimazione delle curve.<br/>            Il valore predefinito è 30. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta tutti i punti che si trovano entro una distanza specificata da<br/>            questa geometria.<br/>            Il tipo di risultato è o [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) o [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__23}


```
 get_centroid() 
```

Calcola il centroide di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Il centroide di questa geometria. Se questa geometria è vuota viene restituito un punto vuoto.<br/>            Il centroide è uguale al centroide delle geometrie di dimensione più alta in questa geometria<br/>            (ad esempio, se nella geometria sono contenuti sia punti sia linee, solo le linee contribuiscono al centroide). |


### Method: get_convex_hull() {#get_convex_hull__24}


```
 get_convex_hull() 
```

Calcola l'involucro convesso di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta l'involucro convesso di questa geometria.<br/>            Se questa geometria non ha punti, il risultato è [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Se questa geometria ha un solo punto, il risultato è quel punto.<br/>            Se questa geometria ha solo due punti, il risultato è un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) con i punti.<br/>            Se questa geometria ha tre o più punti, il risultato è un [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) che rappresenta un involucro convesso<br/>            attorno a tutti i punti delle geometrie. |


### Method: get_distance_to(other) {#get_distance_to_other_25}


```
 get_distance_to(other) 
```

Calcola la distanza minima tra questa geometria e una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria verso cui trovare la distanza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Se entrambe le geometrie non sono [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - una distanza tra i punti più vicini delle geometrie.<br/>            Se almeno una geometria è vuota viene restituito -1. |


### Method: get_extent() {#get_extent__26}


```
 get_extent() 
```

Calcola e restituisce l'estensione di delimitazione di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione di delimitazione di questa geometria. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

Calcola la lunghezza di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | La lunghezza di questa geometria.<br/>            Perimetro se questa è un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Somma delle lunghezze degli elementi di questa geometria se questa geometria è una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

Trova un punto che è garantito essere su una delle superfici in questa collezione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Un punto su una delle superfici. Un punto vuoto se questa collezione non contiene superfici o tutte le superfici sono vuote. |


### Method: intersection(other) {#intersection_other_29}


```
 intersection(other) 
```

Costruisce un'intersezione tra questa geometria e una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria con cui calcolare l'intersezione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta l'intersezione di questa geometria e un argomento. La geometria risultante contiene<br/>            l'insieme di punti presenti sia in questa geometria sia nell'argomento. |


### Method: intersects(extent) {#intersects_extent_30}


```
 intersects(extent) 
```

Determina se questa geometria interseca un'estensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | L'estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria interseca l'estensione; <see langword="false" /> altrimenti. |


### Method: intersects(other) {#intersects_other_31}


```
 intersects(other) 
```

Determina se questa geometria e una geometria specificata si intersecano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria "interseca spazialmente" un'altra geometria. <see langword="false" /> altrimenti. |


### Method: overlaps(other) {#overlaps_other_32}


```
 overlaps(other) 
```

Determina se questa geometria si sovrappone a una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria "si sovrappone spazialmente" a un'altra geometria. <see langword="false" /> altrimenti. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


```
 relate(other, intersection_pattern_matrix) 
```

Determina se la matrice di intersezione DE-9IM di questa geometria e una geometria specificata corrisponde al modello fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |
| intersection_pattern_matrix | string | Un modello con cui confrontare.<br/>            Questa dovrebbe essere una stringa di lunghezza pari a 9.<br/>            Ogni carattere della stringa rappresenta la dimensione prevista di un'intersezione:<br/>            <ul><br/>            <li>carattere 0 - tra gli interni delle geometrie.</li><br/>            <li>carattere 1 - tra l'interno di questa geometria e il contorno di un'altra geometria.</li><br/>            <li>carattere 2 - tra l'interno di questa geometria e l'esterno di un'altra geometria.</li><br/>            <li>carattere 3 - tra il contorno di questa geometria e l'interno di un'altra geometria.</li><br/>            <li>carattere 4 - tra i contorni delle geometrie.</li><br/>            <li>carattere 5 - tra il contorno di questa geometria e l'esterno di un'altra geometria.</li><br/>            <li>carattere 6 - tra l'esterno di questa geometria e l'interno di un'altra geometria.</li><br/>            <li>carattere 7 - tra l'esterno di questa geometria e il contorno di un'altra geometria.</li><br/>            <li>carattere 8 - tra gli esterni delle geometrie.</li><br/>            </ul><br/>            Possibili valori di ciascun carattere sono:<br/>            <ul><br/>            <li>* - qualsiasi valore;</li><br/>            <li>F - nessuna intersezione;</li><br/>            <li>T - qualsiasi intersezione;</li><br/>            <li>0 - intersezione puntuale (es. punto condiviso);</li><br/>            <li>1 - intersezione lineare (es. segmento di linea condiviso);</li><br/>            <li>2 - intersezione di area (es. parte di poligono condivisa);</li><br/>            </ul><br/>            Ad esempio, un modello di intersezione "F0*******" indica che non dovrebbe esserci intersezione tra gli interni delle geometrie e che l'intersezione tra i contorni delle geometrie deve essere un punto.<br/>            Vedi la Specifica OpenGIS Simple Features per ulteriori dettagli sul modello della matrice di intersezione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa matrice di intersezione corrisponde al modello; <see langword="false" /> altrimenti. |


### Method: remove_at(index) {#remove_at_index_34}


```
 remove_at(index) 
```

Rimuove la geometria specificata dalla collezione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice della geometria da rimuovere. |

### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

Ottiene i poligoni rappresentati come linee di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | Una geometria che non contiene geometrie poligonali. Vengono applicate le seguenti trasformazioni:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono linearizzate<br/>            (trasformate in [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono unite in [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

Arrotonda la coordinata M a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

Arrotonda le coordinate X e Y a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Arrotonda la coordinata Z a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

Determina se questa geometria contiene spazialmente una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria "contiene spazialmente" un'altra geometria. <see langword="false" /> altrimenti. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

Determina se questa geometria è spazialmente uguale a una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria "è spazialmente uguale" alla geometria specificata. <see langword="false" /> altrimenti. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

Costruisce una differenza simmetrica tra questa geometria e una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria con cui calcolare la differenza simmetrica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta la differenza simmetrica tra questa geometria e un argomento. La geometria risultante contiene<br/>            l'insieme di punti presente in una delle geometrie ma non in entrambe. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

Ottiene una copia modificabile di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [MultiPoint](/psd/python-net/aspose.gis.geometries/multipoint) | Una copia modificabile di questa geometria. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> predefinita.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | Una geometria che non ha geometrie curve. Questo è l'equivalente di <DOM Element: class at 0x2a1791cc040>.IGeometryCollection.to_linear_geometry()(float) con<br/> la <c>tolerance</c> predefinita. Il valore predefinito della <c>tolerance</c> dipende da [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) di questa geometria:<br/> <ul><br/> <li> Per SRS proiettato la tolleranza è 0.001 metri (nelle unità SRS) </li><br/> <li> Per SRS geografico la tolleranza è <c>1e-5</c> gradi (nelle unità SRS) </li><br/> <li> Per SRS sconosciuto la tolleranza è <c>1e-5</c> </li><br/> </ul><br/> Per ulteriori dettagli su quali trasformazioni vengono applicate, fare riferimento alla specifica <DOM Element: class at 0x2a1791cc040>.IGeometryCollection.to_linear_geometry()(float) . |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tolleranza | double | La <c>tolerance</c> da usare. Il risultato è garantito essere inferiore a <c>tolerance</c> dalla<br/> geometria curva. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | Una geometria che non ha geometrie curve. Vengono applicate le seguenti trasformazioni:<br/> <ul><br/> <li> I [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono linearizzati<br/> (trasformati in [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) con la <paramref name="tolerance" /> specificata) </li><br/> <li> I [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono uniti in <c>LineString</c> </li><br/> <li> I [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono trasformati in [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/> <li> I [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono trasformati in [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/> <li> I [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono trasformati in [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/> </ul><br/> Di conseguenza, [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) della geometria di output è <see langword="false" />. |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

Traduce questa geometria nella rappresentazione Svg.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Estensione per la traduzione di questa geometria in Svg |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | La rappresentazione Svg. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

Determina se questa geometria e una geometria specificata si toccano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria "tocca spazialmente" un'altra geometria. <see langword="false" /> altrimenti. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Unisce questa geometria e una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria con cui unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta l'unione di questa geometria e di un argomento. La geometria risultante contiene<br/>            l'insieme di punti presente in questa geometria o in un argomento. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

Unisce questa geometria e una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria con cui unire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta l'unione di questa geometria e di un argomento. La geometria risultante contiene<br/>            l'insieme di punti presente in questa geometria o in un argomento. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

Determina se questa geometria è all'interno di un'estensione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | L'estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria è all'interno dell'estensione; <see langword="false" /> altrimenti. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

Determina se questa geometria è all'interno di una geometria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se questa geometria è "spazialmente all'interno" di un'altra geometria. <see langword="false" /> altrimenti. |


