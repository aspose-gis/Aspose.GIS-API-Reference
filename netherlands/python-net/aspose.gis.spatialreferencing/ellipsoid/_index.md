---
title: "Ellipsoïdeklasse"
type: docs
weight: 40
url: /nl/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Maakt een nieuwe ellipsoïde aan. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy-ellipsoïde. |
| epsg_code | int | r | Als de identifier van dit object een EPSG-identificatie is - retourneer de code. Anders - retourneer -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980-ellipsoïde. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifier van dit identificeerbare object. |
| inverse_flattening | double | r | Inverse afplatting van de ellipsoïde. 0 als dit een bol is. |
| is_sphere | bool | r | Detecteert of deze ellipsoïde een bol is. |
| is_valid | bool | r | Detecteert of de ellipsoïde geldig is: de semi‑grote as is groter dan 0 en de inverse afplatting is positief of gelijk aan 0. |
| naam | string | r | Naam van dit object. |
| semi_major_axis | double | r | Semi‑grote as van de ellipsoïde. |
| semi_minor_axis | double | r | Semi‑kleine as van de ellipsoïde. Gelijk aan de semi‑grote as als dit een bol is. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72-ellipsoïde. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84-ellipsoïde. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Bepaalt of twee ellipsoïden gelijk zijn.<br/>            Als ellipsoïde A gelijk is aan ellipsoïde B, dan hebben ze dezelfde semi‑grote as en inverse afplatting. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bepaalt of twee ellipsoïden gelijk zijn.<br/>            Als ellipsoïde A gelijk is aan ellipsoïde B, dan hebben ze dezelfde semi‑grote as en inverse afplatting. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Maakt een nieuwe ellipsoïde aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de ellipsoïde. |
| semi_major_axis | double | Semi‑grote as van de ellipsoïde. |
| inverse_flattening | double | Inverse afplatting van de ellipsoïde. Moet 0 zijn om een sferoïde te creëren. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatie van de ellipsoïde. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Bepaalt of twee ellipsoïden gelijk zijn.<br/>            Als ellipsoïde A gelijk is aan ellipsoïde B, dan hebben ze dezelfde semi‑grote as en inverse afplatting.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Eerste ellipsoïde. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Tweede ellipsoïde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool‑waarde, die aangeeft of twee ellipsoïden gelijk zijn. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bepaalt of twee ellipsoïden gelijk zijn.<br/>            Als ellipsoïde A gelijk is aan ellipsoïde B, dan hebben ze dezelfde semi‑grote as en inverse afplatting.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Andere ellipsoïde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool‑waarde, die aangeeft of twee ellipsoïden gelijk zijn. |


