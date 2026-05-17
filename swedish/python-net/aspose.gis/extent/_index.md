---
title: "Extent-klass"
type: docs
weight: 820
url: /sv/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Extent()](#Extent__1) | Skapar ny instans. |
| [Extent(srs)](#Extent_srs_2) | Skapar ny instans. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Centrum för extent. |
| höjd | double | r | Höjd för extent. |
| is_valid | bool | r | Bestämmer om denna [Extent](/psd/python-net/aspose.gis/extent/) är giltig. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associerad med detta extent.<br/>            Kan vara <see langword=\"null\" /> om [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) är okänd.<br/>            Använd Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            för att transformera extent mellan olika rumsliga referenssystem. |
| bredd | double | r | Bredd för extent. |
| x_max | double | läs/skriv | Maximalt värde för X‑koordinaten. |
| x_min | double | läs/skriv | Minimalt värde för X‑koordinaten. |
| y_max | double | läs/skriv | Maximalt värde för Y-koordinaten. |
| y_min | double | läs/skriv | Minimalt värde för Y-koordinaten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar detta objekt. |
| [contains(extent)](#contains_extent_2) | Bestämmer om detta omfång innehåller argumentet. |
| [contains(geometry)](#contains_geometry_3) | Bestämmer om detta omfång innehåller argumentet. |
| [contains(x, y)](#contains_x_y_4) | Bestämmer om detta omfång innehåller en koordinat som definieras av argumenten. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Returnerar ett nytt omfång i angivet [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) som innehåller detta omfång. |
| [grow(extent)](#grow_extent_6) | Utökar detta omfång så att det inkluderar argumentet. |
| [grow(x, y)](#grow_x_y_7) | Utökar detta omfång så att det inkluderar den angivna punkten. |
| [grow_x(value)](#grow_x_value_8) | Utökar detta omfång längs X-axeln så att det inkluderar det angivna värdet. |
| [grow_y(value)](#grow_y_value_9) | Utökar detta omfång längs Y-axeln så att det inkluderar det angivna värdet. |
| [intersects(extent)](#intersects_extent_10) | Bestämmer om detta omfång skär med argumentet. |
| [intersects(geometry)](#intersects_geometry_11) | Bestämmer om detta omfång skär med argumentet. |
| normalize() | Byter [Extent.x_min](/psd/python-net/aspose.gis/extent/) med [Extent.x_max](/psd/python-net/aspose.gis/extent/) om [Extent.width](/psd/python-net/aspose.gis/extent/) är negativt och<br/> [Extent.y_min](/psd/python-net/aspose.gis/extent/) med [Extent.y_max](/psd/python-net/aspose.gis/extent/) om [Extent.height](/psd/python-net/aspose.gis/extent/) är negativt. |
| [to_polygon()](#to_polygon__12) | Konverterar detta omfång till en rektangulär polygon som representerar det. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Skapar ny instans.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associerad med detta omfång.<br/>            Kan vara <see langword="null" /> för att indikera att SRS är okänt. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x_min | double | Minimalt X-värde. |
| y_min | double | Minimalt Y-värde. |
| x_max | double | Maximalt X-värde. |
| y_max | double | Maximalt Y-värde. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) associerad med detta omfång.<br/>            Kan vara <see langword="null" /> för att indikera att SRS är okänt. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Kopia av detta objekt. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Bestämmer om detta omfång innehåller argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ett annat omfång. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Värde som indikerar om detta omfång innehåller argumentet. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Bestämmer om detta omfång innehåller argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | En geometri för att testa innehåll. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Värde som indikerar om detta omfång innehåller argumentet. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bestämmer om detta omfång innehåller en koordinat som definieras av argumenten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | double | X för koordinaten. |
| y | double | Y för koordinaten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Värde som indikerar om koordinaten är inom begränsningsrutan. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Returnerar ett nytt omfång i angivet [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) som innehåller detta omfång.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) att transformera till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Resultatet av transformation av detta område till den specificerade SRS. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Utökar detta omfång så att det inkluderar argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Annat område. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Utökar detta omfång så att det inkluderar den angivna punkten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | double | X-koordinat att inkludera. |
| y | double | Y-koordinat att inkludera. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Utökar detta omfång längs X-axeln så att det inkluderar det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | double | Värde att inkludera. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Utökar detta omfång längs Y-axeln så att det inkluderar det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | double | Värde att inkludera. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Bestämmer om detta omfång skär med argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ett annat omfång. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Värde som indikerar om detta område skär med argumentet. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Bestämmer om detta omfång skär med argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | En geometri för att testa skärning |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Värde som indikerar om detta område skär med argumentet. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Konverterar detta omfång till en rektangulär polygon som representerar det.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | En rektangulär [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) som representerar detta område. För ogiltiga områden<br/>            returneras en tom polygon. |


