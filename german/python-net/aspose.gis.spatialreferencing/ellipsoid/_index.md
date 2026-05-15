---
title: "Ellipsoidklasse"
type: docs
weight: 40
url: /de/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Erstellt einen neuen Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy-Ellipsoid. |
| epsg_code | int | r | Wenn der Bezeichner dieses Objekts ein EPSG‑Bezeichner ist – geben Sie dessen Code zurück. Andernfalls - geben Sie -1 zurück. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS‑1980‑Ellipsoid. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bezeichner dieses identifizierbaren Objekts. |
| inverse_flattening | double | r | Inverse Abflachung des Ellipsoids. 0, wenn dies eine Kugel ist. |
| is_sphere | bool | r | Ermittelt, ob dieses Ellipsoid eine Kugel ist. |
| is_valid | bool | r | Ermittelt, ob das Ellipsoid gültig ist: seine Halbachse ist größer als 0 und die inverse Abflachung ist positiv oder gleich 0. |
| Name | string | r | Name dieses Objekts. |
| semi_major_axis | double | r | Halbachse des Ellipsoids. |
| semi_minor_axis | double | r | Kleinere Halbachse des Ellipsoids. Gleich der Halbachse, wenn dies eine Kugel ist. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS‑72‑Ellipsoid. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS‑84‑Ellipsoid. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Bestimmt, ob zwei Ellipsoide äquivalent sind.<br/>            Wenn Ellipsoid A äquivalent zu Ellipsoid B ist, haben sie dieselbe Halbachse und inverse Abflachung. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestimmt, ob zwei Ellipsoide äquivalent sind.<br/>            Wenn Ellipsoid A äquivalent zu Ellipsoid B ist, haben sie dieselbe Halbachse und inverse Abflachung. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Erstellt einen neuen Ellipsoid.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Ellipsoids. |
| semi_major_axis | double | Halbachse des Ellipsoids. |
| inverse_flattening | double | Inverse Abflachung des Ellipsoids. Sollte 0 sein, um ein Sphäroid zu erzeugen. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Bezeichner des Ellipsoids. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Bestimmt, ob zwei Ellipsoide äquivalent sind.<br/>            Wenn Ellipsoid A äquivalent zu Ellipsoid B ist, haben sie dieselbe Halbachse und inverse Abflachung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Erstes Ellipsoid. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Zweites Ellipsoid. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool-Wert, der angibt, ob zwei Ellipsoide äquivalent sind. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bestimmt, ob zwei Ellipsoide äquivalent sind.<br/>            Wenn Ellipsoid A äquivalent zu Ellipsoid B ist, haben sie dieselbe Halbachse und inverse Abflachung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Anderes Ellipsoid. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool-Wert, der angibt, ob zwei Ellipsoide äquivalent sind. |


