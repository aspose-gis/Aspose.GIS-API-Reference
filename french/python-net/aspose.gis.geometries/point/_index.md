---
title: "Classe Point"
type: docs
weight: 300
url: /fr/python-net/aspose.gis.geometries/point/
---

**Summary:** A [Point](/psd/python-net/aspose.gis.geometries/point/) represents a single location in coordinate space.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Point

**Inheritance:** IGeometry, IPoint, Geometry

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/). |
| [Point(other)](#Point_other_2) | Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/). |
| [Point(x, y)](#Point_x_y_3) | Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/). |
| [Point(x, y, z)](#Point_x_y_z_4) | Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/). |
| [Point(x, y, z, m)](#Point_x_y_z_m_5) | Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Obtient le nombre de dimensions de coordonnées pour ce [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Obtient la dimension topologique de ce [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Obtient le type de la géométrie. |
| has_curve_geometry | bool | r | Obtient une valeur indiquant si cette géométrie est ou contient une géométrie courbe (non linéaire). |
| has_m | bool | r/w | Obtient une valeur indiquant si cette instance possède une coordonnée M. |
| has_z | bool | r/w | Obtient une valeur indiquant si cette instance possède une coordonnée Z. |
| is_empty | bool | r | Obtient une valeur indiquant si cette instance est vide. |
| is_simple | bool | r | Obtient une valeur indiquant si cette instance est simple du point de vue du SFA. |
| is_valid | bool | r | Obtient une valeur indiquant si cette instance est valide. |
| m | double | r/w | Obtient ou définit une valeur pour la coordonnée m. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Obtient une instance de géométrie nulle. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Obtient le SpatialReferenceSystem de cette instance.<br/>            Cette propriété peut être <see langword=\"null\" />, si le SpatialReferenceSystem est inconnu.<br/>            L'attribution d'un nouveau SpatialReferenceSystem n'effectuera aucune transformation de coordonnées, seul la référence sera modifiée. |
| x | double | r/w | Obtient ou définit une valeur pour la coordonnée x. |
| y | double | r/w | Obtient ou définit une valeur pour la coordonnée y. |
| z | double | r/w | Obtient ou définit une valeur pour la coordonnée z. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Traduit cette géométrie en sa représentation Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_2) | Traduit cette géométrie en sa représentation Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Exporte cette géométrie vers une représentation image. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Exporte cette géométrie vers une représentation image. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Exporte cette géométrie vers une représentation image. |
| [as_text()](#as_text__6) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [as_text(variant)](#as_text_variant_7) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_8) | Traduit cette géométrie en sa représentation Well-Known Text. |
| [clone()](#clone__9) | Clone cette instance. |
| [covered_by(other)](#covered_by_other_10) | Détermine si cette géométrie est couverte par une géométrie spécifiée. |
| [covers(other)](#covers_other_11) | Détermine si cette géométrie couvre une géométrie spécifiée. |
| [crosses(other)](#crosses_other_12) | Détermine si cette géométrie et une géométrie spécifiée se croisent. |
| [difference(other)](#difference_other_13) | Soustrait une géométrie spécifiée de cette géométrie. |
| [disjoint(other)](#disjoint_other_14) | Détermine si cette géométrie est disjointe d'une géométrie spécifiée. |
| [from_binary(wkb)](#from_binary_wkb_15) | Crée une géométrie à partir de sa représentation Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_16) | Crée une géométrie à partir de sa représentation Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_17) | Crée une géométrie à partir de sa représentation Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_18) | Crée une géométrie à partir de sa représentation Well-Known Text. |
| [get_area()](#get_area__19) | Calcule la surface de cette géométrie. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_20) | Calcule une zone tampon autour de cette géométrie. |
| [get_centroid()](#get_centroid__21) | Calcule le centroïde de cette géométrie. |
| [get_convex_hull()](#get_convex_hull__22) | Calcule l'enveloppe convexe de cette géométrie. |
| [get_distance_to(other)](#get_distance_to_other_23) | Calcule la distance minimale entre cette géométrie et une géométrie spécifiée. |
| [get_extent()](#get_extent__24) | Calcule et renvoie l'étendue englobante de cette géométrie. |
| [get_length()](#get_length__25) | Calcule la longueur de cette géométrie. |
| [intersection(other)](#intersection_other_26) | Construit une intersection entre cette géométrie et une géométrie spécifiée. |
| [intersects(extent)](#intersects_extent_27) | Détermine si cette géométrie intersecte une étendue spécifiée. |
| [intersects(other)](#intersects_other_28) | Détermine si cette géométrie et une géométrie spécifiée s'intersectent. |
| [overlaps(other)](#overlaps_other_29) | Détermine si cette géométrie se chevauche avec une géométrie spécifiée. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_30) | Détermine si la matrice d'intersection DE-9IM de cette géométrie et d'une géométrie spécifiée correspond au modèle fourni. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__31) | Obtient les polygones représentés comme lignes de cette géométrie. |
| [round_m(digits)](#round_m_digits_32) | Arrondit la coordonnée M à un nombre spécifié de chiffres fractionnels. |
| [round_xy(digits)](#round_xy_digits_33) | Arrondit les coordonnées X et Y à un nombre spécifié de chiffres fractionnels. |
| [round_z(digits)](#round_z_digits_34) | Arrondit la coordonnée Z à un nombre spécifié de chiffres fractionnels. |
| set_empty() | Rend cette [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) vide. |
| [spatially_contains(other)](#spatially_contains_other_35) | Détermine si cette géométrie contient spatialement une géométrie spécifiée. |
| [spatially_equals(other)](#spatially_equals_other_36) | Détermine si cette géométrie est spatialement égale à une géométrie spécifiée. |
| [sym_difference(other)](#sym_difference_other_37) | Construit une différence symétrique entre cette géométrie et une géométrie spécifiée. |
| [to_editable()](#to_editable__38) | Obtient une copie modifiable de cette géométrie. |
| [to_linear_geometry()](#to_linear_geometry__39) | Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> par défaut. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_40) | Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> spécifiée. |
| [to_svg(extent)](#to_svg_extent_41) | Traduit cette géométrie en représentation Svg. |
| [touches(other)](#touches_other_42) | Détermine si cette géométrie et une géométrie spécifiée se touchent. |
| [union(other)](#union_other_43) | Unit cette géométrie et une géométrie spécifiée. |
| [union(other)](#union_other_44) | Unit cette géométrie et une géométrie spécifiée. |
| [within(extent)](#within_extent_45) | Détermine si cette géométrie se trouve à l'intérieur d'une étendue spécifiée. |
| [within(other)](#within_other_46) | Détermine si cette géométrie se trouve à l'intérieur d'une géométrie spécifiée. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/).

### Constructor: Point(other) {#Point_other_2}


```
 Point(other) 
```

Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | L'autre [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) dont copier les données. |

### Constructor: Point(x, y) {#Point_x_y_3}


```
 Point(x, y) 
```

Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |

### Constructor: Point(x, y, z) {#Point_x_y_z_4}


```
 Point(x, y, z) 
```

Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |
| z | double | La valeur pour la coordonnée Z. |

### Constructor: Point(x, y, z, m) {#Point_x_y_z_m_5}


```
 Point(x, y, z, m) 
```

Initialise une nouvelle instance de la classe [Point](/psd/python-net/aspose.gis.geometries/point/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | La valeur pour la coordonnée X. |
| y | double | La valeur pour la coordonnée Y. |
| z | double | La valeur pour la coordonnée Z. |
| m | double | La valeur pour la coordonnée M. |

### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Traduit cette géométrie en sa représentation Well-Known Binary.

**Returns**

| Type | Description |
| :- | :- |
| byte | Représentation Well-Known Binary de cette géométrie. |


### Method: as_binary(variant) {#as_binary_variant_2}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


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


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Traduit cette géométrie en sa représentation Well-Known Text.

**Returns**

| Type | Description |
| :- | :- |
| string | Représentation Well-Known Text de cette géométrie. |


### Method: as_text(variant) {#as_text_variant_7}


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


### Method: as_text(variant, format) {#as_text_variant_format_8}


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


### Method: clone() {#clone__9}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Le clone de cette instance |


### Method: covered_by(other) {#covered_by_other_10}


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


### Method: covers(other) {#covers_other_11}


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


### Method: crosses(other) {#crosses_other_12}


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


### Method: difference(other) {#difference_other_13}


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


### Method: disjoint(other) {#disjoint_other_14}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_15}


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


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_16}


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


### Method: from_text(wkt)  [static] {#from_text_wkt_17}


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


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_18}


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


### Method: get_area() {#get_area__19}


```
 get_area() 
```

Calcule la surface de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| double | L'aire de cette géométrie.<br/>            Somme des aires des éléments de cette géométrie si celle-ci est une [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_20}


```
 get_buffer(distance, quadrant_segments) 
```

Calcule une zone tampon autour de cette géométrie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| distance | double | La largeur de la zone tampon. |
| quadrant_segments | int | Nombre de segments utilisés pour approximer une courbure de 90 degrés.<br/>            Plus ce nombre est grand, meilleure est l'approximation des courbes.<br/>            La valeur par défaut est 30. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente tous les points situés à une distance spécifiée de<br/>            cette géométrie.<br/>            Le type du résultat est soit [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ou [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__21}


```
 get_centroid() 
```

Calcule le centroïde de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Le centroïde de cette géométrie. Si cette géométrie est vide, un point vide est renvoyé.<br/>            Le centroïde est égal au centroïde des géométries de plus haute dimension dans cette géométrie<br/>            (par ex. si des points et des lignes sont contenus dans la géométrie, seules les lignes contribuent au centroïde). |


### Method: get_convex_hull() {#get_convex_hull__22}


```
 get_convex_hull() 
```

Calcule l'enveloppe convexe de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui représente l'enveloppe convexe de cette géométrie.<br/>            Si cette géométrie n'a aucun point, le résultat est [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Si cette géométrie n'a qu'un seul point, le résultat est ce point.<br/>            Si cette géométrie n'a que deux points, le résultat est un [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) contenant les points.<br/>            Si cette géométrie a trois points ou plus, le résultat est un [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) qui représente une enveloppe convexe autour de tous les points de la géométrie. |


### Method: get_distance_to(other) {#get_distance_to_other_23}


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
| double | Si les deux géométries ne sont pas [Geometry.is_empty](/psd/python-net/aspose.gis.geometries/geometry/) - une distance entre les points les plus proches des géométries.<br/>            Si au moins une géométrie est vide, -1 est renvoyé. |


### Method: get_extent() {#get_extent__24}


```
 get_extent() 
```

Calcule et renvoie l'étendue englobante de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue englobante de cette géométrie. |


### Method: get_length() {#get_length__25}


```
 get_length() 
```

Calcule la longueur de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| double | La longueur de cette géométrie.<br/>            Périmètre si c'est un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Somme des longueurs des éléments de cette géométrie si celle-ci est une [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_26}


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


### Method: intersects(extent) {#intersects_extent_27}


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


### Method: intersects(other) {#intersects_other_28}


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


### Method: overlaps(other) {#overlaps_other_29}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_30}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__31}


```
 replace_polygons_by_lines() 
```

Obtient les polygones représentés comme lignes de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui ne possède pas de géométries polygonales. Les transformations suivantes sont appliquées :<br/>            <ul><br/>            <li> les [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) sont linéarisés<br/> (transformés en [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li> les [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) sont fusionnés en [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_32}


```
 round_m(digits) 
```

Arrondit la coordonnée M à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: round_xy(digits) {#round_xy_digits_33}


```
 round_xy(digits) 
```

Arrondit les coordonnées X et Y à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: round_z(digits) {#round_z_digits_34}


```
 round_z(digits) 
```

Arrondit la coordonnée Z à un nombre spécifié de chiffres fractionnels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| digits | int | Nombre de chiffres fractionnaires. |

### Method: spatially_contains(other) {#spatially_contains_other_35}


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


### Method: spatially_equals(other) {#spatially_equals_other_36}


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


### Method: sym_difference(other) {#sym_difference_other_37}


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


### Method: to_editable() {#to_editable__38}


```
 to_editable() 
```

Obtient une copie modifiable de cette géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.gis.geometries/point) | Une copie modifiable de cette géométrie. |


### Method: to_linear_geometry() {#to_linear_geometry__39}


```
 to_linear_geometry() 
```

Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> par défaut.

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui ne possède pas de géométries de courbe. C'est l'équivalent de <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) avec<br/>            la <c>tolerance</c> par défaut. La <c>tolerance</c> par défaut est définie par [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            de cette géométrie :<br/>            <ul><br/>            <li> Pour un SRS projeté, la tolérance est de 0,001 mètres (dans les unités du SRS) </li><br/>            <li> Pour un SRS géographique, la tolérance est de <c>1e-5</c> degrés (dans les unités du SRS) </li><br/>            <li> Pour un SRS inconnu, la tolérance est de <c>1e-5</c> </li><br/>            </ul><br/>            Pour plus de détails sur les transformations appliquées, consultez la spécification <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_40}


```
 to_linear_geometry(tolerance) 
```

Obtient une version approximative ou équivalente sans courbe de cette géométrie en utilisant la <c>tolerance</c> spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tolerance | double | La <c>tolerance</c> à utiliser. Le résultat est garanti d'être inférieur à <c>tolerance</c> de la géométrie courbée,<br/>            sauf si le nombre de points nécessaires pour linéariser la géométrie dépasse le maximum par quadrant<br/>            qui est actuellement égal à 10000 points. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Une géométrie qui ne possède pas de géométries de courbe. Les transformations suivantes sont appliquées :<br/>            <ul><br/>            <li> Les [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) sont linéarisés<br/>            (transformés en [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) avec la <paramref name=\"tolerance\" /> spécifiée) </li><br/>            <li> Les [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) sont joints en <c>LineString</c>s </li><br/>            <li> Les [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) sont transformés en [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> Les [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) sont transformés en [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> Les [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/) sont transformés en [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            </ul><br/>            En conséquence, [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) de la géométrie de sortie est <see langword=\"false\" />. |


### Method: to_svg(extent) {#to_svg_extent_41}


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


### Method: touches(other) {#touches_other_42}


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


### Method: union(other) {#union_other_43}


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


### Method: union(other) {#union_other_44}


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


### Method: within(extent) {#within_extent_45}


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


### Method: within(other) {#within_other_46}


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


