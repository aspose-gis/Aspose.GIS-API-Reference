---
title: "Extent-Klasse"
type: docs
weight: 820
url: /de/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Extent()](#Extent__1) | Erstellt eine neue Instanz. |
| [Extent(srs)](#Extent_srs_2) | Erstellt eine neue Instanz. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Mitte des Extents. |
| Höhe | double | r | Höhe des Extents. |
| is_valid | bool | r | Bestimmt, ob dieses [Extent](/psd/python-net/aspose.gis/extent/) gültig ist. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) assoziiert mit diesem Extent.<br/>            Kann <see langword="null" /> sein, wenn [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) unbekannt ist.<br/>            Verwenden Sie Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            um den Extent zwischen unterschiedlichen räumlichen Bezugssystemen zu transformieren. |
| width | double | r | Breite des Extents. |
| x_max | double | r/w | Maximalwert der X-Koordinate. |
| x_min | double | r/w | Minimalwert der X-Koordinate. |
| y_max | double | r/w | Maximalwert der Y‑Koordinate. |
| y_min | double | r/w | Minimalwert der Y‑Koordinate. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |
| [contains(extent)](#contains_extent_2) | Bestimmt, ob dieser Ausschnitt das Argument enthält. |
| [contains(geometry)](#contains_geometry_3) | Bestimmt, ob dieser Ausschnitt das Argument enthält. |
| [contains(x, y)](#contains_x_y_4) | Bestimmt, ob dieser Ausschnitt eine durch die Argumente definierte Koordinate enthält. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Gibt einen neuen Ausschnitt im angegebenen [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) zurück, der diesen Ausschnitt enthält. |
| [grow(extent)](#grow_extent_6) | Erweitert diesen Ausschnitt, sodass er das Argument einschließt. |
| [grow(x, y)](#grow_x_y_7) | Erweitert diesen Ausschnitt, sodass er den angegebenen Punkt einschließt. |
| [grow_x(value)](#grow_x_value_8) | Erweitert diesen Ausschnitt entlang der X‑Achse, sodass er den angegebenen Wert einschließt. |
| [grow_y(value)](#grow_y_value_9) | Erweitert diesen Ausschnitt entlang der Y‑Achse, sodass er den angegebenen Wert einschließt. |
| [intersects(extent)](#intersects_extent_10) | Bestimmt, ob dieser Ausschnitt mit dem Argument schneidet. |
| [intersects(geometry)](#intersects_geometry_11) | Bestimmt, ob dieser Ausschnitt mit dem Argument schneidet. |
| normalize() | Vertauscht [Extent.x_min](/psd/python-net/aspose.gis/extent/) mit [Extent.x_max](/psd/python-net/aspose.gis/extent/), wenn [Extent.width](/psd/python-net/aspose.gis/extent/) negativ ist und<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) mit [Extent.y_max](/psd/python-net/aspose.gis/extent/) wenn [Extent.height](/psd/python-net/aspose.gis/extent/) negativ ist. |
| [to_polygon()](#to_polygon__12) | Konvertiert diesen Ausschnitt in ein rechteckiges Polygon, das ihn darstellt. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Erstellt eine neue Instanz.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) ist mit diesem Ausschnitt verknüpft.<br/>            Kann <see langword=\"null\" /> sein, um anzuzeigen, dass das SRS unbekannt ist. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x_min | double | Minimaler X‑Wert. |
| y_min | double | Minimaler Y‑Wert. |
| x_max | double | Maximaler X‑Wert. |
| y_max | double | Maximaler Y‑Wert. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) ist mit diesem Ausschnitt verknüpft.<br/>            Kann <see langword=\"null\" /> sein, um anzuzeigen, dass das SRS unbekannt ist. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Klon dieser Instanz. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Bestimmt, ob dieser Ausschnitt das Argument enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ein weiterer Ausschnitt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wert, der angibt, ob dieser Ausschnitt das Argument enthält. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Bestimmt, ob dieser Ausschnitt das Argument enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Eine Geometrie zum Testen der Einschließung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wert, der angibt, ob dieser Ausschnitt das Argument enthält. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bestimmt, ob dieser Ausschnitt eine durch die Argumente definierte Koordinate enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double | X der Koordinate. |
| y | double | Y der Koordinate. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wert, der angibt, ob die Koordinate innerhalb der Begrenzungsbox liegt. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Gibt einen neuen Ausschnitt im angegebenen [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) zurück, der diesen Ausschnitt enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) zum Transformieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Das Ergebnis der Transformation dieser Ausdehnung in das angegebene SRS. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Erweitert diesen Ausschnitt, sodass er das Argument einschließt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Andere Ausdehnung. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Erweitert diesen Ausschnitt, sodass er den angegebenen Punkt einschließt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double | X‑Koordinate zum Einschließen. |
| y | double | Y‑Koordinate zum Einschließen. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Erweitert diesen Ausschnitt entlang der X‑Achse, sodass er den angegebenen Wert einschließt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | double | Wert zum Einschließen. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Erweitert diesen Ausschnitt entlang der Y‑Achse, sodass er den angegebenen Wert einschließt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | double | Wert zum Einschließen. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Bestimmt, ob dieser Ausschnitt mit dem Argument schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ein weiterer Ausschnitt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wert, der angibt, ob diese Ausdehnung mit dem Argument überschneidet. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Bestimmt, ob dieser Ausschnitt mit dem Argument schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Eine Geometrie zum Prüfen einer Schnittmenge. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wert, der angibt, ob diese Ausdehnung mit dem Argument überschneidet. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Konvertiert diesen Ausschnitt in ein rechteckiges Polygon, das ihn darstellt.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Ein rechteckiges [Polygon](/psd/python-net/aspose.gis.geometries/polygon/), das diese Ausdehnung darstellt. Für ungültige Ausdehnungen<br/>            wird ein leeres Polygon zurückgegeben. |


