---
title: "DatabaseQueryDataSourceBuilder Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configureert de naam van het veld dat informatie voor het attribuut van het object zal bevatten. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Configureer de resulterende laag om wijzigingen bij te houden en maak een gegevensbron om de aangebrachte wijzigingen te synchroniseren. |
| [build()](#build__3) | De methode haalt een implementatie op van de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Configureert de naam van het veld waaruit de geometrie wordt geëxtraheerd. |
| [srid_field(name)](#srid_field_name_5) | Configureren van de naam van het queryveld dat de ruimtelijke referentiesysteem‑identificator (srid) zal bevatten. |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Staat u toe de gegevensbron te configureren om gegevens van een derde‑partij ruimtelijk referentiesysteem te gebruiken, waarbij de vooraf geïnstalleerde gegevens in de Aspose.GIS‑bibliotheek worden omzeild. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configureert de naam van het veld dat informatie voor het attribuut van het object zal bevatten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het queryveld voor attribuut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Type gegevens waarin data uit de database moet worden geconverteerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Configureer de resulterende laag om wijzigingen bij te houden en maak een gegevensbron om de aangebrachte wijzigingen te synchroniseren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| table_name | string | De naam van de tabel waarin de wijzigingen zullen worden aangebracht. |
| identity_attribute | string | Een attribuut van een object dat wordt beschouwd als uniek identificerend voor het object. |
| overwrite_same_key | bool | Als deze vlag op true wordt gezet, dan worden nieuw toegevoegde objecten met een unieke identifier die al in de laag aanwezig is, overschreven, en worden de gegevens gelezen als bijgewerkt als er verschillen worden gevonden. |
| db_func | string | Functie die zal worden geleverd in de SQL‑query om binaire gegevens om te zetten naar een geografische gegevensrepresentatie van de huidige database. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

De methode haalt een implementatie op van de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementatie van de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Configureert de naam van het veld waaruit de geometrie wordt geëxtraheerd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van geometrieveld. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Configureren van de naam van het queryveld dat de ruimtelijke referentiesysteem‑identificator (srid) zal bevatten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het queryveld dat de ruimtelijke referentiesysteem‑identificator bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Staat u toe de gegevensbron te configureren om gegevens van een derde‑partij ruimtelijk referentiesysteem te gebruiken, waarbij de vooraf geïnstalleerde gegevens in de Aspose.GIS‑bibliotheek worden omzeild.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| srs_query | string | Query om informatie op te halen over extra ruimtelijke coördinatensystemen die worden gebruikt in de hoofdquery om kenmerken op te halen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


