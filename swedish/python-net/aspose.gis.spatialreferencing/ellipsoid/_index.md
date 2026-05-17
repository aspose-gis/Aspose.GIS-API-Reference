---
title: "Ellipsoidklass"
type: docs
weight: 40
url: /sv/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Skapar ny ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy-ellipsoiden. |
| epsg_code | int | r | Om detta objekts identifierare är en EPSG‑identifierare – returnera dess kod. Annars – returnera -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980-ellipsoiden. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifierare för detta identifierbara objekt. |
| inverse_flattening | double | r | Invers plattning av ellipsoiden. 0 om detta är en sfär. |
| is_sphere | bool | r | Detekterar om denna ellipsoid är en sfär. |
| is_valid | bool | r | Detekterar om ellipsoiden är giltig: dess halva stora axel är större än 0 och invers plattning är positiv eller lika med 0. |
| namn | string | r | Namn på detta objekt. |
| semi_major_axis | double | r | Halv stor axel för ellipsoiden. |
| semi_minor_axis | double | r | Halv liten axel för ellipsoiden. Är lika med den halva stora axeln om detta är en sfär. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72-ellipsoiden. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84-ellipsoiden. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Bestämmer om två ellipsoider är ekvivalenta.<br/>            Om ellipsoid A är ekvivalent med ellipsoid B, har de samma halv stora axel och invers plattning. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestämmer om två ellipsoider är ekvivalenta.<br/>            Om ellipsoid A är ekvivalent med ellipsoid B, har de samma halv stora axel och invers plattning. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Skapar ny ellipsoid.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på ellipsoiden. |
| semi_major_axis | double | Halv stor axel för ellipsoiden. |
| inverse_flattening | double | Invers plattning av ellipsoiden. Ska vara 0 för att skapa en sfäroid. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare för ellipsoiden. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Bestämmer om två ellipsoider är ekvivalenta.<br/>            Om ellipsoid A är ekvivalent med ellipsoid B, har de samma halv stora axel och invers plattning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Första ellipsoiden. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Andra ellipsoiden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool-värde som indikerar om två ellipsoider är ekvivalenta. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bestämmer om två ellipsoider är ekvivalenta.<br/>            Om ellipsoid A är ekvivalent med ellipsoid B, har de samma halv stora axel och invers plattning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Annan ellipsoid. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool-värde som indikerar om två ellipsoider är ekvivalenta. |


