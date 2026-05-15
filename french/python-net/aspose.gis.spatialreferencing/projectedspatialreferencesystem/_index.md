---
title: "ProjectedSpatialReferenceSystem Classe"
type: docs
weight: 150
url: /fr/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/
---

**Summary:** Projected SRS is a result of application a projection to geographic SRS.<br/>            A projected SRS can be two dimensional or three dimensional.<br/>            If projected SRS is three dimensional, then it is actually a compound SRS of two dimensional projected SRS and one dimensional vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unité utilisée pour les valeurs angulaires dans ce SRS et pour les paramètres angulaires de [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/).<br/>            Correspond à l’unité angulaire de [ProjectedSpatialReferenceSystem.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/). |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Renvoie ce SRS converti en [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/).<br/>            Utilisez [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) pour savoir si la conversion est possible. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Renvoie ce SRS converti en [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Utilisez [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) pour savoir si la conversion est possible. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Renvoie ce SRS converti en [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/).<br/>            Utilisez [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) pour savoir si la conversion est possible. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Renvoie ce SRS converti en [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Utilisez [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) pour savoir si la conversion est possible. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Renvoie ceci. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Renvoie ce SRS converti en [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Utilisez [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) pour savoir si la conversion est possible. |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r | Ordre des axes dans ce SRS.<br/>            Si ce SRS n'est pas valide et possède des directions d'axes incorrectes, [ProjectedAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) est renvoyé. |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | SRS géographique auquel la [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) a été appliquée pour obtenir ce SRS. |
| dimensions_count | int | r | Renvoie le nombre de dimensions dans ce SRS. Pour un SRS projeté, cela peut être :<br/>            deux - si c'est un SRS projeté unique.<br/>            trois - si c'est un SRS composé, qui consiste en un SRS projeté unique à deux dimensions et un SRS vertical, qui ajoute une troisième dimension. |
| epsg_code | int | r | Si l’identifiant de cet objet est un identifiant EPSG, renvoie son code. Sinon, renvoie -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Système de référence spatiale ETRS 89 (EPSG:4258). |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Système de référence spatiale ETRS 89 / ETRS Lambert Azimutal à Aire Égale (EPSG:3035). |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Système de référence spatiale ETRS 89 / Lambert Conique Conforme (EPSG:3034). |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Renvoie le datum géographique de ce SRS. |
| has_geographic_datum | bool | r | Renvoie true, car les SRS projetés ont toujours un méridien principal. |
| has_prime_meridian | bool | r | Renvoie true, car les SRS projetés ont toujours un méridien principal. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifiant de cet objet identifiable. |
| is_compound | bool | r | Renvoie si ce SRS est composé (une union de deux SRS).<br/>            Les combinaisons suivantes de SRS dans un SRS composé sont considérées comme valides :<br/>            SRS géographique + SRS vertical, auquel cas le type du SRS composé sera [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            SRS projeté + SRS vertical, auquel cas le type du SRS composé sera [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Si la combinaison des SRS diffère, le type du SRS composé sera [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| is_single | bool | r | Renvoie si ce SRS est unique (pas une union de deux SRS). |
| is_valid | bool | r | Identique à <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, mais ne renvoie pas de message d'erreur. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unité utilisée pour les dimensions linéaires dans ce SRS et pour les paramètres linéaires de la [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/). |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Système de référence spatiale NAD 83 (EPSG:4269). |
| nom | string | r | Nom de cet objet. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Système de référence spatiale OSGB 36 (EPSG:4277). |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Système de référence spatiale OSGB 36 / British National Grid (EPSG:27700). |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Renvoie le méridien principal de ce SRS. |
| projection | [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) | r | Projection qui a été appliquée à la [ProjectedSpatialReferenceSystem.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) pour obtenir ce SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Renvoie [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Système de référence spatiale Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Système de référence spatiale WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Système de référence spatiale WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Créer un SRS composé. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Créer un système de référence spatiale basé sur le code EPSG spécifié. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Crée un nouveau <c>SpatialReferenceSystem</c> basé sur une chaîne WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Créer un SRS géocentrique à partir de paramètres personnalisés. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Créer un SRS géographique à partir de paramètres personnalisés. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Créer un système de référence spatiale local. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Créer un SRS projeté à partir de paramètres personnalisés. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Crée une transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Créer un SRS vertical. |
| [export_to_wkt()](#export_to_wkt__10) | Renvoie la représentation de ce SRS sous forme de chaîne WKT.<br/>            La chaîne WKT résultante correspondra à la spécification OGC 01-009, généralement nommée "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Obtenir [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) qui décrit la dimension. |
| [get_unit(dimension)](#get_unit_dimension_12) | Obtenir [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) de la dimension. |
| [is_equivalent(other)](#is_equivalent_other_13) | Détecte si ce SRS est équivalent à un autre SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Détermine si deux SRS sont équivalents.<br/>            Les mêmes coordonnées d'un SRS équivalent correspondent au même endroit sur Terre.<br/>            Certains paramètres d'un SRS équivalent peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Créer un système de référence spatiale basé sur le code EPSG spécifié. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Crée un nouveau <c>SpatialReferenceSystem</c> basé sur une chaîne WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Crée une transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Déterminer si ce SRS est valide. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Créer un SRS composé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du nouveau SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS principal du nouveau SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS secondaire du nouveau SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Nouveau SRS composé. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Créer un système de référence spatiale basé sur le code EPSG spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| epsg | int | Code EPSG du système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un nouveau système de référence spatiale avec le code EPSG spécifié. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Crée un nouveau <c>SpatialReferenceSystem</c> basé sur une chaîne WKT (Well-Known Text).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkt | string | Chaîne WKT. |

**Returns**

| Type | Description |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Nouveau <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Créer un SRS géocentrique à partir de paramètres personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Paramètres à créer à partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Nouveau SRS géocentrique. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Créer un SRS géographique à partir de paramètres personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Paramètres à créer à partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Nouveau SRS géographique. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Créer un système de référence spatiale local.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du système de référence spatiale. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum à utiliser dans le SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unité à utiliser dans le SRS. |
| axes | System.Collections.Generic.ICollection<Axis> | Axes à utiliser dans le SRS. Doit être non vide |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Nouveau système de référence spatiale local. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Créer un SRS projeté à partir de paramètres personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Paramètres à créer à partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Nouveau SRS projeté. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Crée une transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un autre <c>SpatialReferenceSystem</c>. |

**Returns**

| Type | Description |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Créer un SRS vertical.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du SRS. Si <see langword="null" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum à utiliser dans le SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unité à utiliser dans le SRS. Si <see langword="null" />, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) sera utilisée. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Axe avec la direction "up" ou "down", à utiliser dans le SRS. Si <see langword="null" />, l'axe avec la direction up sera utilisé. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifiant, qui sera attaché au SRS. Attacher un identifiant ne modifiera pas les autres paramètres du SRS.<br/>            Il vous revient de garantir la cohérence de l'identifiant et des paramètres du SRS. |

**Returns**

| Type | Description |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Nouveau SRS vertical. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Renvoie la représentation de ce SRS sous forme de chaîne WKT.<br/>            La chaîne WKT résultante correspondra à la spécification OGC 01-009, généralement nommée "WKT1".

**Returns**

| Type | Description |
| :- | :- |
| string | Représentation WKT de ce SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Obtenir [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) qui décrit la dimension.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dimension | int | Nombre de dimensions. |

**Returns**

| Type | Description |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Axe qui décrit la dimension. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Obtenir [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) de la dimension.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dimension | int | Nombre de dimensions. |

**Returns**

| Type | Description |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unité de dimension. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Détecte si ce SRS est équivalent à un autre SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Autre SRS. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur bool, indiquant si ce SRS est équivalent à un autre SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Détermine si deux SRS sont équivalents.<br/>            Les mêmes coordonnées d'un SRS équivalent correspondent au même endroit sur Terre.<br/>            Certains paramètres d'un SRS équivalent peuvent être différents, par exemple [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Premier SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Deuxième SRS. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur bool, indiquant si deux SRS sont équivalents. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Créer un système de référence spatiale basé sur le code EPSG spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| epsg | int | Code EPSG du système de référence spatiale. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Lorsque cette méthode renvoie <see langword=\"true\" />, contient un SRS avec le code EPSG spécifié ; sinon,<br/>            contient <see langword=\"null\" />. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si le code EPSG spécifié est connu et le SRS a été créé ; <see langword=\"false\" /> sinon. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Crée un nouveau <c>SpatialReferenceSystem</c> basé sur une chaîne WKT (Well-Known Text).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| wkt | string | Chaîne WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Lorsque cette méthode renvoie <see langword=\"true\" />, contient un SRS créé à partir de WKT ; sinon,<br/>            contient <see langword=\"null\" />. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si le SRS a été créé avec succès ; <see langword=\"false\" /> sinon. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Crée une transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un autre <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Lorsque cette méthode renvoie <see langword=\"true\" />, contient une transformation ; sinon, contient <see langword=\"null\" />. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Transformation de ce <c>SpatialReferenceSystem</c> vers un autre <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Déterminer si ce SRS est valide.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| error_message | String | Si la méthode renvoie <see langword=\"false\" />, alors ceci est la description de l'invalidité. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si le SRS est valide, <see langword=\"false\" /> sinon. |


