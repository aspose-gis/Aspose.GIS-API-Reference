---
title: "GeographicDatum-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, som används i detta datum för att approximera jorden. |
| epsg_code | int | r | Om detta objekts identifierare är en EPSG‑identifierare – returnera dess kod. Annars – returnera -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89-datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifierare för detta identifierbara objekt. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83-datum. |
| namn | string | r | Namn på detta objekt. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936-datum. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters som kan användas för att transformera koordinater i detta datum till koordinater i WGS84-datum. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72-datum. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84-datum. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Bestämmer om två datum är ekvivalenta.<br/>            Samma koordinater för ekvivalenta datum motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta datum kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestämmer om två datum är ekvivalenta.<br/>            Samma koordinater för ekvivalenta datum motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta datum kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på detta datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid för detta datum. Får inte vara null. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parametrar som kan ges till bursa wolf-formeln för att konvertera koordinater i detta datum till koordinater i WGS84-datum.<br/>            Om detta datum ligger nära WGS84 och ingen transformation behövs, skicka bursa wolf-parametrar med alla värden satta till 0.<br/>            Om null kommer ToWgs84 att sättas till [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) parametrar. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare för detta datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Bestämmer om två datum är ekvivalenta.<br/>            Samma koordinater för ekvivalenta datum motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta datum kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Första datumet. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Andra datumet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool-värde som indikerar om två datum är ekvivalenta. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bestämmer om två datum är ekvivalenta.<br/>            Samma koordinater för ekvivalenta datum motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta datum kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Annat datum. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool-värde som indikerar om två datum är ekvivalenta. |


