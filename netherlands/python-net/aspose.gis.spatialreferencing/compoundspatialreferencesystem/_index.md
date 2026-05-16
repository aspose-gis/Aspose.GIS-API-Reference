---
title: "CompoundSpatialReferenceSystem klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Retourneer dit. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Retourneert dit SRS geconverteerd naar [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Gebruik [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) om te achterhalen of conversie mogelijk is. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Retourneer de geografische representatie van dit SRS. Als dit samengestelde SRS inderdaad een geografisch SRS vertegenwoordigt, zal het resultaat<br/>            een driedimensionaal geografisch SRS zijn (met lengtegraden, breedtegraden, hoogtedimensies). Anders wordt een uitzondering gegooid. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Retourneert dit SRS geconverteerd naar [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/> Gebruik [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) om te achterhalen of conversie mogelijk is. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Retourneer de geprojecteerde representatie van dit SRS. Als dit samengestelde SRS inderdaad een geprojecteerd SRS vertegenwoordigt, zal het resultaat<br/>            een driedimensionaal geprojecteerd SRS zijn (met X-, Y- en hoogtedimensies). Anders wordt een uitzondering gegooid. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Retourneert dit SRS geconverteerd naar [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/> Gebruik [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) om te achterhalen of conversie mogelijk is. |
| dimensions_count | int | r | Aantal dimensies. Voor samengestelde SRS is dit de som van het aantal dimensies van de onderliggende SRS. |
| epsg_code | int | r | Als de identifier van dit object een EPSG-identificatie is - retourneer de code. Anders - retourneer -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) ruimtelijk referentiesysteem. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimutale Gelijke Oppervlakte (EPSG:3035) ruimtelijk referentiesysteem. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformale Kegel (EPSG:3034) ruimtelijk referentiesysteem. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Geef het geografische datum van deze SRS terug.<br/>            Als zowel [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) als [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) een geografisch datum hebben - geef het geografische datum van head terug. |
| has_geographic_datum | bool | r | Samengestelde SRS hebben een geografisch datum als een van de onderliggende SRS een geografisch datum heeft. |
| has_prime_meridian | bool | r | Samengestelde SRS heeft een nulmeridiaan als een van de onderliggende SRS een nulmeridiaan heeft. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Eerste onderliggende SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifier van dit identificeerbare object. |
| is_compound | bool | r | Retourneert <see langword="true" />. |
| is_single | bool | r | Retourneert of dit SRS enkel is (geen vereniging van twee SRS). |
| is_valid | bool | r | Hetzelfde als <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, maar retourneert geen foutmelding. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) ruimtelijk referentiesysteem. |
| naam | string | r | Naam van dit object. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) ruimtelijk referentiesysteem. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / Britse Nationale Raster (EPSG:27700) ruimtelijk referentiesysteem. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Geef de nulmeridiaan van deze SRS terug.<br/>            Als zowel [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) als [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) een nulmeridiaan hebben - geef de nulmeridiaan van head terug. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Tweede onderliggende SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Type van deze samengestelde SRS. Kan [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) zijn als<br/>            deze samengestelde SRS een combinatie is van een geografische en verticale SRS, of [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) als<br/>            deze samengestelde SRS een combinatie is van een geprojecteerde en verticale SRS. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) ruimtelijk referentiesysteem. |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) ruimtelijk referentiesysteem. |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) ruimtelijk referentiesysteem. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Maak een samengestelde SRS. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Maak een ruimtelijk referentiesysteem op basis van de opgegeven EPSG-code. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Maakt een nieuw <c>SpatialReferenceSystem</c> op basis van een WKT (Well-Known Text) tekenreeks. |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Maak een geocentrische SRS aan vanuit aangepaste parameters. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Maak een geografische SRS aan vanuit aangepaste parameters. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Maak een lokaal ruimtelijk referentiesysteem aan. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Maak een geprojecteerde SRS aan vanuit aangepaste parameters. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Maakt een transformatie van dit <c>SpatialReferenceSystem</c> naar een ander <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Maak een verticale SRS aan. |
| [export_to_wkt()](#export_to_wkt__10) | Retourneert een representatie van deze SRS als WKT-tekenreeks.<br/>            De resulterende WKT-tekenreeks zal voldoen aan de OGC 01-009 specificatie, meestal genaamd "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Haal de [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) op die de dimensie beschrijft. |
| [get_unit(dimension)](#get_unit_dimension_12) | Haal de [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) van de dimensie op. |
| [is_equivalent(other)](#is_equivalent_other_13) | Detecteert of deze SRS gelijk is aan een andere SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Bepaalt of twee SRS gelijk zijn.<br/>            Dezelfde coördinaten van gelijkwaardige SRS komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van gelijkwaardige SRS kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Maak een ruimtelijk referentiesysteem op basis van de opgegeven EPSG-code. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Maakt een nieuw <c>SpatialReferenceSystem</c> op basis van een WKT (Well-Known Text) tekenreeks. |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Maakt een transformatie van dit <c>SpatialReferenceSystem</c> naar een ander <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Bepaal of deze SRS geldig is. Zie <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" /> voor de beschrijving van de geldigheid. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Maak een samengestelde SRS.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de nieuwe SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Hoofd SRS van nieuwe SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Eind SRS van nieuwe SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Nieuwe samengestelde SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Maak een ruimtelijk referentiesysteem op basis van de opgegeven EPSG-code.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| epsg | int | EPSG-code van het ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Een nieuw ruimtelijk referentiesysteem met de opgegeven EPSG-code. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Maakt een nieuw <c>SpatialReferenceSystem</c> op basis van een WKT (Well-Known Text) tekenreeks.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkt | string | WKT-tekenreeks. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Nieuwe <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Maak een geocentrische SRS aan vanuit aangepaste parameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parameters om van te maken. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Nieuwe Geocentrische SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Maak een geografische SRS aan vanuit aangepaste parameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parameters om van te maken. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Nieuwe Geografische SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Maak een lokaal ruimtelijk referentiesysteem aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het ruimtelijk referentiesysteem. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum dat gebruikt wordt in de SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Eenheid die gebruikt wordt in de SRS. |
| assen | System.Collections.Generic.ICollection<Axis> | Assen die gebruikt worden in de SRS. Moet niet leeg zijn. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Nieuw lokaal ruimtelijk referentiesysteem. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Maak een geprojecteerde SRS aan vanuit aangepaste parameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parameters om van te maken. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Nieuwe geprojecteerde SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Maakt een transformatie van dit <c>SpatialReferenceSystem</c> naar een ander <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Een andere <c>SpatialReferenceSystem</c>. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformatie van dit <c>SpatialReferenceSystem</c> naar een andere <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Maak een verticale SRS aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de SRS. Indien <see langword="null" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum dat gebruikt wordt in de SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Eenheid die gebruikt wordt in de SRS. Indien <see langword="null" />, zal [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) worden gebruikt. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | As met de richting "up" of "down", die gebruikt wordt in de SRS. Indien <see langword="null" />, wordt een as met de up-richting gebruikt. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, die aan de SRS wordt gekoppeld. Het koppelen van een Identifier wijzigt geen andere SRS‑parameters.<br/>            Het is aan jou om de consistentie van de identifier en de SRS‑parameters te waarborgen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Nieuwe verticale SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Retourneert een representatie van deze SRS als WKT-tekenreeks.<br/>            De resulterende WKT-tekenreeks zal voldoen aan de OGC 01-009 specificatie, meestal genaamd "WKT1".

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | WKT-representatie van deze SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Haal de [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) op die de dimensie beschrijft.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dimensie | int | Aantal dimensies. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | As die de dimensie beschrijft. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Haal de [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) van de dimensie op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dimensie | int | Aantal dimensies. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Eenheid van dimensie. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Detecteert of deze SRS gelijk is aan een andere SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Andere SRS. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool-waarde, die aangeeft of deze SRS gelijk is aan een andere SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Bepaalt of twee SRS gelijk zijn.<br/>            Dezelfde coördinaten van gelijkwaardige SRS komen overeen met dezelfde plaats op aarde.<br/>            Sommige parameters van gelijkwaardige SRS kunnen verschillend zijn, bijvoorbeeld [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Eerste SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Tweede SRS. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | bool-waarde, die aangeeft of twee SRS gelijk zijn. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Maak een ruimtelijk referentiesysteem op basis van de opgegeven EPSG-code.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| epsg | int | EPSG-code van het ruimtelijk referentiesysteem. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Wanneer deze methode <see langword="true" /> retourneert, bevat een SRS met de opgegeven EPSG-code; anders,<br/>            bevat <see langword="null" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als de opgegeven EPSG-code bekend is en de SRS is aangemaakt; <see langword="false" /> anders. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Maakt een nieuw <c>SpatialReferenceSystem</c> op basis van een WKT (Well-Known Text) tekenreeks.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| wkt | string | WKT-tekenreeks. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Wanneer deze methode <see langword="true" /> retourneert, bevat een SRS gemaakt vanuit WKT; anders,<br/>            bevat <see langword="null" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als de SRS succesvol is aangemaakt; <see langword="false" /> anders. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Maakt een transformatie van dit <c>SpatialReferenceSystem</c> naar een ander <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Een andere <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Wanneer deze methode <see langword="true" /> retourneert, bevat een transformatie; anders, bevat <see langword="null" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Transformatie van dit <c>SpatialReferenceSystem</c> naar een andere <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Bepaal of deze SRS geldig is. Zie <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" /> voor de beschrijving van de geldigheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| error_message | String | Beschrijving van ongeldig (als resultaat <see langword="false" /> is) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Als deze SRS geldig is - <see langword="true" />, anders - <see langword="false" />. |


