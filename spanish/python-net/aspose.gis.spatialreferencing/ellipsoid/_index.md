---
title: "Clase Ellipsoid"
type: docs
weight: 40
url: /es/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Crea un nuevo Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Elipsoide Airy. |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Elipsoide GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| inverse_flattening | double | r | Aplanamiento inverso del elipsoide. 0 si es una esfera. |
| is_sphere | bool | r | Detecta si este elipsoide es una esfera. |
| is_valid | bool | r | Detecta si el elipsoide es válido: su eje semi mayor es mayor que 0 y el aplanamiento inverso es positivo o igual a 0. |
| nombre | string | r | Nombre de este objeto. |
| semi_major_axis | double | r | Eje semi mayor del elipsoide. |
| semi_minor_axis | double | r | Eje semi menor del elipsoide. Igual al eje semi mayor si es una esfera. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Elipsoide WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Elipsoide WGS 84. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Determina si dos elipsoides son equivalentes.<br/>            Si el elipsoide A es equivalente al elipsoide B, entonces tienen el mismo eje semi mayor y aplanamiento inverso. |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina si dos elipsoides son equivalentes.<br/>            Si el elipsoide A es equivalente al elipsoide B, entonces tienen el mismo eje semi mayor y aplanamiento inverso. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Crea un nuevo Ellipsoid.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del elipsoide. |
| semi_major_axis | double | Eje semi mayor del elipsoide. |
| inverse_flattening | double | Aplanamiento inverso del elipsoide. Debe ser 0 para crear un esferoide. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador del elipsoide. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Determina si dos elipsoides son equivalentes.<br/>            Si el elipsoide A es equivalente al elipsoide B, entonces tienen el mismo eje semi mayor y aplanamiento inverso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Primer elipsoide. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Segundo elipsoide. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | valor bool, que indica si dos elipsoides son equivalentes. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Determina si dos elipsoides son equivalentes.<br/>            Si el elipsoide A es equivalente al elipsoide B, entonces tienen el mismo eje semi mayor y aplanamiento inverso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Otro elipsoide. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | valor bool, que indica si dos elipsoides son equivalentes. |


