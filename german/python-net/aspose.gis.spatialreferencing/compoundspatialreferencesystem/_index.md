---
title: "CompoundSpatialReferenceSystem Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Gibt dies zurück. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Gibt dieses SRS zurück, konvertiert zu [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Verwenden Sie [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/), um herauszufinden, ob eine Konvertierung möglich ist. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Gibt die geografische Darstellung dieses SRS zurück. Wenn dieses zusammengesetzte SRS tatsächlich ein geografisches SRS darstellt, wird das Ergebnis<br/>            ein dreidimensionales geografisches SRS sein (mit Längen-, Breiten- und Höhenmaßen). Andernfalls wird eine Ausnahme ausgelöst. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Gibt dieses SRS zurück, konvertiert zu [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Verwenden Sie [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) um herauszufinden, ob die Konvertierung möglich ist. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Gibt die projizierte Darstellung dieses SRS zurück. Wenn dieses zusammengesetzte SRS tatsächlich ein projiziertes SRS darstellt, wird das Ergebnis<br/>            ein dreidimensionales projiziertes SRS sein (mit X-, Y- und Höhenmaßen). Andernfalls wird eine Ausnahme ausgelöst. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Gibt dieses SRS zurück, konvertiert zu [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Verwenden Sie [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) um herauszufinden, ob die Konvertierung möglich ist. |
| dimensions_count | int | r | Anzahl der Dimensionen. Für zusammengesetzte SRS ist dies die Summe der Anzahl der Dimensionen des zugrunde liegenden SRS. |
| epsg_code | int | r | Wenn der Bezeichner dieses Objekts ein EPSG‑Bezeichner ist – geben Sie dessen Code zurück. Andernfalls - geben Sie -1 zurück. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) räumliches Bezugssystem. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimutal Equal Area (EPSG:3035) räumliches Bezugssystem. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) räumliches Bezugssystem. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Gibt das geografische Datum dieses SRS zurück.<br/>            Wenn sowohl [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) und [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) ein geografisches Datum haben - gibt das geografische Datum des Kopfes zurück. |
| has_geographic_datum | bool | r | Zusammengesetzte SRS haben ein geografisches Datum, wenn irgendeines der zugrunde liegenden SRS ein geografisches Datum hat. |
| has_prime_meridian | bool | r | Zusammengesetzte SRS haben einen Prime-Meridian, wenn irgendeines der zugrunde liegenden SRS einen Prime-Meridian hat. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Erstes zugrunde liegendes SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bezeichner dieses identifizierbaren Objekts. |
| is_compound | bool | r | Gibt <see langword="true" /> zurück. |
| is_single | bool | r | Gibt zurück, ob dieses SRS einzeln ist (keine Vereinigung von zwei SRS). |
| is_valid | bool | r | Dasselbe wie <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, aber gibt keine Fehlermeldung zurück. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 84 (EPSG:4269) räumliches Bezugssystem. |
| Name | string | r | Name dieses Objekts. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) räumliches Bezugssystem. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) räumliches Bezugssystem. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Gibt den Prime-Meridian dieses SRS zurück.<br/>            Wenn sowohl [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) und [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) einen Prime-Meridian haben - gibt den Prime-Meridian des Kopfes zurück. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Zweites zugrunde liegendes SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Typ dieses zusammengesetzten SRS. Kann [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) sein, wenn<br/>            dieses zusammengesetzte SRS eine Kombination aus geografischem und vertikalem SRS ist, oder [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) sein, wenn<br/>            dieses zusammengesetzte SRS eine Kombination aus projiziertem und vertikalem SRS ist. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) räumliches Referenzsystem. |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) räumliches Referenzsystem. |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) räumliches Referenzsystem. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Erstelle zusammengesetztes SRS. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Erstelle ein räumliches Referenzsystem basierend auf dem angegebenen EPSG-Code. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Erstellt ein neues <c>SpatialReferenceSystem</c> basierend auf einer WKT (Well-Known Text)-Zeichenkette. |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Erstelle ein geozentrisches SRS aus benutzerdefinierten Parametern. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Erstelle ein geografisches SRS aus benutzerdefinierten Parametern. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Erstelle ein lokales räumliches Referenzsystem. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Erstelle ein projiziertes SRS aus benutzerdefinierten Parametern. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Erstellt eine Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Erstelle ein vertikales SRS. |
| [export_to_wkt()](#export_to_wkt__10) | Gibt die Darstellung dieses SRS als WKT-Zeichenkette zurück.<br/>            Die resultierende WKT-Zeichenkette entspricht der OGC 01-009 Spezifikation, üblicherweise "WKT1" genannt. |
| [get_axis(dimension)](#get_axis_dimension_11) | Hole [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/), das die Dimension beschreibt. |
| [get_unit(dimension)](#get_unit_dimension_12) | Hole [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) der Dimension. |
| [is_equivalent(other)](#is_equivalent_other_13) | Ermittelt, ob dieses SRS einem anderen SRS entspricht. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Bestimmt, ob zwei SRS äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter SRS entsprechen derselben Stelle auf der Erde.<br/>            Einige Parameter äquivalenter SRS können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Erstelle ein räumliches Referenzsystem basierend auf dem angegebenen EPSG-Code. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Erstellt ein neues <c>SpatialReferenceSystem</c> basierend auf einer WKT (Well-Known Text)-Zeichenkette. |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Erstellt eine Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Bestimmen Sie, ob dieses SRS gültig ist. Siehe <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> für die Gültigkeitsbeschreibung. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Erstelle zusammengesetztes SRS.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des neuen SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Kopf‑SRS des neuen SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | End‑SRS des neuen SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Neues zusammengesetztes SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Erstelle ein räumliches Referenzsystem basierend auf dem angegebenen EPSG-Code.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| epsg | int | EPSG-Code des räumlichen Referenzsystems. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ein neues räumliches Referenzsystem mit dem angegebenen EPSG-Code. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Erstellt ein neues <c>SpatialReferenceSystem</c> basierend auf einer WKT (Well-Known Text)-Zeichenkette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkt | string | WKT-Zeichenkette. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Neues <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Erstelle ein geozentrisches SRS aus benutzerdefinierten Parametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parameter zum Erstellen aus. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Neues geozentrisches SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Erstelle ein geografisches SRS aus benutzerdefinierten Parametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parameter zum Erstellen aus. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Neues geografisches SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Erstelle ein lokales räumliches Referenzsystem.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des räumlichen Referenzsystems. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum, das im SRS verwendet wird. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Einheit, die im SRS verwendet wird. |
| Achsen | System.Collections.Generic.ICollection<Axis> | Achsen, die im SRS verwendet werden. Müssen nicht leer sein. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Neues lokales räumliches Referenzsystem. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Erstelle ein projiziertes SRS aus benutzerdefinierten Parametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parameter zum Erstellen aus. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Neues projiziertes SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Erstellt eine Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ein weiteres <c>SpatialReferenceSystem</c>. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Erstelle ein vertikales SRS.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des SRS. Falls <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum, das im SRS verwendet wird. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Einheit, die im SRS verwendet wird. Falls <see langword=\"null\" />, wird [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) verwendet. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Achse mit \"up\"- oder \"down\"-Richtung, die im SRS verwendet wird. Falls <see langword=\"null\" />, wird eine Achse mit Aufwärtsrichtung verwendet. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier, der dem SRS angehängt wird. Das Anhängen eines Identifiers ändert keine anderen SRS‑Parameter.<br/>            Es liegt an Ihnen, die Konsistenz von Identifier und SRS‑Parametern sicherzustellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Neues vertikales SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Gibt die Darstellung dieses SRS als WKT-Zeichenkette zurück.<br/>            Die resultierende WKT-Zeichenkette entspricht der OGC 01-009 Spezifikation, üblicherweise "WKT1" genannt.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | WKT-Darstellung dieses SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Hole [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/), das die Dimension beschreibt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dimension | int | Anzahl der Dimension. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Achse, die die Dimension beschreibt. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Hole [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) der Dimension.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dimension | int | Anzahl der Dimension. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Einheit der Dimension. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Ermittelt, ob dieses SRS einem anderen SRS entspricht. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Andere SRS. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool-Wert, der angibt, ob dieses SRS dem anderen SRS entspricht. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Bestimmt, ob zwei SRS äquivalent sind.<br/>            Gleiche Koordinaten äquivalenter SRS entsprechen derselben Stelle auf der Erde.<br/>            Einige Parameter äquivalenter SRS können unterschiedlich sein, zum Beispiel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Erstes SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Zweites SRS. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | bool-Wert, der angibt, ob zwei SRS äquivalent sind. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Erstelle ein räumliches Referenzsystem basierend auf dem angegebenen EPSG-Code.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| epsg | int | EPSG-Code des räumlichen Referenzsystems. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Wenn diese Methode <see langword=\"true\" /> zurückgibt, enthält sie ein SRS mit dem angegebenen EPSG-Code; andernfalls,<br/>            enthält sie <see langword=\"null\" />. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn der angegebene EPSG-Code bekannt ist und das SRS erstellt wurde; <see langword=\"false\" /> andernfalls. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Erstellt ein neues <c>SpatialReferenceSystem</c> basierend auf einer WKT (Well-Known Text)-Zeichenkette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| wkt | string | WKT-Zeichenkette. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Wenn diese Methode <see langword=\"true\" /> zurückgibt, enthält sie ein SRS, das aus WKT erstellt wurde; andernfalls,<br/>            enthält sie <see langword=\"null\" />. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn das SRS erfolgreich erstellt wurde; <see langword=\"false\" /> andernfalls. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Erstellt eine Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ein weiteres <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Wenn diese Methode <see langword=\"true\" /> zurückgibt, enthält sie eine Transformation; andernfalls enthält sie <see langword=\"null\" />. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Transformation von diesem <c>SpatialReferenceSystem</c> zu einem anderen <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Bestimmen Sie, ob dieses SRS gültig ist. Siehe <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> für die Gültigkeitsbeschreibung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Fehlermeldung | String | Beschreibung der Ungültigkeit (wenn das Ergebnis <see langword="false" /> ist) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Wenn dieses SRS gültig ist - <see langword="true" />, andernfalls - <see langword="false" />. |


