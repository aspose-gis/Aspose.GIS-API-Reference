---
title: "Classe Ellipsoid"
type: docs
weight: 40
url: /fr/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Crée un nouvel Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde d'Airy. |
| epsg_code | int | r | Si l’identifiant de cet objet est un identifiant EPSG, renvoie son code. Sinon, renvoie -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifiant de cet objet identifiable. |
| inverse_flattening | double | r | Aplatissement inverse de l'ellipsoïde. 0 si c'est une sphère. |
| is_sphere | bool | r | Détecte si cet ellipsoïde est une sphère. |
| is_valid | bool | r | Détecte si l'ellipsoïde est valide : son axe semi‑majeur est supérieur à 0 et l'aplatissement inverse est positif ou égal à 0. |
| nom | string | r | Nom de cet objet. |
| semi_major_axis | double | r | Axe semi‑majeur de l'ellipsoïde. |
| semi_minor_axis | double | r | Axe semi‑mineur de l'ellipsoïde. Égal à l'axe semi‑majeur si c'est une sphère. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde WGS 84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Détermine si deux ellipsoïdes sont équivalents.<br/>            Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même axe semi‑majeur et le même aplatissement inverse. |
| [is_equivalent(other)](#is_equivalent_other_2) | Détermine si deux ellipsoïdes sont équivalents.<br/>            Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même axe semi‑majeur et le même aplatissement inverse. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Crée un nouvel Ellipsoid.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de l'ellipsoïde. |
| semi_major_axis | double | Axe semi‑majeur de l'ellipsoïde. |
| inverse_flattening | double | Aplatissement inverse de l'ellipsoïde. Doit être 0 pour créer un sphéroïde. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant de l'ellipsoïde. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Détermine si deux ellipsoïdes sont équivalents.<br/>            Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même axe semi‑majeur et le même aplatissement inverse.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Premier ellipsoïde. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Deuxième ellipsoïde. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur booléenne, indiquant si deux ellipsoïdes sont équivalents. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Détermine si deux ellipsoïdes sont équivalents.<br/>            Si l'ellipsoïde A est équivalent à l'ellipsoïde B, alors ils ont le même axe semi‑majeur et le même aplatissement inverse.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Autre ellipsoïde. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur booléenne, indiquant si deux ellipsoïdes sont équivalents. |


