---
title: "GeographicDatum Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde, gebruikt in dit datum om de aarde te benaderen. |
| epsg_code | int | r | Als de identifier van dit object een EPSG-identificatie is - retourneer de code. Anders - retourneer -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifier van dit identificeerbare object. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 datum. |
| naam | string | r | Naam van dit object. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 datum. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters die kunnen worden gebruikt om coördinaten in dit datum te transformeren naar coördinaten in WGS84 datum. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 datum. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 datum. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Bepaalt of twee datum gelijk zijn.<br/>            Dezelfde coördinaten van equivalente datum komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van equivalente datum kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Bepaalt of twee datum gelijk zijn.<br/>            Dezelfde coördinaten van equivalente datum komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van equivalente datum kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van dit datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoïde van dit datum. Kan niet null zijn. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parameters die kunnen worden opgegeven aan de bursa wolf-formule, om coördinaten in dit datum te converteren naar coördinaten in WGS84 datum.<br/>            Als dit datum dicht bij WGS84 ligt en er geen transformatie nodig is, geef bursa wolf-parameters door met alle waarden ingesteld op 0.<br/>            Als null, zal ToWgs84 worden ingesteld op [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) parameters. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier van dit datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Bepaalt of twee datum gelijk zijn.<br/>            Dezelfde coördinaten van equivalente datum komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van equivalente datum kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Eerste datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Tweede datum. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool-waarde, die aangeeft of twee datum gelijk zijn. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Bepaalt of twee datum gelijk zijn.<br/>            Dezelfde coördinaten van equivalente datum komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van equivalente datum kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Andere datum. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool-waarde, die aangeeft of twee datum gelijk zijn. |


