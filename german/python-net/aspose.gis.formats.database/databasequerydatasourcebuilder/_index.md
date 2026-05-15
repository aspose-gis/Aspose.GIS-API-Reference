---
title: "DatabaseQueryDataSourceBuilder Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Konfiguriert den Namen des Feldes, das Informationen für das Feature‑Attribut enthält. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Konfigurieren Sie die resultierende Ebene, um Änderungen zu verfolgen, und erstellen Sie eine Datenquelle, um die vorgenommenen Änderungen zu synchronisieren. |
| [build()](#build__3) | Die Methode ruft eine Implementierung von [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) ab |
| [geometry_field(name)](#geometry_field_name_4) | Konfiguriert den Namen des Feldes, aus dem die Geometrie extrahiert wird. |
| [srid_field(name)](#srid_field_name_5) | Konfiguration des Namens des Abfragefeldes, das die Kennung des räumlichen Referenzsystems (srid) enthält. |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Ermöglicht die Konfiguration der Datenquelle zur Verwendung von Drittanbieter-Daten für räumliche Referenzsysteme, wobei die vorinstallierten Daten in der Aspose.GIS-Bibliothek umgangen werden. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Konfiguriert den Namen des Feldes, das Informationen für das Feature‑Attribut enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Abfragefeldes für das Attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datentyp, in den Daten aus der Datenbank konvertiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Konfigurieren Sie die resultierende Ebene, um Änderungen zu verfolgen, und erstellen Sie eine Datenquelle, um die vorgenommenen Änderungen zu synchronisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| table_name | string | Der Name der Tabelle, in der die Änderungen vorgenommen werden. |
| identity_attribute | string | Ein Attribut eines Features, das als eindeutige Identifizierung des Features behandelt wird. |
| overwrite_same_key | bool | Wenn dieses Flag auf true gesetzt ist, werden neu hinzugefügte Features mit einer eindeutigen Kennung, die bereits in der Ebene vorhanden ist, überschrieben, und die Daten werden als aktualisiert gelesen, wenn Unterschiede gefunden werden. |
| db_func | string | Funktion, die in der SQL-Abfrage bereitgestellt wird, um Binärdaten in die geografische Datenrepräsentation der aktuellen Datenbank zu transformieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Die Methode ruft eine Implementierung von [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) ab

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementierung von [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Konfiguriert den Namen des Feldes, aus dem die Geometrie extrahiert wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Geometriefelds. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Konfiguration des Namens des Abfragefeldes, das die Kennung des räumlichen Referenzsystems (srid) enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Abfragefeldes, das die Kennung des räumlichen Referenzsystems enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Ermöglicht die Konfiguration der Datenquelle zur Verwendung von Drittanbieter-Daten für räumliche Referenzsysteme, wobei die vorinstallierten Daten in der Aspose.GIS-Bibliothek umgangen werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| srs_query | string | Abfrage zum Abrufen von Informationen über zusätzliche räumliche Koordinatensysteme, die in der Hauptabfrage zum Abrufen von Features verwendet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


