---
title: "Classe Extent"
type: docs
weight: 820
url: /fr/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Extent()](#Extent__1) | Crée une nouvelle instance. |
| [Extent(srs)](#Extent_srs_2) | Crée une nouvelle instance. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Centre de l'étendue. |
| hauteur | double | r | Hauteur de l'étendue. |
| is_valid | bool | r | Détermine si cet [Extent](/psd/python-net/aspose.gis/extent/) est valide. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associé à cette étendue.<br/>            Peut être <see langword="null" /> si [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) est inconnu.<br/>            Utilisez Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            afin de transformer l'étendue entre différents systèmes de référence spatiale. |
| width | double | r | Largeur de l'étendue. |
| x_max | double | r/w | Valeur maximale de la coordonnée X. |
| x_min | double | r/w | Valeur minimale de la coordonnée X. |
| y_max | double | r/w | Valeur maximale de la coordonnée Y. |
| y_min | double | r/w | Valeur minimale de la coordonnée Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |
| [contains(extent)](#contains_extent_2) | Détermine si cette étendue contient l'argument. |
| [contains(geometry)](#contains_geometry_3) | Détermine si cette étendue contient l'argument. |
| [contains(x, y)](#contains_x_y_4) | Détermine si cette étendue contient une coordonnée définie par les arguments. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Renvoie une nouvelle étendue dans le [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) spécifié qui contient cette étendue. |
| [grow(extent)](#grow_extent_6) | Agrandit cette étendue afin qu'elle inclue l'argument. |
| [grow(x, y)](#grow_x_y_7) | Agrandit cette étendue afin qu'elle inclue le point spécifié. |
| [grow_x(value)](#grow_x_value_8) | Agrandit cette étendue le long de l'axe X afin qu'elle inclue la valeur spécifiée. |
| [grow_y(value)](#grow_y_value_9) | Agrandit cette étendue le long de l'axe Y afin qu'elle inclue la valeur spécifiée. |
| [intersects(extent)](#intersects_extent_10) | Détermine si cette étendue intersecte l'argument. |
| [intersects(geometry)](#intersects_geometry_11) | Détermine si cette étendue intersecte l'argument. |
| normalize() | Échange [Extent.x_min](/psd/python-net/aspose.gis/extent/) avec [Extent.x_max](/psd/python-net/aspose.gis/extent/) si [Extent.width](/psd/python-net/aspose.gis/extent/) est négatif et<br/> [Extent.y_min](/psd/python-net/aspose.gis/extent/) avec [Extent.y_max](/psd/python-net/aspose.gis/extent/) si [Extent.height](/psd/python-net/aspose.gis/extent/) est négatif. |
| [to_polygon()](#to_polygon__12) | Convertit cette étendue en un polygone rectangulaire qui la représente. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Crée une nouvelle instance.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associé à cette étendue.<br/> Peut être <see langword=\"null\" /> pour indiquer que le SRS est inconnu. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x_min | double | Valeur minimale de X. |
| y_min | double | Valeur minimale de Y. |
| x_max | double | Valeur maximale de X. |
| y_max | double | Valeur maximale de Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associé à cette étendue.<br/> Peut être <see langword=\"null\" /> pour indiquer que le SRS est inconnu. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Clone de cette instance. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Détermine si cette étendue contient l'argument.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Une autre étendue. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur indiquant si cette étendue contient l'argument. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Détermine si cette étendue contient l'argument.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Une géométrie à tester pour la contenance. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur indiquant si cette étendue contient l'argument. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Détermine si cette étendue contient une coordonnée définie par les arguments.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | X de la coordonnée. |
| y | double | Y de la coordonnée. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur indiquant si la coordonnée est à l'intérieur de la boîte englobante. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Renvoie une nouvelle étendue dans le [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) spécifié qui contient cette étendue.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) vers lequel transformer. |

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Le résultat de la transformation de cette étendue vers le SRS spécifié. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Agrandit cette étendue afin qu'elle inclue l'argument.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Autre étendue. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Agrandit cette étendue afin qu'elle inclue le point spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | Coordonnée X à inclure. |
| y | double | Coordonnée Y à inclure. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Agrandit cette étendue le long de l'axe X afin qu'elle inclue la valeur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | double | Valeur à inclure. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Agrandit cette étendue le long de l'axe Y afin qu'elle inclue la valeur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | double | Valeur à inclure. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Détermine si cette étendue intersecte l'argument.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Une autre étendue. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur, indiquant si cette étendue intersecte l'argument. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Détermine si cette étendue intersecte l'argument.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Une géométrie pour tester l'intersection |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur, indiquant si cette étendue intersecte l'argument. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Convertit cette étendue en un polygone rectangulaire qui la représente.

**Returns**

| Type | Description |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) rectangulaire qui représente cette étendue. Pour les étendues invalides<br/>            un polygone vide est renvoyé. |


