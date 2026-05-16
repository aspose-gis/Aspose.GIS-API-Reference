---
title: "Classe Extent"
type: docs
weight: 820
url: /it/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Extent()](#Extent__1) | Crea una nuova istanza. |
| [Extent(srs)](#Extent_srs_2) | Crea una nuova istanza. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Centro dell'extent. |
| altezza | double | r | Altezza dell'extent. |
| is_valid | bool | r | Determina se questo [Extent](/psd/python-net/aspose.gis/extent/) è valido. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associato a questo extent.<br/>            Può essere <see langword="null" /> se [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) è sconosciuto.<br/>            Usa Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            per trasformare l'extent tra diversi sistemi di riferimento spaziale. |
| width | double | r | Larghezza dell'extent. |
| x_max | double | r/w | Valore massimo della coordinata X. |
| x_min | double | r/w | Valore minimo della coordinata X. |
| y_max | double | r/w | Valore massimo della coordinata Y. |
| y_min | double | r/w | Valore minimo della coordinata Y. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |
| [contains(extent)](#contains_extent_2) | Determina se questa estensione contiene l'argomento. |
| [contains(geometry)](#contains_geometry_3) | Determina se questa estensione contiene l'argomento. |
| [contains(x, y)](#contains_x_y_4) | Determina se questa estensione contiene una coordinata definita dagli argomenti. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Restituisce una nuova estensione nel [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) specificato che contiene questa estensione. |
| [grow(extent)](#grow_extent_6) | Espande questa estensione in modo che includa l'argomento. |
| [grow(x, y)](#grow_x_y_7) | Espande questa estensione in modo che includa il punto specificato. |
| [grow_x(value)](#grow_x_value_8) | Espande questa estensione lungo l'asse X in modo che includa il valore specificato. |
| [grow_y(value)](#grow_y_value_9) | Espande questa estensione lungo l'asse Y in modo che includa il valore specificato. |
| [intersects(extent)](#intersects_extent_10) | Determina se questa estensione interseca l'argomento. |
| [intersects(geometry)](#intersects_geometry_11) | Determina se questa estensione interseca l'argomento. |
| normalize() | Scambia [Extent.x_min](/psd/python-net/aspose.gis/extent/) con [Extent.x_max](/psd/python-net/aspose.gis/extent/) se [Extent.width](/psd/python-net/aspose.gis/extent/) è negativo e<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) con [Extent.y_max](/psd/python-net/aspose.gis/extent/) se [Extent.height](/psd/python-net/aspose.gis/extent/) è negativo. |
| [to_polygon()](#to_polygon__12) | Converte questa estensione in un poligono rettangolare che la rappresenta. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Crea una nuova istanza.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associato a questa estensione.<br/>            Può essere <see langword="null" /> per indicare che il SRS è sconosciuto. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x_min | double | Valore minimo X. |
| y_min | double | Valore minimo Y. |
| x_max | double | Valore massimo X. |
| y_max | double | Valore massimo Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associato a questa estensione.<br/>            Può essere <see langword="null" /> per indicare che il SRS è sconosciuto. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Clone di questa istanza. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Determina se questa estensione contiene l'argomento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Un'altra estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore, che indica se questa estensione contiene l'argomento. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Determina se questa estensione contiene l'argomento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Una geometria da testare per il contenimento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore, che indica se questa estensione contiene l'argomento. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina se questa estensione contiene una coordinata definita dagli argomenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | double | X della coordinata. |
| y | double | Y della coordinata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore, che indica se la coordinata è all'interno del riquadro delimitante. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Restituisce una nuova estensione nel [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) specificato che contiene questa estensione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) in cui trasformare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Il risultato della trasformazione di questa estensione nel SRS specificato. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Espande questa estensione in modo che includa l'argomento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Altra estensione. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Espande questa estensione in modo che includa il punto specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | double | Coordinata X da includere. |
| y | double | Coordinata Y da includere. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Espande questa estensione lungo l'asse X in modo che includa il valore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | double | Valore da includere. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Espande questa estensione lungo l'asse Y in modo che includa il valore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valore | double | Valore da includere. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Determina se questa estensione interseca l'argomento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Un'altra estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore, che indica se questa estensione interseca l'argomento. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Determina se questa estensione interseca l'argomento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Una geometria da testare per l'intersezione |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore, che indica se questa estensione interseca l'argomento. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Converte questa estensione in un poligono rettangolare che la rappresenta.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) rettangolare che rappresenta questa estensione. Per estensioni non valide<br/>            viene restituito un poligono vuoto. |


