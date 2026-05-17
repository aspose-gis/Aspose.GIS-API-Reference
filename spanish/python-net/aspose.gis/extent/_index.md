---
title: "Clase Extent"
type: docs
weight: 820
url: /es/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Extent()](#Extent__1) | Crea una nueva instancia. |
| [Extent(srs)](#Extent_srs_2) | Crea una nueva instancia. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Centro de la extensión. |
| altura | double | r | Altura de la extensión. |
| is_valid | bool | r | Determina si este [Extent](/psd/python-net/aspose.gis/extent/) es válido. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) asociado con esta extensión.<br/>            Puede ser <see langword="null" /> si [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) es desconocido.<br/>            Utilice Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            para transformar la extensión entre diferentes sistemas de referencia espacial. |
| width | double | r | Ancho de la extensión. |
| x_max | double | r/w | Valor máximo de la coordenada X. |
| x_min | double | r/w | Valor mínimo de la coordenada X. |
| y_max | double | r/w | Valor máximo de la coordenada Y. |
| y_min | double | r/w | Valor mínimo de la coordenada Y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |
| [contains(extent)](#contains_extent_2) | Determina si esta extensión contiene el argumento. |
| [contains(geometry)](#contains_geometry_3) | Determina si esta extensión contiene el argumento. |
| [contains(x, y)](#contains_x_y_4) | Determina si esta extensión contiene una coordenada definida por los argumentos. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Devuelve una nueva extensión en el [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) especificado que contiene esta extensión. |
| [grow(extent)](#grow_extent_6) | Amplía esta extensión para que incluya el argumento. |
| [grow(x, y)](#grow_x_y_7) | Amplía esta extensión para que incluya el punto especificado. |
| [grow_x(value)](#grow_x_value_8) | Amplía esta extensión a lo largo del eje X para que incluya el valor especificado. |
| [grow_y(value)](#grow_y_value_9) | Amplía esta extensión a lo largo del eje Y para que incluya el valor especificado. |
| [intersects(extent)](#intersects_extent_10) | Determina si esta extensión intersecta con el argumento. |
| [intersects(geometry)](#intersects_geometry_11) | Determina si esta extensión intersecta con el argumento. |
| normalize() | Intercambia [Extent.x_min](/psd/python-net/aspose.gis/extent/) con [Extent.x_max](/psd/python-net/aspose.gis/extent/) si [Extent.width](/psd/python-net/aspose.gis/extent/) es negativo y<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) con [Extent.y_max](/psd/python-net/aspose.gis/extent/) si [Extent.height](/psd/python-net/aspose.gis/extent/) es negativo. |
| [to_polygon()](#to_polygon__12) | Convierte esta extensión en un polígono rectangular que la representa. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Crea una nueva instancia.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) asociado con esta extensión.<br/>            Puede ser <see langword="null" /> para indicar que el SRS es desconocido. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x_min | double | Valor mínimo de X. |
| y_min | double | Valor mínimo de Y. |
| x_max | double | Valor máximo de X. |
| y_max | double | Valor máximo de Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) asociado con esta extensión.<br/>            Puede ser <see langword="null" /> para indicar que el SRS es desconocido. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Clon de esta instancia. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Determina si esta extensión contiene el argumento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Otra extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor que indica si esta extensión contiene el argumento. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Determina si esta extensión contiene el argumento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Una geometría para probar la contención. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor que indica si esta extensión contiene el argumento. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determina si esta extensión contiene una coordenada definida por los argumentos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | double | X de la coordenada. |
| y | double | Y de la coordenada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor que indica si la coordenada está dentro del cuadro delimitador. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Devuelve una nueva extensión en el [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) especificado que contiene esta extensión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) al que transformar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | El resultado de transformar esta extensión al SRS especificado. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Amplía esta extensión para que incluya el argumento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Otra extensión. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Amplía esta extensión para que incluya el punto especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | double | Coordenada X a incluir. |
| y | double | Coordenada Y a incluir. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Amplía esta extensión a lo largo del eje X para que incluya el valor especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | double | Valor a incluir. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Amplía esta extensión a lo largo del eje Y para que incluya el valor especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | double | Valor a incluir. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Determina si esta extensión intersecta con el argumento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Otra extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor, que indica si esta extensión intersecta con el argumento. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Determina si esta extensión intersecta con el argumento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Una geometría para probar la intersección |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor, que indica si esta extensión intersecta con el argumento. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Convierte esta extensión en un polígono rectangular que la representa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Un [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) rectangular que representa esta extensión. Para extensiones inválidas<br/>            se devuelve un polígono vacío. |


