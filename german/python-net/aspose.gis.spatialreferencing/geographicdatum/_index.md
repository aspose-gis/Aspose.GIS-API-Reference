---
title: "GeographicDatum Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, das in diesem Datum verwendet wird, um die Erde zu approximieren. |
| epsg_code | int | r | Wenn der Bezeichner dieses Objekts ein EPSG‑Bezeichner ist – geben Sie dessen Code zurück. Andernfalls - geben Sie -1 zurück. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 Datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bezeichner dieses identifizierbaren Objekts. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 Datum. |
| Name | string | r | Name dieses Objekts. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 Datum. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters, die verwendet werden können, um Koordinaten in diesem Datum in Koordinaten im WGS84-Datum zu transformieren. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 Datum. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 Datum. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Bestimmt, ob zwei Datums äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter Datums entsprechen demselben Ort auf der Erde.<br/>            Einige Parameter äquivalenter Datums können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestimmt, ob zwei Datums äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter Datums entsprechen demselben Ort auf der Erde.<br/>            Einige Parameter äquivalenter Datums können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name dieses Datums. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid dieses Datums. Darf nicht null sein. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parameter, die der Bursa‑Wolf‑Formel übergeben werden können, um Koordinaten in diesem Datum in Koordinaten im WGS84-Datum zu konvertieren.<br/>            Wenn dieses Datum nahe an WGS84 liegt und keine Transformation erforderlich ist, übergeben Sie Bursa‑Wolf‑Parameter mit allen Werten auf 0 gesetzt.<br/>            Wenn null, wird ToWgs84 auf die Parameter [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) gesetzt. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Bezeichner dieses Datums. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Bestimmt, ob zwei Datums äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter Datums entsprechen demselben Ort auf der Erde.<br/>            Einige Parameter äquivalenter Datums können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Erstes Datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Zweites Datum. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool‑Wert, der angibt, ob zwei Datums äquivalent sind. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bestimmt, ob zwei Datums äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter Datums entsprechen demselben Ort auf der Erde.<br/>            Einige Parameter äquivalenter Datums können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Anderes Datum. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool‑Wert, der angibt, ob zwei Datums äquivalent sind. |


