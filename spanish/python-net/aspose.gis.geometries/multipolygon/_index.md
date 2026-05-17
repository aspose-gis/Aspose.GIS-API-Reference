---
title: "MultiPolygon Clase"
type: docs
weight: 280
url: /es/python-net/aspose.gis.geometries/multipolygon/
---

**Summary:** A [MultiPolygon](/psd/python-net/aspose.gis.geometries/multipolygon/) is a one-dimensional <br/>            [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) whose elements are [Polygon](/psd/python-net/aspose.gis.geometries/polygon/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.MultiPolygon

**Inheritance:** IGeometry, IGeometryCollection, IMultiSurface, IMultiPolygon, MultiSurface

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [MultiPolygon()](#MultiPolygon__1) | Inicializa una nueva instancia de la clase [MultiPolygon](/psd/python-net/aspose.gis.geometries/multipolygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Obtiene el número de dimensiones de coordenadas para este [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| conteo | int | r | Obtiene el número de geometrías en esta colección. |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Obtiene la dimensión topológica de este [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Obtiene el tipo de la geometría. |
| has_curve_geometry | bool | r | Obtiene un valor que indica si esta geometría es o contiene geometría curva (no lineal). |
| has_m | bool | r/w | Obtiene un valor que indica si esta instancia tiene coordenada M. |
| has_z | bool | r/w | Obtiene un valor que indica si esta instancia tiene coordenada Z. |
| is_empty | bool | r | Obtiene un valor que indica si esta instancia está vacía (representa el conjunto de puntos vacío). |
| is_simple | bool | r | Obtiene un valor que indica si esta instancia es simple desde el punto de vista de SFA. |
| is_valid | bool | r | Obtiene un valor que indica si esta instancia es válida. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Obtiene una instancia de geometría nula. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Obtiene el SpatialReferenceSystem de esta instancia.<br/>            Esta propiedad puede ser <see langword="null" />, si el SpatialReferenceSystem es desconocido. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(geometry)](#add_geometry_1) | Agrega la geometría especificada a la colección. |
| [add_range(geometries)](#add_range_geometries_2) | Agrega las geometrías especificadas a la colección. |
| [as_binary()](#as_binary__3) | Traduce esta geometría a su representación Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_4) | Traduce esta geometría a su representación Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Exporta esta geometría a una representación de imagen. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_6) | Exporta esta geometría a una representación de imagen. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_7) | Exporta esta geometría a una representación de imagen. |
| [as_text()](#as_text__8) | Traduce esta geometría a su representación Well-Known Text. |
| [as_text(variant)](#as_text_variant_9) | Traduce esta geometría a su representación Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_10) | Traduce esta geometría a su representación Well-Known Text. |
| [clone()](#clone__11) | Clona esta instancia. |
| [covered_by(other)](#covered_by_other_12) | Determina si esta geometría está cubierta por una geometría especificada. |
| [covers(other)](#covers_other_13) | Determina si esta geometría cubre una geometría especificada. |
| [crosses(other)](#crosses_other_14) | Determina si esta geometría y una geometría especificada se cruzan. |
| [difference(other)](#difference_other_15) | Resta una geometría especificada de esta geometría. |
| [disjoint(other)](#disjoint_other_16) | Determina si esta geometría está disjunta de una geometría especificada. |
| [from_binary(wkb)](#from_binary_wkb_17) | Crea una geometría a partir de su representación Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_18) | Crea una geometría a partir de su representación Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_19) | Crea una geometría a partir de su representación Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_20) | Crea una geometría a partir de su representación Well-Known Text. |
| [get_area()](#get_area__21) | Calcula el área de esta geometría. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_22) | Calcula una región de buffer alrededor de esta geometría. |
| [get_centroid()](#get_centroid__23) | Calcula el centroide de esta geometría. |
| [get_convex_hull()](#get_convex_hull__24) | Calcula la envolvente convexa de esta geometría. |
| [get_distance_to(other)](#get_distance_to_other_25) | Calcula la distancia mínima entre esta geometría y una geometría especificada. |
| [get_extent()](#get_extent__26) | Calcula y devuelve una extensión delimitadora de esta geometría. |
| [get_length()](#get_length__27) | Calcula la longitud de esta geometría. |
| [get_point_on_surface()](#get_point_on_surface__28) | Encuentra un punto que se garantiza que está en una de las superficies de esta colección. |
| [intersection(other)](#intersection_other_29) | Construye una intersección entre esta geometría y una geometría especificada. |
| [intersects(extent)](#intersects_extent_30) | Determina si esta geometría intersecta una extensión especificada. |
| [intersects(other)](#intersects_other_31) | Determina si esta geometría y una geometría especificada intersectan. |
| [overlaps(other)](#overlaps_other_32) | Determina si esta geometría se superpone con una geometría especificada. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | Determina si la matriz de intersección DE-9IM de esta geometría y una geometría especificada coincide con el patrón proporcionado. |
| [remove_at(index)](#remove_at_index_34) | Elimina la geometría especificada de la colección. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | Obtiene los polígonos representados como líneas de esta geometría. |
| [round_m(digits)](#round_m_digits_36) | Redondea la coordenada M a un número especificado de dígitos fraccionarios. |
| [round_xy(digits)](#round_xy_digits_37) | Redondea las coordenadas X e Y a un número especificado de dígitos fraccionarios. |
| [round_z(digits)](#round_z_digits_38) | Redondea la coordenada Z a un número especificado de dígitos fraccionarios. |
| set_empty() | Hace que esta [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) esté vacía. |
| [spatially_contains(other)](#spatially_contains_other_39) | Determina si esta geometría contiene espacialmente una geometría especificada. |
| [spatially_equals(other)](#spatially_equals_other_40) | Determina si esta geometría es espacialmente igual a una geometría especificada. |
| [sym_difference(other)](#sym_difference_other_41) | Construye una diferencia simétrica entre esta geometría y una geometría especificada. |
| [to_editable()](#to_editable__42) | Obtiene una copia editable de esta geometría. |
| [to_linear_geometry()](#to_linear_geometry__43) | Obtiene una versión aproximada o equivalente sin curvas de esta geometría usando la <c>tolerance</c> predeterminada. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | Obtiene una versión aproximada o equivalente sin curvas de esta geometría usando la <c>tolerance</c> especificada. |
| [to_svg(extent)](#to_svg_extent_45) | Traduce esta geometría a la representación Svg. |
| [touches(other)](#touches_other_46) | Determina si esta geometría y una geometría especificada se tocan. |
| [union(other)](#union_other_47) | Une esta geometría y una geometría especificada. |
| [union(other)](#union_other_48) | Une esta geometría y una geometría especificada. |
| [within(extent)](#within_extent_49) | Determina si esta geometría está dentro de una extensión especificada. |
| [within(other)](#within_other_50) | Determina si esta geometría está dentro de una geometría especificada. |


### Constructor: MultiPolygon() {#MultiPolygon__1}


```
 MultiPolygon() 
```

Inicializa una nueva instancia de la clase [MultiPolygon](/psd/python-net/aspose.gis.geometries/multipolygon/).

### Method: add(geometry) {#add_geometry_1}


```
 add(geometry) 
```

Agrega la geometría especificada a la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | La geometría a agregar. |

### Method: add_range(geometries) {#add_range_geometries_2}


```
 add_range(geometries) 
```

Agrega las geometrías especificadas a la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometries | System.Collections.Generic.IEnumerable<IGeometry> | Las geometrías a agregar. |

### Method: as_binary() {#as_binary__3}


```
 as_binary() 
```

Traduce esta geometría a su representación Well-Known Binary.

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Representación Well-Known Binary de esta geometría. |


### Method: as_binary(variant) {#as_binary_variant_4}


```
 as_binary(variant) 
```

Traduce esta geometría a su representación Well-Known Binary.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Variante Well-Known Binary a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Representación Well-Known Binary de esta geometría. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporta esta geometría a una representación de imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la imagen de salida. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ancho del mapa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altura del mapa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderizador a usar. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_6}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporta esta geometría a una representación de imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| output_path | string | Ruta a la imagen de salida. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ancho del mapa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altura del mapa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderizador a usar. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_7}


```
 as_image(width, height, renderer, symbolizer) 
```

Exporta esta geometría a una representación de imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ancho del mapa. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Altura del mapa. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderizador a usar. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un simbolizador a usar para el renderizado. Si <see langword="null" />, se usa el simbolizador predeterminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | La imagen como flujo |


### Method: as_text() {#as_text__8}


```
 as_text() 
```

Traduce esta geometría a su representación Well-Known Text.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Representación Well-Known Text de esta geometría. |


### Method: as_text(variant) {#as_text_variant_9}


```
 as_text(variant) 
```

Traduce esta geometría a su representación Well-Known Text.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Representación Well-Known Text de esta geometría. |


### Method: as_text(variant, format) {#as_text_variant_format_10}


```
 as_text(variant, format) 
```

Traduce esta geometría a su representación Well-Known Text.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text a usar. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Formato de coordenadas para la conversión a cadena. Consulte el [NumericFormat](/psd/python-net/aspose.gis/numericformat/) para obtenerlo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Representación Well-Known Text de esta geometría. |


### Method: clone() {#clone__11}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | El clon de esta instancia |


### Method: covered_by(other) {#covered_by_other_12}


```
 covered_by(other) 
```

Determina si esta geometría está cubierta por una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword="true" /> si esta geometría está "spatially covered by" otra geometría. <see langword="false" /> de lo contrario. |


### Method: covers(other) {#covers_other_13}


```
 covers(other) 
```

Determina si esta geometría cubre una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword="true" /> si esta geometría "spatially covers" otra geometría. <see langword="false" /> de lo contrario. |


### Method: crosses(other) {#crosses_other_14}


```
 crosses(other) 
```

Determina si esta geometría y una geometría especificada se cruzan.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword="true" /> si esta geometría "spatially crosses" otra geometría. <see langword="false" /> de lo contrario. |


### Method: difference(other) {#difference_other_15}


```
 difference(other) 
```

Resta una geometría especificada de esta geometría.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría para restar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la diferencia de esta geometría y un argumento. La geometría resultante contiene<br/>            conjunto de puntos que están presentes en esta geometría pero no en un argumento. |


### Method: disjoint(other) {#disjoint_other_16}


```
 disjoint(other) 
```

Determina si esta geometría está disjunta de una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría está \"espacialmente disjunta\" de otra geometría. <see langword=\"false\" /> en caso contrario. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_17}


```
 from_binary(wkb) 
```

Crea una geometría a partir de su representación Well-Known Binary.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkb | byte | Representación Well-Known Binary de una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría representada por el argumento. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_18}


```
 from_binary(wkb, spatial_reference_system) 
```

Crea una geometría a partir de su representación Well-Known Binary.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkb | byte | Representación Well-Known Binary de una geometría. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de Referencia Espacial que se asignará a la geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría representada por el argumento. |


### Method: from_text(wkt)  [static] {#from_text_wkt_19}


```
 from_text(wkt) 
```

Crea una geometría a partir de su representación Well-Known Text.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkt | string | Representación Well-Known Text de una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría representada por el argumento. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_20}


```
 from_text(wkt, spatial_reference_system) 
```

Crea una geometría a partir de su representación Well-Known Text.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkt | string | Representación Well-Known Text de una geometría. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de Referencia Espacial que se asignará a la geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría representada por el argumento. |


### Method: get_area() {#get_area__21}


```
 get_area() 
```

Calcula el área de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | El área de esta geometría.<br/>            Suma de áreas de los elementos de esta geometría si esta geometría es una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_22}


```
 get_buffer(distance, quadrant_segments) 
```

Calcula una región de buffer alrededor de esta geometría.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| distance | double | El ancho de la región de buffer (en unidades de Spatial Reference). |
| quadrant_segments | int | Número de segmentos utilizados para aproximar una curvatura de 90 grados.<br/>            Cuanto mayor sea este número, mejor será la aproximación de las curvas.<br/>            El valor predeterminado es 30. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa todos los puntos que están dentro de una distancia especificada de<br/>            esta geometría.<br/>            El tipo de resultado es o bien [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) o [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__23}


```
 get_centroid() 
```

Calcula el centroide de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | El centroide de esta geometría. Si esta geometría está vacía se devuelve un punto vacío.<br/>            El centroide es igual al centroide de las geometrías de mayor dimensión en esta geometría<br/>            (p. ej., si la geometría contiene puntos y líneas, solo las líneas contribuyen al centroide). |


### Method: get_convex_hull() {#get_convex_hull__24}


```
 get_convex_hull() 
```

Calcula la envolvente convexa de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la envolvente convexa de esta geometría.<br/>            Si esta geometría no tiene puntos, el resultado es [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Si esta geometría tiene solo un punto, el resultado es ese punto.<br/>            Si esta geometría tiene solo dos puntos, el resultado es [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) con los puntos.<br/>            Si esta geometría tiene tres o más puntos, el resultado es [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) que representa una envolvente convexa<br/>            alrededor de todos los puntos de las geometrías. |


### Method: get_distance_to(other) {#get_distance_to_other_25}


```
 get_distance_to(other) 
```

Calcula la distancia mínima entre esta geometría y una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría para encontrar la distancia. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | Si ambas geometrías no están [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - una distancia entre los puntos más cercanos de las geometrías.<br/>            Si al menos una geometría está vacía, se devuelve -1. |


### Method: get_extent() {#get_extent__26}


```
 get_extent() 
```

Calcula y devuelve una extensión delimitadora de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Una extensión delimitadora de esta geometría. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

Calcula la longitud de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | La longitud de esta geometría.<br/>            Perímetro si se trata de un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Suma de longitudes de los elementos de esta geometría si esta geometría es una [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

Encuentra un punto que se garantiza que está en una de las superficies de esta colección.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Un punto en una de las superficies. Un punto vacío si esta colección no contiene superficies o todas las superficies están vacías. |


### Method: intersection(other) {#intersection_other_29}


```
 intersection(other) 
```

Construye una intersección entre esta geometría y una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría con la que calcular la intersección. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la intersección de esta geometría y un argumento. La geometría resultante contiene<br/>            conjunto de puntos que están presentes tanto en esta geometría como en un argumento. |


### Method: intersects(extent) {#intersects_extent_30}


```
 intersects(extent) 
```

Determina si esta geometría intersecta una extensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | La extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría intersecta la extensión; <see langword=\"false\" /> de lo contrario. |


### Method: intersects(other) {#intersects_other_31}


```
 intersects(other) 
```

Determina si esta geometría y una geometría especificada intersectan.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría \"intersecta espacialmente\" otra geometría. <see langword=\"false\" /> de lo contrario. |


### Method: overlaps(other) {#overlaps_other_32}


```
 overlaps(other) 
```

Determina si esta geometría se superpone con una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría \"se superpone espacialmente\" con otra geometría. <see langword=\"false\" /> de lo contrario. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


```
 relate(other, intersection_pattern_matrix) 
```

Determina si la matriz de intersección DE-9IM de esta geometría y una geometría especificada coincide con el patrón proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |
| intersection_pattern_matrix | string | Un patrón con el que coincidir.<br/>            Debe ser una cadena con longitud igual a 9.<br/>            Cada carácter de la cadena representa la dimensión esperada de una intersección:<br/>            <ul><br/>            <li>carácter 0 - entre los interiores de las geometrías.</li><br/>            <li>carácter 1 - entre el interior de esta geometría y el límite de otra geometría.</li><br/>            <li>carácter 2 - entre el interior de esta geometría y el exterior de otra geometría.</li><br/>            <li>carácter 3 - entre el límite de esta geometría y el interior de otra geometría.</li><br/>            <li>carácter 4 - entre los límites de las geometrías.</li><br/>            <li>carácter 5 - entre el límite de esta geometría y el exterior de otra geometría.</li><br/>            <li>carácter 6 - entre el exterior de esta geometría y el interior de otra geometría.</li><br/>            <li>carácter 7 - entre el exterior de esta geometría y el límite de otra geometría.</li><br/>            <li>carácter 8 - entre los exteriores de las geometrías.</li><br/>            </ul><br/>            Los valores posibles de cada carácter son:<br/>            <ul><br/>            <li>* - cualquier valor;</li><br/>            <li>F - no hay intersección;</li><br/>            <li>T - cualquier intersección;</li><br/>            <li>0 - intersección de punto (p.ej., punto compartido);</li><br/>            <li>1 - intersección de línea (p.ej., segmento de línea compartido);</li><br/>            <li>2 - intersección de área (p.ej., parte compartida de polígono);</li><br/>            </ul><br/>            Por ejemplo, un patrón de intersección \"F0*******\" indica que no debe haber intersección entre los interiores de las geometrías y que la intersección entre los límites de las geometrías debe ser un punto.<br/>            Consulte la especificación OpenGIS Simple Features para más detalles sobre el patrón de la matriz de intersección. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta matriz de intersección coincide con el patrón; <see langword=\"false\" /> de lo contrario. |


### Method: remove_at(index) {#remove_at_index_34}


```
 remove_at(index) 
```

Elimina la geometría especificada de la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la geometría a eliminar. |

### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

Obtiene los polígonos representados como líneas de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | Una geometría que no contiene geometrías de tipo polígono. Se aplican las siguientes transformaciones:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s se linealizan<br/>            (transformados en [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s se combinan en [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

Redondea la coordenada M a un número especificado de dígitos fraccionarios.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dígitos | int | Número de dígitos fraccionarios. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

Redondea las coordenadas X e Y a un número especificado de dígitos fraccionarios.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dígitos | int | Número de dígitos fraccionarios. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Redondea la coordenada Z a un número especificado de dígitos fraccionarios.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dígitos | int | Número de dígitos fraccionarios. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

Determina si esta geometría contiene espacialmente una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría \"contiene espacialmente\" otra geometría. <see langword=\"false\" /> de lo contrario. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

Determina si esta geometría es espacialmente igual a una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría \"es espacialmente igual\" a la geometría especificada. <see langword=\"false\" /> de lo contrario. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

Construye una diferencia simétrica entre esta geometría y una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría con la que calcular la diferencia simétrica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la diferencia simétrica de esta geometría y un argumento. La geometría resultante contiene<br/>            el conjunto de puntos que está presente en una de las geometrías pero no en ambas. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

Obtiene una copia editable de esta geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [MultiPolygon](/psd/python-net/aspose.gis.geometries/multipolygon) | Una copia editable de esta geometría. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

Obtiene una versión aproximada o equivalente sin curvas de esta geometría usando la <c>tolerance</c> predeterminada.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon) | Un [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) que aproxima o es equivalente a este [IMultiSurface](/psd/python-net/aspose.gis.geometries/imultisurface/).<br/>            Esto es el equivalente de <DOM Element: class at 0x2a1792e8790>.IMultiSurface.to_linear_geometry()(float) con<br/>            tolerancia predeterminada <c>tolerance</c>. El valor predeterminado de <c>tolerance</c> depende de [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            de esta geometría:<br/>            <ul><br/>            <li> Para SRS proyectado la tolerancia es 0.001 metros (en unidades del SRS) </li><br/>            <li> Para SRS geográfico la tolerancia es <c>1e-5</c> grados (en unidades del SRS) </li><br/>            <li> Para SRS desconocido la tolerancia es <c>1e-5</c> </li><br/>            </ul><br/>            Para más detalles sobre qué transformaciones se aplican, consulte la especificación de <DOM Element: class at 0x2a1792e8790>.IMultiSurface.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

Obtiene una versión aproximada o equivalente sin curvas de esta geometría usando la <c>tolerance</c> especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tolerancia | double | La <c>tolerance</c> a usar. Se garantiza que el resultado esté a menos de <c>tolerance</c> de la<br/>             geometría curva, a menos que la cantidad de puntos necesarios para linealizar la geometría supere el máximo por cuadrante,<br/>             actualmente igual a 10000 puntos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon) | Un [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) que aproxima o es equivalente a este [IMultiSurface](/psd/python-net/aspose.gis.geometries/imultisurface/):<br/>             <ul><br/>             Si este objeto es [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) en sí, el resultado es equivalente a este objeto<br/>             Si este objeto no es [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) - todas las superficies se linealizan y se crea un nuevo <c>IMultiPolygon</c><br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

Traduce esta geometría a la representación Svg.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Extensión para traducir esta geometría a Svg |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | La representación Svg. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

Determina si esta geometría y una geometría especificada se tocan.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría \"toca espacialmente\" otra geometría. <see langword=\"false\" /> de lo contrario. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Une esta geometría y una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría con la que unir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la unión de esta geometría y un argumento. La geometría resultante contiene<br/>            el conjunto de puntos que está presente en esta geometría o en el argumento. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

Une esta geometría y una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría con la que unir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría que representa la unión de esta geometría y un argumento. La geometría resultante contiene<br/>            el conjunto de puntos que está presente en esta geometría o en el argumento. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

Determina si esta geometría está dentro de una extensión especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | La extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría está dentro de la extensión; <see langword=\"false\" /> de lo contrario. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

Determina si esta geometría está dentro de una geometría especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Una geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si esta geometría está \"espacialmente dentro\" de otra geometría. <see langword=\"false\" /> de lo contrario. |


