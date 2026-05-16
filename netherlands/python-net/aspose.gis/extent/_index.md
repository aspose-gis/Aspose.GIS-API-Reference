---
title: "Extent-klasse"
type: docs
weight: 820
url: /nl/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Extent()](#Extent__1) | Creëert een nieuw exemplaar. |
| [Extent(srs)](#Extent_srs_2) | Creëert een nieuw exemplaar. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Middelpunt van de extent. |
| hoogte | double | r | Hoogte van de extent. |
| is_valid | bool | r | Bepaalt of deze [Extent](/psd/python-net/aspose.gis/extent/) geldig is. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) geassocieerd met deze extent.<br/>            Kan <see langword="null" /> zijn als [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) onbekend is.<br/>            Gebruik Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            om de extent te transformeren tussen verschillende ruimtelijke referentiesystemen. |
| width | double | r | Breedte van de extent. |
| x_max | double | r/w | Maximumwaarde van de X-coördinaat. |
| x_min | double | r/w | Minimumwaarde van de X-coördinaat. |
| y_max | double | r/w | Maximumwaarde van de Y-coördinaat. |
| y_min | double | r/w | Minimumwaarde van de Y-coördinaat. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |
| [contains(extent)](#contains_extent_2) | Bepaalt of deze extent het argument bevat. |
| [contains(geometry)](#contains_geometry_3) | Bepaalt of deze extent het argument bevat. |
| [contains(x, y)](#contains_x_y_4) | Bepaalt of deze extent een coördinaat bevat dat door de argumenten is gedefinieerd. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Retourneert een nieuwe extent in de opgegeven [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) die deze extent bevat. |
| [grow(extent)](#grow_extent_6) | Vergroot deze extent zodat het argument wordt opgenomen. |
| [grow(x, y)](#grow_x_y_7) | Vergroot deze extent zodat het opgegeven punt wordt opgenomen. |
| [grow_x(value)](#grow_x_value_8) | Vergroot deze extent langs de X-as zodat de opgegeven waarde wordt opgenomen. |
| [grow_y(value)](#grow_y_value_9) | Vergroot deze extent langs de Y-as zodat de opgegeven waarde wordt opgenomen. |
| [intersects(extent)](#intersects_extent_10) | Bepaalt of deze extent intersecteert met het argument. |
| [intersects(geometry)](#intersects_geometry_11) | Bepaalt of deze extent intersecteert met het argument. |
| normalize() | Wisselt [Extent.x_min](/psd/python-net/aspose.gis/extent/) met [Extent.x_max](/psd/python-net/aspose.gis/extent/) als [Extent.width](/psd/python-net/aspose.gis/extent/) negatief is en<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) met [Extent.y_max](/psd/python-net/aspose.gis/extent/) als [Extent.height](/psd/python-net/aspose.gis/extent/) negatief is. |
| [to_polygon()](#to_polygon__12) | Converteert deze extent naar een rechthoekig polygoon dat het representeert. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Creëert een nieuw exemplaar.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) geassocieerd met deze extent.<br/>            Kan <see langword="null" /> zijn om aan te geven dat de SRS onbekend is. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x_min | double | Minimum X-waarde. |
| y_min | double | Minimum Y-waarde. |
| x_max | double | Maximum X-waarde. |
| y_max | double | Maximum Y-waarde. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) geassocieerd met deze extent.<br/>            Kan <see langword="null" /> zijn om aan te geven dat de SRS onbekend is. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Kloon van deze instantie. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Bepaalt of deze extent het argument bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Een andere extent. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waarde die aangeeft of deze extent het argument bevat. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Bepaalt of deze extent het argument bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Een geometrie om op containment te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waarde die aangeeft of deze extent het argument bevat. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bepaalt of deze extent een coördinaat bevat dat door de argumenten is gedefinieerd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | double | X van de coördinaat. |
| y | double | Y van de coördinaat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waarde die aangeeft of de coördinaat zich binnen de omsluitende rechthoek bevindt. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Retourneert een nieuwe extent in de opgegeven [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) die deze extent bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) om naartoe te transformeren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Het resultaat van de transformatie van dit gebied naar het opgegeven SRS. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Vergroot deze extent zodat het argument wordt opgenomen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Andere omvang. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Vergroot deze extent zodat het opgegeven punt wordt opgenomen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | double | X-coördinaat om op te nemen. |
| y | double | Y-coördinaat om op te nemen. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Vergroot deze extent langs de X-as zodat de opgegeven waarde wordt opgenomen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| waarde | double | Waarde om op te nemen. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Vergroot deze extent langs de Y-as zodat de opgegeven waarde wordt opgenomen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| waarde | double | Waarde om op te nemen. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Bepaalt of deze extent intersecteert met het argument.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Een andere extent. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waarde die aangeeft of deze omvang intersecteert met het argument. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Bepaalt of deze extent intersecteert met het argument.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Een geometrie om op intersectie te testen |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Waarde die aangeeft of deze omvang intersecteert met het argument. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Converteert deze extent naar een rechthoekig polygoon dat het representeert.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Een rechthoekige [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) die deze omvang vertegenwoordigt. Voor ongeldige omvang<br/>            wordt een lege polygon geretourneerd. |


