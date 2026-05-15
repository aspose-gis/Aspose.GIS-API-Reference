---
title: "Classe CircularString"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.geometries/circularstring/
---

**Summary:** A multi-vertex curve with circular interpolation between points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.CircularString

**Inheritance:** IGeometry, ICurve, ICircularString, Curve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CircularString()](#CircularString__1) | Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/). |
| [CircularString(collection)](#CircularString_collection_2) | Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/). |
| [CircularString(other)](#CircularString_other_3) | Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Obtient le nombre de dimensions de coordonnées pour ce [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Obtient la dimension topologique de ce [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Renvoie une copie du point final de la courbe. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Obtient le type de la géométrie. |
| has_curve_geometry | bool | r | Obtient une valeur indiquant si cette géométrie est ou contient une géométrie courbe (non linéaire). |
| has_m | bool | r/w | Obtient une valeur indiquant si cette instance possède une coordonnée M. |
| has_z | bool | r/w | Obtient une valeur indiquant si cette instance possède une coordonnée Z. |
| is_closed | bool | r | Obtient une valeur indiquant si une courbe est fermée. <br/> Une courbe est fermée si son point de départ est égal à son point final. |
| is_empty | bool | r | Obtient une valeur indiquant si cette instance est vide. |
| is_simple | bool | r | Obtient une valeur indiquant si cette instance est simple du point de vue du SFA. |
| is_valid | bool | r | Obtient une valeur indiquant si cette instance est valide. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Obtient une instance de géométrie nulle. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Obtient le SpatialReferenceSystem de cette instance.<br/> Cette propriété peut être <see langword="null" />, si le SpatialReferenceSystem n'est pas défini.<br/> L'affectation d'un nouveau SpatialReferenceSystem n'effectuera aucune transformation de coordonnées, seul la référence changera. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Renvoie une copie du point de départ de la courbe. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | Ajoute un point à la fin de la chaîne circulaire. |
| [add_point(x, y)](#add_point_x_y_2) | Ajoute un point à la fin de la chaîne circulaire. |
| [add_point(x, y, z)](#add_point_x_y_z_3) | Ajoute un point à la fin de la chaîne circulaire. |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | Ajoute un point à la fin de la chaîne circulaire. |
| [as_binary()](#as_binary__5) | Traduit cette géométrie en sa représentation Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_6) | Traduit cette géométrie en sa représentation Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | Exporte cette géométrie vers une représentation image. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | Exporte cette géométrie vers une représentation image. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | Exporte cette géométrie vers une représentation image. |
| [as_text()](#as_text__10) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [as_text(variant)](#as_text_variant_11) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_12) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [clone()](#clone__13) | Clone cette instance. |
| [covered_by(other)](#covered_by_other_14) | Détermine si cette géométrie est couverte par une géométrie spécifiée. |
| [covers(other)](#covers_other_15) | Détermine si cette géométrie couvre une géométrie spécifiée. |
| [crosses(other)](#crosses_other_16) | Détermine si cette géométrie et une géométrie spécifiée se croisent. |
| [difference(other)](#difference_other_17) | Soustrait une géométrie spécifiée de cette géométrie. |
| [disjoint(other)](#disjoint_other_18) | Détermine si cette géométrie est disjointe d'une géométrie spécifiée. |
| [from_binary(wkb)](#from_binary_wkb_19) | Crée une géométrie à partir de sa représentation Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | Crée une géométrie à partir de sa représentation Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_21) | Crée une géométrie à partir de sa représentation Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | Crée une géométrie à partir de sa représentation Well-Known Text. |
| [get_area()](#get_area__23) | Calcule la surface de cette géométrie. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | Calcule une zone tampon autour de cette géométrie. |
| [get_centroid()](#get_centroid__25) | Calcule le centroïde de cette géométrie. |
| [get_convex_hull()](#get_convex_hull__26) | Calcule l'enveloppe convexe de cette géométrie. |
| [get_distance_to(other)](#get_distance_to_other_27) | Calcule la distance minimale entre cette géométrie et une géométrie spécifiée. |
| [get_extent()](#get_extent__28) | Calcule et renvoie l'étendue englobante de cette géométrie. |
| [get_length()](#get_length__29) | Calcule la longueur de cette géométrie. |
| [intersection(other)](#intersection_other_30) | Construit une intersection entre cette géométrie et une géométrie spécifiée. |
| [intersects(extent)](#intersects_extent_31) | Détermine si cette géométrie intersecte une étendue spécifiée. |
| [intersects(other)](#intersects_other_32) | Détermine si cette géométrie et une géométrie spécifiée s'intersectent. |
| [overlaps(other)](#overlaps_other_33) | Détermine si cette géométrie se chevauche avec une géométrie spécifiée. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_34) | Détermine si la matrice d'intersection DE-9IM de cette géométrie et d'une géométrie spécifiée correspond au modèle fourni. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | Obtient les polygones représentés comme lignes de cette géométrie. |
| reverse() | Inverse l’ordre des points dans ce [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/). |
| [round_m(digits)](#round_m_digits_36) | Arrondit la coordonnée M à un nombre spécifié de chiffres fractionnels. |
| [round_xy(digits)](#round_xy_digits_37) | Arrondit les coordonnées X et Y à un nombre spécifié de chiffres fractionnels. |
| [round_z(digits)](#round_z_digits_38) | Arrondit la coordonnée Z à un nombre spécifié de chiffres fractionnels. |
| set_empty() | Rend cette [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) vide. |
| [spatially_contains(other)](#spatially_contains_other_39) | Détermine si cette géométrie contient spatialement une géométrie spécifiée. |
| [spatially_equals(other)](#spatially_equals_other_40) | Détermine si cette géométrie est spatialement égale à une géométrie spécifiée. |
| [sym_difference(other)](#sym_difference_other_41) | Construit une différence symétrique entre cette géométrie et une géométrie spécifiée. |
| [to_editable()](#to_editable__42) | Obtient une copie modifiable de cette géométrie. |
| [to_linear_geometry()](#to_linear_geometry__43) | Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> par défaut. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> spécifiée. |
| [to_svg(extent)](#to_svg_extent_45) | Traduit cette géométrie en représentation Svg. |
| [touches(other)](#touches_other_46) | Détermine si cette géométrie et une géométrie spécifiée se touchent. |
| [union(other)](#union_other_47) | Unit cette géométrie et une géométrie spécifiée. |
| [union(other)](#union_other_48) | Unit cette géométrie et une géométrie spécifiée. |
| [within(extent)](#within_extent_49) | Détermine si cette géométrie se trouve à l'intérieur d'une étendue spécifiée. |
| [within(other)](#within_other_50) | Détermine si cette géométrie se trouve à l'intérieur d'une géométrie spécifiée. |


### Constructor: CircularString() {#CircularString__1}


```
 CircularString() 
```

Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/).

### Constructor: CircularString(collection) {#CircularString_collection_2}


```
 CircularString(collection) 
```

Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| collection | System.Collections.Generic.IEnumerable<IPoint> | La collection de points. |

### Constructor: CircularString(other) {#CircularString_other_3}


```
 CircularString(other) 
```

Initialise une nouvelle instance de la classe [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring) | L’autre chaîne à partir de laquelle copier les données. |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

Ajoute un point à la fin de la chaîne circulaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Le point à ajouter. |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

Ajoute un point à la fin de la chaîne circulaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

Ajoute un point à la fin de la chaîne circulaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |
| z | double | La valeur pour la coordonnée Z. |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

Ajoute un point à la fin de la chaîne circulaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |
| z | double | La valeur pour la coordonnée Z. |
| m | double | La valeur pour la coordonnée M. |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

Traduit cette géométrie en sa représentation Well-Known Binary.

**Returns**

| Type | Description |
| :- | :- |
| byte | Représentation Well-Known Binary de cette géométrie. |


### Method: as_binary(variant) {#as_binary_variant_6}


```
 as_binary(variant) 
```

Traduit cette géométrie en sa représentation Well-Known Binary.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Variante Well-Known Binary à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Représentation Well-Known Binary de cette géométrie. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporte cette géométrie vers une représentation image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers l'image de sortie. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Largeur de la carte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hauteur de la carte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Moteur de rendu à utiliser. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Exporte cette géométrie vers une représentation image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| output_path | string | Chemin vers l'image de sortie. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Largeur de la carte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hauteur de la carte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Moteur de rendu à utiliser. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


```
 as_image(width, height, renderer, symbolizer) 
```

Exporte cette géométrie vers une représentation image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Largeur de la carte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Hauteur de la carte. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Moteur de rendu à utiliser. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | L'image sous forme de flux |


### Method: as_text() {#as_text__10}


```
 as_text() 
```

Traduit cette géométrie en sa représentation Well-Known Text.

**Returns**

| Type | Description |
| :- | :- |
| string | Représentation Well-Known Text de cette géométrie. |


### Method: as_text(variant) {#as_text_variant_11}


```
 as_text(variant) 
```

Traduit cette géométrie en sa représentation Well-Known Text.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| string | Représentation Well-Known Text de cette géométrie. |


### Method: as_text(variant, format) {#as_text_variant_format_12}


```
 as_text(variant, format) 
```

Traduit cette géométrie en sa représentation Well-Known Text.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Variante Well-Known Text à utiliser. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Format de coordonnées pour la conversion en chaîne. Voir le [NumericFormat](/psd/python-net/aspose.gis/numericformat/) pour l'obtenir. |

**Returns**

| Type | Description |
| :- | :- |
| string | Représentation Well-Known Text de cette géométrie. |


### Method: clone() {#clone__13}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Le clone de cette instance |


### Method: covered_by(other) {#covered_by_other_14}


```
 covered_by(other) 
```

Détermine si cette géométrie est couverte par une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie est « spatialement couverte par » une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: covers(other) {#covers_other_15}


```
 covers(other) 
```

Détermine si cette géométrie couvre une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie « couvre spatialement » une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: crosses(other) {#crosses_other_16}


```
 crosses(other) 
```

Détermine si cette géométrie et une géométrie spécifiée se croisent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie « croise spatialement » une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: difference(other) {#difference_other_17}


```
 difference(other) 
```

Soustrait une géométrie spécifiée de cette géométrie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie à soustraire. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente la différence entre cette géométrie et un argument. La géométrie résultante contient<br/>            l'ensemble de points présents dans cette géométrie mais pas présents dans un argument. |


### Method: disjoint(other) {#disjoint_other_18}


```
 disjoint(other) 
```

Détermine si cette géométrie est disjointe d'une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword="true" /> si cette géométrie est "spatially disjoint" d'une autre géométrie. <see langword="false" /> sinon. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


```
 from_binary(wkb) 
```

Crée une géométrie à partir de sa représentation Well-Known Binary.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkb | byte | Représentation Well-Known Binary d'une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie représentée par l'argument. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


```
 from_binary(wkb, spatial_reference_system) 
```

Crée une géométrie à partir de sa représentation Well-Known Binary.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkb | byte | Représentation Well-Known Binary d'une géométrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale à attribuer à la géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie représentée par l'argument. |


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


```
 from_text(wkt) 
```

Crée une géométrie à partir de sa représentation Well-Known Text.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkt | string | Représentation Well-Known Text d'une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie représentée par l'argument. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


```
 from_text(wkt, spatial_reference_system) 
```

Crée une géométrie à partir de sa représentation Well-Known Text.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkt | string | Représentation Well-Known Text d'une géométrie. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale à attribuer à la géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie représentée par l'argument. |


### Method: get_area() {#get_area__23}


```
 get_area() 
```

Calcule la surface de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| double | L'aire de cette géométrie.<br/>            Somme des aires des éléments de cette géométrie si celle-ci est une [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


```
 get_buffer(distance, quadrant_segments) 
```

Calcule une zone tampon autour de cette géométrie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| distance | double | La largeur de la zone tampon (en unités de référence spatiale). |
| quadrant_segments | int | Nombre de segments utilisés pour approximer une courbure de 90 degrés.<br/>            Plus ce nombre est grand, meilleure est l'approximation des courbes.<br/>            La valeur par défaut est 30. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente tous les points situés à une distance spécifiée de<br/>            cette géométrie.<br/>            Le type du résultat est soit [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ou [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

Calcule le centroïde de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Le centroïde de cette géométrie. Si cette géométrie est vide, un point vide est renvoyé.<br/>            Le centroïde est égal au centroïde des géométries de plus haute dimension dans cette géométrie<br/>            (par ex. si des points et des lignes sont contenus dans la géométrie, seules les lignes contribuent au centroïde). |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

Calcule l'enveloppe convexe de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente l'enveloppe convexe de cette géométrie.<br/>            Si cette géométrie n'a aucun point, le résultat est [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Si cette géométrie n'a qu'un seul point, le résultat est ce point.<br/>            Si cette géométrie n'a que deux points, le résultat est un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) contenant les points.<br/>            Si cette géométrie a trois points ou plus, le résultat est un [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) qui représente une enveloppe convexe autour de tous les points de la géométrie. |


### Method: get_distance_to(other) {#get_distance_to_other_27}


```
 get_distance_to(other) 
```

Calcule la distance minimale entre cette géométrie et une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie vers laquelle trouver la distance. |

**Returns**

| Type | Description |
| :- | :- |
| double | Si les deux géométries ne sont pas [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - une distance entre les points les plus proches des géométries.<br/>            Si au moins une géométrie est vide, -1 est renvoyé. |


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

Calcule et renvoie l'étendue englobante de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue englobante de cette géométrie. |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

Calcule la longueur de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| double | La longueur de cette géométrie.<br/>            Périmètre si c'est un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Somme des longueurs des éléments de cette géométrie si celle-ci est une [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_30}


```
 intersection(other) 
```

Construit une intersection entre cette géométrie et une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie avec laquelle calculer l'intersection. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente l'intersection de cette géométrie et d'un argument. La géométrie résultante contient<br/>            l'ensemble de points présents à la fois dans cette géométrie et dans l'argument. |


### Method: intersects(extent) {#intersects_extent_31}


```
 intersects(extent) 
```

Détermine si cette géométrie intersecte une étendue spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | L'étendue. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie intersecte l'étendue ; <see langword=\"false\" /> sinon. |


### Method: intersects(other) {#intersects_other_32}


```
 intersects(other) 
```

Détermine si cette géométrie et une géométrie spécifiée s'intersectent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially intersects\" une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: overlaps(other) {#overlaps_other_33}


```
 overlaps(other) 
```

Détermine si cette géométrie se chevauche avec une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially overlaps\" une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_34}


```
 relate(other, intersection_pattern_matrix) 
```

Détermine si la matrice d'intersection DE-9IM de cette géométrie et d'une géométrie spécifiée correspond au modèle fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |
| intersection_pattern_matrix | string | Un modèle à faire correspondre.<br/>            Cette chaîne doit avoir une longueur égale à 9.<br/>            Chaque caractère de la chaîne représente la dimension attendue d'une intersection :<br/>            <ul><br/>            <li>caractère 0 - entre les intérieurs des géométries.</li><br/>            <li>caractère 1 - entre l'intérieur de cette géométrie et la frontière d'une autre géométrie.</li><br/>            <li>caractère 2 - entre l'intérieur de cette géométrie et l'extérieur d'une autre géométrie.</li><br/>            <li>caractère 3 - entre la frontière de cette géométrie et l'intérieur d'une autre géométrie.</li><br/>            <li>caractère 4 - entre les frontières des géométries.</li><br/>            <li>caractère 5 - entre la frontière de cette géométrie et l'extérieur d'une autre géométrie.</li><br/>            <li>caractère 6 - entre l'extérieur de cette géométrie et l'intérieur d'une autre géométrie.</li><br/>            <li>caractère 7 - entre l'extérieur de cette géométrie et la frontière d'une autre géométrie.</li><br/>            <li>caractère 8 - entre les extérieurs des géométries.</li><br/>            </ul><br/>            Les valeurs possibles de chaque caractère sont :<br/>            <ul><br/>            <li>* - toute valeur ;</li><br/>            <li>F - aucune intersection ;</li><br/>            <li>T - toute intersection ;</li><br/>            <li>0 - intersection ponctuelle (p. ex. point partagé) ;</li><br/>            <li>1 - intersection linéaire (p. ex. segment partagé) ;</li><br/>            <li>2 - intersection surfacique (p. ex. partie partagée d'un polygone) ;</li><br/>            </ul><br/>            Par exemple, un motif d'intersection \"F0*******\" signifie qu'il ne doit pas y avoir d'intersection entre les intérieurs des géométries<br/>            et que l'intersection entre les frontières des géométries doit être un point.<br/>            Voir la spécification OpenGIS Simple Features pour plus de détails sur le motif de matrice d'intersection. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette matrice d'intersection correspond au modèle ; <see langword=\"false\" /> sinon. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

Obtient les polygones représentés comme lignes de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui ne possède pas de géométries polygonales. Les transformations suivantes sont appliquées :<br/>            <ul><br/>            <li> les [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) sont linéarisés<br/> (transformés en [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li> les [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) sont fusionnés en [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

Arrondit la coordonnée M à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

Arrondit les coordonnées X et Y à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Arrondit la coordonnée Z à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

Détermine si cette géométrie contient spatialement une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially contains\" une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

Détermine si cette géométrie est spatialement égale à une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially equals\" à la géométrie spécifiée. <see langword=\"false\" /> sinon. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

Construit une différence symétrique entre cette géométrie et une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie avec laquelle calculer la différence symétrique. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente la différence symétrique entre cette géométrie et un argument. La géométrie résultante contient<br/>            l'ensemble des points présents dans l'une des géométries mais pas dans les deux. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

Obtient une copie modifiable de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [CircularString](/psd/python-net/aspose.gis.geometries/circularstring) | Une copie modifiable de cette géométrie. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> par défaut.

**Returns**

| Type | Description |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) qui approxime ou équivaut à cette courbe.<br/> C'est l'équivalent de <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) avec<br/> la <c>tolerance</c> par défaut. La valeur par défaut de la <c>tolerance</c> dépend de [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) de cette géométrie :<br/> <ul><br/> <li> Pour un SRS projeté, la tolérance est de 0,001 mètres (dans les unités du SRS) </li><br/> <li> Pour un SRS géographique, la tolérance est de <c>1e-5</c> degrés (dans les unités du SRS) </li><br/> <li> Pour un SRS inconnu, la tolérance est de <c>1e-5</c> </li><br/> </ul><br/> Pour plus de détails sur les transformations appliquées, consultez la spécification de <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tolerance | double | La <c>tolerance</c> à utiliser. Le résultat est garanti être inférieur à <c>tolerance</c> de la géométrie courbe,<br/>             sauf si le nombre de points nécessaires pour linéariser la géométrie dépasse le maximum par quadrant,<br/>             actuellement égal à 10 000 points. |

**Returns**

| Type | Description |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Une [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) qui approxime ou équivalente à cette courbe :<br/>             <ul><br/>             Si cet objet est [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) lui‑même, le résultat est équivalent à cet objet<br/>             Si cet objet est [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) le résultat est la chaîne circulaire linéarisée avec la <paramref name="tolerance" /> spécifiée<br/>             Si cet objet est [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) - toutes les courbes qu’il contient sont linéarisées puis jointes en un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

Traduit cette géométrie en représentation Svg.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Étendue pour la translation de cette géométrie vers SVG |

**Returns**

| Type | Description |
| :- | :- |
| string | La représentation SVG. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

Détermine si cette géométrie et une géométrie spécifiée se touchent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially touches\" une autre géométrie. <see langword=\"false\" /> sinon. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Unit cette géométrie et une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie avec laquelle unir. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente l'union de cette géométrie et d'un argument. La géométrie résultante contient<br/>            l'ensemble des points présents dans cette géométrie ou dans l'argument. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

Unit cette géométrie et une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie avec laquelle unir. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente l'union de cette géométrie et d'un argument. La géométrie résultante contient<br/>            l'ensemble des points présents dans cette géométrie ou dans l'argument. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

Détermine si cette géométrie se trouve à l'intérieur d'une étendue spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | L'étendue. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie est à l'intérieur de l'étendue ; <see langword=\"false\" /> sinon. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

Détermine si cette géométrie se trouve à l'intérieur d'une géométrie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si cette géométrie \"spatially within\" une autre géométrie. <see langword=\"false\" /> sinon. |


