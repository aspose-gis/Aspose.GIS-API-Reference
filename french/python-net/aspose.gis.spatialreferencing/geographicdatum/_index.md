---
title: "Classe GeographicDatum"
type: docs
weight: 70
url: /fr/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoïde, utilisé dans ce datum pour approximer la Terre. |
| epsg_code | int | r | Si l’identifiant de cet objet est un identifiant EPSG, renvoie son code. Sinon, renvoie -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifiant de cet objet identifiable. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 datum. |
| nom | string | r | Nom de cet objet. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 datum. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters qui peuvent être utilisés pour transformer les coordonnées de ce datum en coordonnées du datum WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 datum. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 datum. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Détermine si deux datums sont équivalents.<br/>            Les mêmes coordonnées de datums équivalents correspondent au même endroit sur Terre.<br/>            Certains paramètres de datums équivalents peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Détermine si deux datums sont équivalents.<br/>            Les mêmes coordonnées de datums équivalents correspondent au même endroit sur Terre.<br/>            Certains paramètres de datums équivalents peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de ce datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoïde de ce datum. Ne peut pas être nul. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Paramètres qui peuvent être fournis à la formule bursa wolf pour convertir les coordonnées de ce datum en coordonnées du datum WGS84.<br/>            Si ce datum est proche de WGS84 et qu'aucune transformation n'est nécessaire, transmettez les paramètres bursa wolf avec toutes les valeurs à 0.<br/>            Si nul, ToWgs84 sera défini sur les paramètres [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant de ce datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Détermine si deux datums sont équivalents.<br/>            Les mêmes coordonnées de datums équivalents correspondent au même endroit sur Terre.<br/>            Certains paramètres de datums équivalents peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Premier datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Deuxième datum. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur booléenne indiquant si deux datums sont équivalents. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Détermine si deux datums sont équivalents.<br/>            Les mêmes coordonnées de datums équivalents correspondent au même endroit sur Terre.<br/>            Certains paramètres de datums équivalents peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Autre datum. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur booléenne indiquant si deux datums sont équivalents. |


