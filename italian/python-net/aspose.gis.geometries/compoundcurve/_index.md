---
title: "CompoundCurve Classe"
type: docs
weight: 20
url: /it/python-net/aspose.gis.geometries/compoundcurve/
---

**Summary:** A curve that represents a sequence of contiguous curves such that adjacent curves are joined at their end points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.CompoundCurve

**Inheritance:** IGeometry, ICurve, ICompoundCurve, Curve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [CompoundCurve()](#CompoundCurve__1) | Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [CompoundCurve(curves)](#CompoundCurve_curves_2) | Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [CompoundCurve(other)](#CompoundCurve_other_3) | Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Restituisce il numero di dimensioni coordinate per questo [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| count | int | r | Restituisce il numero di curve nella [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Restituisce la dimensione topologica di questo [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Restituisce una copia del punto finale della curva. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Restituisce il tipo della geometria. |
| has_curve_geometry | bool | r | Restituisce un valore che indica se questa geometria è o contiene geometria curva (non lineare). |
| has_m | bool | r/w | Restituisce un valore che indica se questa istanza ha la coordinata M. |
| has_z | bool | r/w | Restituisce un valore che indica se questa istanza ha la coordinata Z. |
| is_closed | bool | r | Ottiene un valore che indica se una curva è chiusa. <br/>            Una curva è chiusa se il suo punto iniziale è uguale al punto finale. |
| is_empty | bool | r | Restituisce un valore che indica se questa istanza è vuota. |
| is_simple | bool | r | Restituisce un valore che indica se questa istanza è semplice dal punto di vista SFA. |
| is_valid | bool | r | Restituisce un valore che indica se questa istanza è valida. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Restituisce un'istanza di geometria nulla. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Ottiene il SpatialReferenceSystem di questa istanza.<br/>            Questa proprietà può essere <see langword=\"null\" />, se il SpatialReferenceSystem non è impostato.<br/>            Assegnare un nuovo SpatialReferenceSystem non eseguirà alcuna trasformazione delle coordinate, cambierà solo il riferimento. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Restituisce una copia del punto di partenza della curva. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_curve(curve)](#add_curve_curve_1) | Aggiunge una curva alla fine di questo [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [as_binary()](#as_binary__2) | Traduce questa geometria nella sua rappresentazione Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_3) | Traduce questa geometria nella sua rappresentazione Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Esporta questa geometria in una rappresentazione immagine. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Esporta questa geometria in una rappresentazione immagine. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_6) | Esporta questa geometria in una rappresentazione immagine. |
| [as_text()](#as_text__7) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [as_text(variant)](#as_text_variant_8) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_9) | Traduce questa geometria nella sua rappresentazione Well-Known Text. |
| [clone()](#clone__10) | Clona questa istanza. |
| [covered_by(other)](#covered_by_other_11) | Determina se questa geometria è coperta da una geometria specificata. |
| [covers(other)](#covers_other_12) | Determina se questa geometria copre una geometria specificata. |
| [crosses(other)](#crosses_other_13) | Determina se questa geometria e una geometria specificata si incrociano. |
| [difference(other)](#difference_other_14) | Sottrae una geometria specificata da questa geometria. |
| [disjoint(other)](#disjoint_other_15) | Determina se questa geometria è disgiunta da una geometria specificata. |
| [from_binary(wkb)](#from_binary_wkb_16) | Crea una geometria dalla sua rappresentazione Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_17) | Crea una geometria dalla sua rappresentazione Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_18) | Crea una geometria dalla sua rappresentazione Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_19) | Crea una geometria dalla sua rappresentazione Well-Known Text. |
| [get_area()](#get_area__20) | Calcola l'area di questa geometria. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_21) | Calcola una zona di buffer attorno a questa geometria. |
| [get_centroid()](#get_centroid__22) | Calcola il centroide di questa geometria. |
| [get_convex_hull()](#get_convex_hull__23) | Calcola l'involucro convesso di questa geometria. |
| [get_distance_to(other)](#get_distance_to_other_24) | Calcola la distanza minima tra questa geometria e una geometria specificata. |
| [get_extent()](#get_extent__25) | Calcola e restituisce l'estensione di delimitazione di questa geometria. |
| [get_length()](#get_length__26) | Calcola la lunghezza di questa geometria. |
| [intersection(other)](#intersection_other_27) | Costruisce un'intersezione tra questa geometria e una geometria specificata. |
| [intersects(extent)](#intersects_extent_28) | Determina se questa geometria interseca un'estensione specificata. |
| [intersects(other)](#intersects_other_29) | Determina se questa geometria e una geometria specificata si intersecano. |
| [overlaps(other)](#overlaps_other_30) | Determina se questa geometria si sovrappone a una geometria specificata. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_31) | Determina se la matrice di intersezione DE-9IM di questa geometria e una geometria specificata corrisponde al modello fornito. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__32) | Ottiene i poligoni rappresentati come linee di questa geometria. |
| reverse() | Inverte questo [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). Cioè - inverte l'ordine delle curve e ogni curva all'interno di questo compound curve. |
| [round_m(digits)](#round_m_digits_33) | Arrotonda la coordinata M a un numero specificato di cifre frazionarie. |
| [round_xy(digits)](#round_xy_digits_34) | Arrotonda le coordinate X e Y a un numero specificato di cifre frazionarie. |
| [round_z(digits)](#round_z_digits_35) | Arrotonda la coordinata Z a un numero specificato di cifre frazionarie. |
| set_empty() | Rende vuota questa [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| [spatially_contains(other)](#spatially_contains_other_36) | Determina se questa geometria contiene spazialmente una geometria specificata. |
| [spatially_equals(other)](#spatially_equals_other_37) | Determina se questa geometria è spazialmente uguale a una geometria specificata. |
| [sym_difference(other)](#sym_difference_other_38) | Costruisce una differenza simmetrica tra questa geometria e una geometria specificata. |
| [to_editable()](#to_editable__39) | Ottiene una copia modificabile di questa geometria. |
| [to_linear_geometry()](#to_linear_geometry__40) | Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> predefinita. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_41) | Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> specificata. |
| [to_svg(extent)](#to_svg_extent_42) | Traduce questa geometria nella rappresentazione Svg. |
| [touches(other)](#touches_other_43) | Determina se questa geometria e una geometria specificata si toccano. |
| [union(other)](#union_other_44) | Unisce questa geometria e una geometria specificata. |
| [union(other)](#union_other_45) | Unisce questa geometria e una geometria specificata. |
| [within(extent)](#within_extent_46) | Determina se questa geometria è all'interno di un'estensione specificata. |
| [within(other)](#within_other_47) | Determina se questa geometria è all'interno di una geometria specificata. |


### Constructor: CompoundCurve() {#CompoundCurve__1}


```
 CompoundCurve() 
```

Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

### Constructor: CompoundCurve(curves) {#CompoundCurve_curves_2}


```
 CompoundCurve(curves) 
```

Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| curve | System.Collections.Generic.IEnumerable<ICurve> | La collezione di curve. |

### Constructor: CompoundCurve(other) {#CompoundCurve_other_3}


```
 CompoundCurve(other) 
```

Inizializza una nuova istanza della classe [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve) | L'altra linea da cui copiare i dati. |

### Method: add_curve(curve) {#add_curve_curve_1}


```
 add_curve(curve) 
```

Aggiunge una curva alla fine di questo [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| curve | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | Curva da aggiungere. |

### Method: as_binary() {#as_binary__2}


```
 as_binary() 
```

Traduce questa geometria nella sua rappresentazione Well-Known Binary.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Rappresentazione Well-Known Binary di questa geometria. |


### Method: as_binary(variant) {#as_binary_variant_3}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_6}


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


### Method: as_text() {#as_text__7}


```
 as_text() 
```

Traduce questa geometria nella sua rappresentazione Well-Known Text.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Rappresentazione Well-Known Text di questa geometria. |


### Method: as_text(variant) {#as_text_variant_8}


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


### Method: as_text(variant, format) {#as_text_variant_format_9}


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


### Method: clone() {#clone__10}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Il clone di questa istanza |


### Method: covered_by(other) {#covered_by_other_11}


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


### Method: covers(other) {#covers_other_12}


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


### Method: crosses(other) {#crosses_other_13}


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


### Method: difference(other) {#difference_other_14}


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


### Method: disjoint(other) {#disjoint_other_15}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_16}


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


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_17}


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


### Method: from_text(wkt)  [static] {#from_text_wkt_18}


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


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_19}


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


### Method: get_area() {#get_area__20}


```
 get_area() 
```

Calcola l'area di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | L'area di questa geometria.<br/>            Somma delle aree degli elementi di questa geometria se questa geometria è una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_21}


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


### Method: get_centroid() {#get_centroid__22}


```
 get_centroid() 
```

Calcola il centroide di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Il centroide di questa geometria. Se questa geometria è vuota viene restituito un punto vuoto.<br/>            Il centroide è uguale al centroide delle geometrie di dimensione più alta in questa geometria<br/>            (ad esempio, se nella geometria sono contenuti sia punti sia linee, solo le linee contribuiscono al centroide). |


### Method: get_convex_hull() {#get_convex_hull__23}


```
 get_convex_hull() 
```

Calcola l'involucro convesso di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che rappresenta l'involucro convesso di questa geometria.<br/>            Se questa geometria non ha punti, il risultato è [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Se questa geometria ha un solo punto, il risultato è quel punto.<br/>            Se questa geometria ha solo due punti, il risultato è un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) con i punti.<br/>            Se questa geometria ha tre o più punti, il risultato è un [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) che rappresenta un involucro convesso<br/>            attorno a tutti i punti delle geometrie. |


### Method: get_distance_to(other) {#get_distance_to_other_24}


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


### Method: get_extent() {#get_extent__25}


```
 get_extent() 
```

Calcola e restituisce l'estensione di delimitazione di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione di delimitazione di questa geometria. |


### Method: get_length() {#get_length__26}


```
 get_length() 
```

Calcola la lunghezza di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | La lunghezza di questa geometria.<br/>            Perimetro se questa è un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Somma delle lunghezze degli elementi di questa geometria se questa geometria è una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_27}


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


### Method: intersects(extent) {#intersects_extent_28}


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


### Method: intersects(other) {#intersects_other_29}


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


### Method: overlaps(other) {#overlaps_other_30}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_31}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__32}


```
 replace_polygons_by_lines() 
```

Ottiene i poligoni rappresentati come linee di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometria che non contiene geometrie poligonali. Vengono applicate le seguenti trasformazioni:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono linearizzate<br/>            (trasformate in [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) vengono unite in [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_33}


```
 round_m(digits) 
```

Arrotonda la coordinata M a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: round_xy(digits) {#round_xy_digits_34}


```
 round_xy(digits) 
```

Arrotonda le coordinate X e Y a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: round_z(digits) {#round_z_digits_35}


```
 round_z(digits) 
```

Arrotonda la coordinata Z a un numero specificato di cifre frazionarie.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cifre | int | Numero di cifre frazionarie. |

### Method: spatially_contains(other) {#spatially_contains_other_36}


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


### Method: spatially_equals(other) {#spatially_equals_other_37}


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


### Method: sym_difference(other) {#sym_difference_other_38}


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


### Method: to_editable() {#to_editable__39}


```
 to_editable() 
```

Ottiene una copia modificabile di questa geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve) | Una copia modificabile di questa geometria. |


### Method: to_linear_geometry() {#to_linear_geometry__40}


```
 to_linear_geometry() 
```

Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> predefinita.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Una [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) che approssima o è equivalente a questa curva.<br/>            Questa è l'equivalente di <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) con<br/>            <c>tolerance</c> predefinito. Il valore predefinito di <c>tolerance</c> dipende da [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            di questa geometria:<br/>            <ul><br/>            <li> Per SRS proiettato la tolleranza è 0.001 metri (nelle unità SRS) </li><br/>            <li> Per SRS geografico la tolleranza è <c>1e-5</c> gradi (nelle unità SRS) </li><br/>            <li> Per SRS sconosciuto la tolleranza è <c>1e-5</c> </li><br/>            </ul><br/>            Per maggiori dettagli sulle trasformazioni applicate, fare riferimento alla specifica <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_41}


```
 to_linear_geometry(tolerance) 
```

Ottiene una versione approssimativa o equivalente non curva di questa geometria usando la <c>tolerance</c> specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tolleranza | double | La <c>tolerance</c> da utilizzare. Il risultato è garantito essere inferiore a <c>tolerance</c> dalla<br/>             geometria curva, a meno che il numero di punti necessario per linearizzare la geometria superi il massimo per quadrante,<br/>             attualmente pari a 10000 punti. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Una [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) che approssima o è equivalente a questa curva:<br/> <ul><br/> Se questo oggetto è [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) stesso il risultato è equivalente a questo oggetto<br/> Se questo oggetto è [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) il risultato è la stringa circolare linearizzata con la <paramref name="tolerance" /> specificata<br/> Se questo oggetto è [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) - tutte le curve da esso sono linearizzate e poi unite in [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/> </ul> |


### Method: to_svg(extent) {#to_svg_extent_42}


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


### Method: touches(other) {#touches_other_43}


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


### Method: union(other) {#union_other_44}


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


### Method: union(other) {#union_other_45}


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


### Method: within(extent) {#within_extent_46}


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


### Method: within(other) {#within_other_47}


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


