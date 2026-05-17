---
title: "Clase CompoundSpatialReferenceSystem"
type: docs
weight: 30
url: /es/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Devuelve esto. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Devuelve este SRS convertido a [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Utilice [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) para averiguar si la conversión es posible. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Devuelve la representación geográfica de este SRS. Si este SRS compuesto realmente representa un SRS geográfico, el resultado será<br/>            un SRS geográfico tridimensional (con dimensiones de longitud, latitud y altura). De lo contrario se lanzará una excepción. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Devuelve este SRS convertido a [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Utilice [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) para averiguar si la conversión es posible. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Devuelve la representación proyectada de este SRS. Si este SRS compuesto realmente representa un SRS proyectado, el resultado será<br/>            un SRS proyectado tridimensional (con dimensiones X, Y y altura). De lo contrario se lanzará una excepción. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Devuelve este SRS convertido a [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Utilice [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) para averiguar si la conversión es posible. |
| dimensions_count | int | r | Número de dimensiones. Para un SRS compuesto, esto es la suma del número de dimensiones de los SRS subyacentes. |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) sistema de referencia espacial. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimutal de Área Igual (EPSG:3035) sistema de referencia espacial. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Cónico Conforme (EPSG:3034) sistema de referencia espacial. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Devuelve el datum geográfico de este SRS.<br/>            Si tanto [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) como [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) tienen datum geográfico, devuelve el datum geográfico del head. |
| has_geographic_datum | bool | r | Los SRS compuestos tienen datum geográfico si alguno de los SRS subyacentes tiene datum geográfico. |
| has_prime_meridian | bool | r | Los SRS compuestos tienen meridiano principal si alguno de los SRS subyacentes tiene meridiano principal. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Primer SRS subyacente. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| is_compound | bool | r | Devuelve <see langword="true" />. |
| is_single | bool | r | Devuelve si este SRS es único (no es una unión de dos SRS). |
| is_valid | bool | r | Igual que <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, pero no devuelve mensaje de error. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) sistema de referencia espacial. |
| nombre | string | r | Nombre de este objeto. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) sistema de referencia espacial. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / Cuadrícula Nacional Británica (EPSG:27700) sistema de referencia espacial. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Devuelve el meridiano principal de este SRS.<br/>            Si tanto [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) como [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) tienen meridiano principal, devuelve el meridiano principal del head. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Segundo SRS subyacente. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Tipo de este SRS compuesto. Puede ser [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) si<br/>            este SRS compuesto es una combinación de SRS geográfico y vertical, o [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) si<br/>            este SRS compuesto es una combinación de SRS proyectado y vertical. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistema de referencia espacial Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistema de referencia espacial WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistema de referencia espacial WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Crear SRS compuesto. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Crear un sistema de referencia espacial basado en el código EPSG especificado. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Crea un nuevo <c>SpatialReferenceSystem</c> basado en una cadena WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Crear SRS geocéntrico a partir de parámetros personalizados. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Crear SRS geográfico a partir de parámetros personalizados. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Crear Sistema de Referencia Espacial local. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Crear SRS proyectado a partir de parámetros personalizados. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Crea una transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Crear SRS vertical. |
| [export_to_wkt()](#export_to_wkt__10) | Devuelve la representación de este SRS como cadena WKT.<br/>            La cadena WKT resultante coincidirá con la especificación OGC 01-009, usualmente llamada "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Obtener [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) que describe la dimensión. |
| [get_unit(dimension)](#get_unit_dimension_12) | Obtener [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) de la dimensión. |
| [is_equivalent(other)](#is_equivalent_other_13) | Detecta si este SRS es equivalente a otro SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Determina si dos SRS son equivalentes.<br/>            Las mismas coordenadas de SRS equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de SRS equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Crear un sistema de referencia espacial basado en el código EPSG especificado. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Crea un nuevo <c>SpatialReferenceSystem</c> basado en una cadena WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Crea una transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Determine si este SRS es válido. Vea <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> para la descripción de validez. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Crear SRS compuesto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del nuevo SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS principal del nuevo SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS secundario del nuevo SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Nuevo SRS compuesto. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Crear un sistema de referencia espacial basado en el código EPSG especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| epsg | int | Código EPSG del sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un nuevo sistema de referencia espacial con el código EPSG especificado. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Crea un nuevo <c>SpatialReferenceSystem</c> basado en una cadena WKT (Well-Known Text).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkt | string | Cadena WKT. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Nuevo <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Crear SRS geocéntrico a partir de parámetros personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parámetros para crear a partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Nuevo SRS geocéntrico. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Crear SRS geográfico a partir de parámetros personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parámetros para crear a partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Nuevo SRS geográfico. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Crear Sistema de Referencia Espacial local.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del Sistema de Referencia Espacial. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum a usar en el SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unidad a usar en el SRS. |
| ejes | System.Collections.Generic.ICollection<Axis> | Ejes a usar en el SRS. Debe no estar vacío. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Nuevo Sistema de Referencia Espacial Local. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Crear SRS proyectado a partir de parámetros personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parámetros para crear a partir de. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Nuevo SRS proyectado. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Crea una transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Otro <c>SpatialReferenceSystem</c>. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Crear SRS vertical.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del SRS. Si <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum a usar en el SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unidad a usar en el SRS. Si <see langword=\"null\" />, se usará [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Eje con dirección \"up\" o \"down\", a usar en el SRS. Si <see langword=\"null\" />, se usará el eje con dirección up. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador, que se adjuntará al SRS. Adjuntar un Identificador no modificará otros parámetros del SRS.<br/>            Depende de usted garantizar la consistencia del identificador y los parámetros del SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Nuevo SRS vertical. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Devuelve la representación de este SRS como cadena WKT.<br/>            La cadena WKT resultante coincidirá con la especificación OGC 01-009, usualmente llamada "WKT1".

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Representación WKT de este SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Obtener [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) que describe la dimensión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dimensión | int | Número de dimensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Eje que describe la dimensión. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Obtener [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) de la dimensión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dimensión | int | Número de dimensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unidad de dimensión. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Detecta si este SRS es equivalente a otro SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Otro SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | valor bool, que indica si este SRS es equivalente a otro SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Determina si dos SRS son equivalentes.<br/>            Las mismas coordenadas de SRS equivalentes coinciden con el mismo lugar en la Tierra.<br/>            Algunos parámetros de SRS equivalentes pueden ser diferentes, por ejemplo [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Primer SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Segundo SRS. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | valor bool, que indica si dos SRS son equivalentes. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Crear un sistema de referencia espacial basado en el código EPSG especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| epsg | int | Código EPSG del sistema de referencia espacial. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Cuando este método devuelve <see langword=\"true\" />, contiene un SRS con el código EPSG especificado; de lo contrario,<br/>            contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si el código EPSG especificado es conocido y se creó el SRS; <see langword=\"false\" /> de lo contrario. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Crea un nuevo <c>SpatialReferenceSystem</c> basado en una cadena WKT (Well-Known Text).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| wkt | string | Cadena WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Cuando este método devuelve <see langword=\"true\" />, contiene un SRS creado a partir de WKT; de lo contrario,<br/>            contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si el SRS se creó con éxito; <see langword=\"false\" /> de lo contrario. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Crea una transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Otro <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Cuando este método devuelve <see langword=\"true\" />, contiene una transformación; de lo contrario, contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Transformación de este <c>SpatialReferenceSystem</c> a otro <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Determine si este SRS es válido. Vea <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> para la descripción de validez.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| error_message | Cadena | Descripción de la invalidez (si el resultado es <see langword="false" />) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Si este SRS es válido - <see langword="true" />, de lo contrario - <see langword="false" />. |


