---
title: "Classe GeographicSpatialReferenceSystem"
type: docs
weight: 80
url: /it/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unità, usata per le dimensioni angolari, in questo SRS. |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Restituisce questo SRS convertito in [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/).<br/>            Usa [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) per verificare se la conversione è possibile. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Restituisce questo SRS convertito in [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Usa [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) per verificare se la conversione è possibile. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Restituisce questo. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Restituisce questo SRS convertito in [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Usa [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) per scoprire se la conversione è possibile. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Restituisce questo SRS convertito in [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/).<br/>            Usa [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) per verificare se la conversione è possibile. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Restituisce questo SRS convertito in [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Usa [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) per scoprire se la conversione è possibile. |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | Ordine degli assi in questo SRS.<br/> Se questo SRS non è valido e ha direzioni degli assi errate, viene restituito [GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| dimensions_count | int | r | Restituisce il conteggio delle dimensioni in questo SRS. Per un SRS geografico può essere:<br/> due - se è un singolo SRS geografico.<br/> tre - se è un SRS composto, che consiste in un singolo SRS geografico bidimensionale e un SRS verticale, che aggiunge la terza dimensione. |
| epsg_code | int | r | Se l'identificatore di questo oggetto è un identificatore EPSG, restituisce il suo codice. Altrimenti restituisce -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) sistema di riferimento spaziale. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035) sistema di riferimento spaziale. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) sistema di riferimento spaziale. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Restituisce il datum geografico di questo SRS. |
| has_geographic_datum | bool | r | Restituisce <see langword=\"true\" />, poiché i SRS geografici hanno sempre il meridiano primario. |
| has_prime_meridian | bool | r | Restituisce <see langword=\"true\" />, poiché i SRS geografici hanno sempre il meridiano primario. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificatore di questo oggetto identificabile. |
| is_compound | bool | r | Restituisce se questo SRS è composto (un'unione di due SRS).<br/>            Le seguenti combinazioni di SRS in un SRS composto sono considerate valide:<br/>            SRS geografico + SRS verticale, in questo caso il tipo di SRS composto sarà [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            SRS proiettato + SRS verticale, in questo caso il tipo di SRS composto sarà [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Se la combinazione di SRS differisce, il tipo di SRS composto sarà [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| is_single | bool | r | Restituisce se questo SRS è singolo (non un'unione di due SRS). |
| is_valid | bool | r | Stesso di <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, ma non restituisce il messaggio di errore. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) sistema di riferimento spaziale. |
| nome | string | r | Nome di questo oggetto. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) sistema di riferimento spaziale. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) sistema di riferimento spaziale. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Restituisce il meridiano primario di questo SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Restituisce [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Sistema di riferimento spaziale Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistema di riferimento spaziale WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Sistema di riferimento spaziale WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Crea un SRS composto. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Crea un sistema di riferimento spaziale basato sul codice EPSG specificato. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Crea un nuovo <c>SpatialReferenceSystem</c> basato su una stringa WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Crea un SRS geocentrico da parametri personalizzati. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Crea un SRS geografico da parametri personalizzati. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Crea un Sistema di Riferimento Spaziale locale. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Crea un SRS proiettato da parametri personalizzati. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Crea una trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Crea un SRS verticale. |
| [export_to_wkt()](#export_to_wkt__10) | Restituisce la rappresentazione di questo SRS come stringa WKT.<br/>            La stringa WKT risultante corrisponderà alla specifica OGC 01-009, solitamente denominata "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Ottieni [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) che descrive la dimensione. |
| [get_unit(dimension)](#get_unit_dimension_12) | Ottieni [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) della dimensione. |
| [is_equivalent(other)](#is_equivalent_other_13) | Rileva se questo SRS è equivalente a un altro SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Determina se due SRS sono equivalenti.<br/>            Le stesse coordinate di SRS equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di SRS equivalenti possono differire, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Crea un sistema di riferimento spaziale basato sul codice EPSG specificato. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Crea un nuovo <c>SpatialReferenceSystem</c> basato su una stringa WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Crea una trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Determina se questo SRS è valido. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Crea un SRS composto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del nuovo SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS principale del nuovo SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS finale del nuovo SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Nuovo SRS composto. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Crea un sistema di riferimento spaziale basato sul codice EPSG specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| epsg | int | Codice EPSG del sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un nuovo sistema di riferimento spaziale con il codice EPSG specificato. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Crea un nuovo <c>SpatialReferenceSystem</c> basato su una stringa WKT (Well-Known Text).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkt | string | Stringa WKT. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Nuovo <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Crea un SRS geocentrico da parametri personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Parametri da cui creare. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Nuovo SRS geocentrico. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Crea un SRS geografico da parametri personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Parametri da cui creare. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Nuovo SRS geografico. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Crea un Sistema di Riferimento Spaziale locale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del Sistema di Riferimento Spaziale. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum da utilizzare nel SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unità da utilizzare nel SRS. |
| assi | System.Collections.Generic.ICollection<Axis> | Assi da utilizzare nel SRS. Deve essere non vuoto. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Nuovo Sistema di Riferimento Spaziale Locale. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Crea un SRS proiettato da parametri personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Parametri da cui creare. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Nuovo SRS proiettato. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Crea una trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un altro <c>SpatialReferenceSystem</c>. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Crea un SRS verticale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del SRS. Se <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum da utilizzare nel SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unità da utilizzare nel SRS. Se <see langword=\"null\" />, verrà utilizzato [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Asse con direzione \"up\" o \"down\", da utilizzare nel SRS. Se <see langword=\"null\" />, verrà utilizzato l'asse con direzione up. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificatore, che verrà allegato al SRS. L'aggiunta di un Identificatore non modificherà gli altri parametri del SRS.<br/>            Spetta a te garantire la coerenza tra l'identificatore e i parametri del SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Nuovo SRS verticale. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Restituisce la rappresentazione di questo SRS come stringa WKT.<br/>            La stringa WKT risultante corrisponderà alla specifica OGC 01-009, solitamente denominata "WKT1".

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Rappresentazione WKT di questo SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Ottieni [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) che descrive la dimensione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | Numero di dimensioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Asse che descrive la dimensione. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Ottieni [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) della dimensione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dimensione | int | Numero di dimensioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Unità di dimensione. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Rileva se questo SRS è equivalente a un altro SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Altro SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | valore booleano, che indica se questo SRS è equivalente a un altro SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Determina se due SRS sono equivalenti.<br/>            Le stesse coordinate di SRS equivalenti corrispondono allo stesso luogo sulla Terra.<br/>            Alcuni parametri di SRS equivalenti possono differire, ad esempio [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Primo SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Secondo SRS. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | valore booleano, che indica se due SRS sono equivalenti. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Crea un sistema di riferimento spaziale basato sul codice EPSG specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| epsg | int | Codice EPSG del sistema di riferimento spaziale. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Quando questo metodo restituisce <see langword=\"true\" />, contiene un SRS con il codice EPSG specificato; altrimenti,<br/>            contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se il codice EPSG specificato è noto e il SRS è stato creato; <see langword=\"false\" /> altrimenti. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Crea un nuovo <c>SpatialReferenceSystem</c> basato su una stringa WKT (Well-Known Text).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| wkt | string | Stringa WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Quando questo metodo restituisce <see langword=\"true\" />, contiene un SRS creato da WKT; altrimenti,<br/>            contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se il SRS è stato creato con successo; <see langword=\"false\" /> altrimenti. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Crea una trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Un altro <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Quando questo metodo restituisce <see langword=\"true\" />, contiene una trasformazione; altrimenti, contiene <see langword=\"null\" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Trasformazione da questo <c>SpatialReferenceSystem</c> a un altro <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Determina se questo SRS è valido.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| messaggio_errore | Stringa | Se il metodo restituisce <see langword=\"false\" />, allora questa è la descrizione dell'invalidità. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se il SRS è valido, <see langword=\"false\" /> altrimenti. |


