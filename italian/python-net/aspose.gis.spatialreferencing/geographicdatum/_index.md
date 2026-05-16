---
title: "Classe GeographicDatum"
type: docs
weight: 70
url: /it/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellissoide, usato in questo datum per approssimare la Terra. |
| epsg_code | int | r | Se l'identificatore di questo oggetto è un identificatore EPSG, restituisce il suo codice. Altrimenti restituisce -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificatore di questo oggetto identificabile. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum NAD 83. |
| nome | string | r | Nome di questo oggetto. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters che possono essere usati per trasformare le coordinate in questo datum in coordinate nel datum WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 84. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Determina se due datum sono equivalenti.<br/>            Le stesse coordinate di datum equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di datum equivalenti possono essere diversi, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina se due datum sono equivalenti.<br/>            Le stesse coordinate di datum equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di datum equivalenti possono essere diversi, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome di questo datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellissoide di questo datum. Non può essere nullo. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parametri che possono essere forniti alla formula bursa wolf, per convertire le coordinate in questo datum in coordinate nel datum WGS84.<br/>            Se questo datum è vicino a WGS84 e non è necessaria alcuna trasformazione, passa i parametri bursa wolf con tutti i valori impostati a 0.<br/>            Se nullo, ToWgs84 sarà impostato ai parametri [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore di questo datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Determina se due datum sono equivalenti.<br/>            Le stesse coordinate di datum equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di datum equivalenti possono essere diversi, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Primo datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Secondo datum. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore bool, che indica se due datum sono equivalenti. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Determina se due datum sono equivalenti.<br/>            Le stesse coordinate di datum equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di datum equivalenti possono essere diversi, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Altro datum. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore bool, che indica se due datum sono equivalenti. |


