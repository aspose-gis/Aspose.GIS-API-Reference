---
title: "GeographicSpatialReferenceSystem-klass"
type: docs
weight: 80
url: /sv/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Enhet som används för vinkeldimensioner i detta SRS. |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Returnerar detta SRS konverterat till [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/).<br/>            Använd [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) för att ta reda på om konvertering är möjlig. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Returnerar detta SRS konverterat till [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Använd [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) för att ta reda på om konvertering är möjlig. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Returnerar detta. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Returnerar detta SRS konverterat till [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Använd [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) för att ta reda på om konvertering är möjlig. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Returnerar denna SRS konverterad till [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/).<br/>            Använd [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) för att ta reda på om konvertering är möjlig. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Returnerar detta SRS konverterat till [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Använd [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) för att ta reda på om konvertering är möjlig. |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | Ordning av axlar i detta SRS.<br/>            Om detta SRS inte är giltigt och har fel axelriktningar, returneras [GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| dimensions_count | int | r | Returnerar antalet dimensioner i detta SRS. För geografiskt SRS kan detta vara:<br/>            två - om detta är ett enkelt geografiskt SRS.<br/>            tre - om detta är ett sammansatt SRS, som består av ett enkelt, tvådimensionellt, geografiskt SRS och ett vertikalt SRS, som lägger till en tredje dimension. |
| epsg_code | int | r | Om detta objekts identifierare är en EPSG‑identifierare – returnera dess kod. Annars – returnera -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) rumsligt referenssystem. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimutal Likarea (EPSG:3035) rumsligt referenssystem. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) rumsligt referenssystem. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Returnerar geografiskt datum för detta SRS. |
| has_geographic_datum | bool | r | Returnerar <see langword=\"true\" />, eftersom geografiska SRS alltid har en primär meridian. |
| has_prime_meridian | bool | r | Returnerar <see langword=\"true\" />, eftersom geografiska SRS alltid har en primär meridian. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifierare för detta identifierbara objekt. |
| is_compound | bool | r | Returnerar om detta SRS är sammansatt (en union av två SRS).<br/>            Följande kombinationer av SRS i ett sammansatt SRS anses vara giltiga:<br/>            Geographic SRS + Vertical SRS, i detta fall blir typen av sammansatt SRS [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Projected SRS + Vertical SRS, i detta fall blir typen av sammansatt SRS [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Om kombinationen av SRS skiljer sig, blir typen av sammansatt SRS [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| is_single | bool | r | Returnerar om detta SRS är enkelt (inte en union av två SRS). |
| is_valid | bool | r | Samma som <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, men returnerar inte felmeddelande. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) rumsligt referenssystem. |
| namn | string | r | Namn på detta objekt. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) rumsligt referenssystem. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) rumsligt referenssystem. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Returnerar primär meridian för detta SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Returnerar [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) rumsligt referenssystem. |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) rumsligt referenssystem. |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) rumsligt referenssystem. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Skapa sammansatt SRS. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Skapa ett rumsligt referenssystem baserat på den angivna EPSG-koden. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Skapar ett nytt <c>SpatialReferenceSystem</c> baserat på en WKT (Well-Known Text)-sträng. |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Skapa geocentrisk SRS från anpassade parametrar. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Skapa geografisk SRS från anpassade parametrar. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Skapa lokalt Spatial Reference System. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Skapa projicerad SRS från anpassade parametrar. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Skapar en transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Skapa vertikal SRS. |
| [export_to_wkt()](#export_to_wkt__10) | Returnerar representation av detta SRS som en WKT-sträng.<br/>            Resultat‑WKT‑strängen kommer att följa OGC 01-009-specifikationen, vanligtvis benämnd "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Hämta [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) som beskriver dimensionen. |
| [get_unit(dimension)](#get_unit_dimension_12) | Hämta [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) för dimensionen. |
| [is_equivalent(other)](#is_equivalent_other_13) | Detekterar om detta SRS är ekvivalent med ett annat SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Bestämmer om två SRS är ekvivalenta.<br/>            Samma koordinater för ekvivalenta SRS motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta SRS kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Skapa ett rumsligt referenssystem baserat på den angivna EPSG-koden. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Skapar ett nytt <c>SpatialReferenceSystem</c> baserat på en WKT (Well-Known Text)-sträng. |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Skapar en transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Bestäm om detta SRS är giltigt. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Skapa sammansatt SRS.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på nytt SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Huvud-SRS för nytt SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Svans-SRS för nytt SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Nytt sammansatt SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Skapa ett rumsligt referenssystem baserat på den angivna EPSG-koden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| epsg | int | EPSG-kod för det rumsliga referenssystemet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ett nytt rumsligt referenssystem med den angivna EPSG-koden. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Skapar ett nytt <c>SpatialReferenceSystem</c> baserat på en WKT (Well-Known Text)-sträng.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkt | string | WKT-sträng. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ny <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Skapa geocentrisk SRS från anpassade parametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parametrar att skapa från. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Nytt geocentriskt SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Skapa geografisk SRS från anpassade parametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parametrar att skapa från. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Nytt geografiskt SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Skapa lokalt Spatial Reference System.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på det rumsliga referenssystemet. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum som ska användas i SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Enhet som ska användas i SRS. |
| axlar | System.Collections.Generic.ICollection<Axis> | Axlar som ska användas i SRS. Måste vara icke tom. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Nytt lokalt rumsligt referenssystem. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Skapa projicerad SRS från anpassade parametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parametrar att skapa från. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Nytt projicerat SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Skapar en transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | En annan <c>SpatialReferenceSystem</c>. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Skapa vertikal SRS.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på SRS. Om <see langword="null" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum som ska användas i SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Enhet som ska användas i SRS. Om <see langword="null" />, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) kommer att användas. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Axel med "upp" eller "ned"-riktning, som ska användas i SRS. Om <see langword="null" />, en axel med uppåtriktning kommer att användas. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifierare som kommer att bifogas till SRS. Att bifoga en identifierare kommer inte att ändra andra SRS‑parametrar.<br/>            Det är upp till dig att säkerställa konsistens mellan identifieraren och SRS‑parametrarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Nytt vertikalt SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Returnerar representation av detta SRS som en WKT-sträng.<br/>            Resultat‑WKT‑strängen kommer att följa OGC 01-009-specifikationen, vanligtvis benämnd "WKT1".

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | WKT-representation av detta SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Hämta [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) som beskriver dimensionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dimension | int | Antal dimensioner. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Axel som beskriver dimensionen. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Hämta [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) för dimensionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dimension | int | Antal dimensioner. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Enhet för dimension. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Detekterar om detta SRS är ekvivalent med ett annat SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Annan SRS. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool‑värde som anger om denna SRS är ekvivalent med annan SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Bestämmer om två SRS är ekvivalenta.<br/>            Samma koordinater för ekvivalenta SRS motsvarar samma plats på jorden.<br/>            Vissa parametrar för ekvivalenta SRS kan vara olika, till exempel [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Första SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Andra SRS. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | bool‑värde som anger om två SRS är ekvivalenta. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Skapa ett rumsligt referenssystem baserat på den angivna EPSG-koden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| epsg | int | EPSG-kod för det rumsliga referenssystemet. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | När den här metoden returnerar <see langword=\"true\" />, innehåller den en SRS med den angivna EPSG‑koden; annars,<br/>            innehåller <see langword=\"null\" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om den angivna EPSG‑koden är känd och SRS skapades; <see langword=\"false\" /> annars. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Skapar ett nytt <c>SpatialReferenceSystem</c> baserat på en WKT (Well-Known Text)-sträng.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| wkt | string | WKT-sträng. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | När den här metoden returnerar <see langword=\"true\" />, innehåller den en SRS skapad från WKT; annars,<br/>            innehåller <see langword=\"null\" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om SRS skapades framgångsrikt; <see langword=\"false\" /> annars. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Skapar en transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | En annan <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | När den här metoden returnerar <see langword=\"true\" />, innehåller den en transformation; annars innehåller <see langword=\"null\" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Transformation från detta <c>SpatialReferenceSystem</c> till ett annat <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Bestäm om detta SRS är giltigt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| error_message | Sträng | Om metoden returnerar <see langword=\"false\" />, är detta beskrivningen av ogiltigheten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" /> om SRS är giltig, <see langword=\"false\" /> annars. |


