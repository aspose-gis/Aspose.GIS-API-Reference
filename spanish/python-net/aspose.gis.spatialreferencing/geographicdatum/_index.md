---
title: "Clase GeographicDatum"
type: docs
weight: 70
url: /es/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Elipsoide, usado en este datum para aproximar la Tierra. |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum NAD 83. |
| nombre | string | r | Nombre de este objeto. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters que pueden usarse para transformar coordenadas en este datum a coordenadas en el datum WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 84. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Determina si dos datums son equivalentes.<br/>            Las mismas coordenadas de datums equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de datums equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina si dos datums son equivalentes.<br/>            Las mismas coordenadas de datums equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de datums equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de este datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Elipsoide de este datum. No puede ser nulo. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Parámetros que pueden darse a la fórmula bursa wolf, para convertir coordenadas en este datum a coordenadas en el datum WGS84.<br/>            Si este datum está cerca de WGS84 y no se necesita transformación, pase los parámetros bursa wolf con todos los valores establecidos en 0.<br/>            Si es nulo, ToWgs84 se establecerá a los parámetros [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador de este datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Determina si dos datums son equivalentes.<br/>            Las mismas coordenadas de datums equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de datums equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Primer datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Segundo datum. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor bool, que indica si dos datums son equivalentes. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Determina si dos datums son equivalentes.<br/>            Las mismas coordenadas de datums equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de datums equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Otro datum. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor bool, que indica si dos datums son equivalentes. |


