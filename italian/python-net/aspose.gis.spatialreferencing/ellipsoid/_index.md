---
title: "Classe Ellipsoid"
type: docs
weight: 40
url: /it/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Crea un nuovo Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellissoide Airy. |
| epsg_code | int | r | Se l'identificatore di questo oggetto è un identificatore EPSG, restituisce il suo codice. Altrimenti restituisce -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellissoide GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificatore di questo oggetto identificabile. |
| inverse_flattening | double | r | Appiattimento inverso dell'ellissoide. 0 se è una sfera. |
| is_sphere | bool | r | Rileva se questo ellissoide è una sfera. |
| is_valid | bool | r | Rileva se l'ellissoide è valido: il suo semiasse maggiore è maggiore di 0 e l'appiattimento inverso è positivo o uguale a 0. |
| nome | string | r | Nome di questo oggetto. |
| semi_major_axis | double | r | Semiasse maggiore dell'ellissoide. |
| semi_minor_axis | double | r | Semiasse minore dell'ellissoide. Uguale al semiasse maggiore se è una sfera. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellissoide WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellissoide WGS 84. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Determina se due ellissoidi sono equivalenti.<br/>            Se l'ellissoide A è equivalente all'ellissoide B, allora hanno lo stesso semiasse maggiore e lo stesso appiattimento inverso. |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina se due ellissoidi sono equivalenti.<br/>            Se l'ellissoide A è equivalente all'ellissoide B, allora hanno lo stesso semiasse maggiore e lo stesso appiattimento inverso. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Crea un nuovo Ellipsoid.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome dell'ellissoide. |
| semi_major_axis | double | Semiasse maggiore dell'ellissoide. |
| inverse_flattening | double | Appiattimento inverso dell'ellissoide. Deve essere 0 per creare uno sferoide. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore dell'ellissoide. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Determina se due ellissoidi sono equivalenti.<br/>            Se l'ellissoide A è equivalente all'ellissoide B, allora hanno lo stesso semiasse maggiore e lo stesso appiattimento inverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Primo ellissoide. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Secondo ellissoide. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore bool, che indica se due ellissoidi sono equivalenti. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Determina se due ellissoidi sono equivalenti.<br/>            Se l'ellissoide A è equivalente all'ellissoide B, allora hanno lo stesso semiasse maggiore e lo stesso appiattimento inverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Altro ellissoide. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore bool, che indica se due ellissoidi sono equivalenti. |


