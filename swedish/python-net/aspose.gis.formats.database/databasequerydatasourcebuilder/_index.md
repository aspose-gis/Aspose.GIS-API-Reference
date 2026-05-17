---
title: "DatabaseQueryDataSourceBuilder klass"
type: docs
weight: 40
url: /sv/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Konfigurerar namnet på fältet som kommer att innehålla information för funktionens attribut. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Konfigurera det resulterande lagret för att spåra ändringar och skapa en datakälla för att synkronisera de gjorda ändringarna. |
| [build()](#build__3) | Metoden hämtar en implementation av [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Konfigurerar namnet på fältet från vilket geometrin kommer att extraheras. |
| [srid_field(name)](#srid_field_name_5) | Konfigurering av namnet på frågefältet som kommer att innehålla identifieraren för det rumsliga referenssystemet (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Gör det möjligt att konfigurera datakällan för att använda tredjepartsdata för rumsliga referenssystem, och kringgå de förinstallerade data i Aspose.GIS‑biblioteket. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Konfigurerar namnet på fältet som kommer att innehålla information för funktionens attribut.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på frågefält för attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datatyp som data från databasen ska konverteras till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Konfigurera det resulterande lagret för att spåra ändringar och skapa en datakälla för att synkronisera de gjorda ändringarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| table_name | string | Namnet på tabellen där ändringarna kommer att göras. |
| identity_attribute | string | Ett attribut för ett objekt som kommer att behandlas som unikt identifierande objektet. |
| overwrite_same_key | bool | Om denna flagga är satt till true, så kommer nyinlagda objekt med en unik identifierare som redan finns i lagret att skrivas över, och data kommer att läsas som uppdaterade om skillnader upptäcks. |
| db_func | string | Funktion som kommer att tillhandahållas i SQL‑frågan för att omvandla binär data till geografisk datrepresentation av den aktuella databasen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Metoden hämtar en implementation av [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementation av [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Konfigurerar namnet på fältet från vilket geometrin kommer att extraheras.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på geometrifältet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Konfigurering av namnet på frågefältet som kommer att innehålla identifieraren för det rumsliga referenssystemet (srid).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på frågefältet som innehåller identifieraren för det rumsliga referenssystemet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Gör det möjligt att konfigurera datakällan för att använda tredjepartsdata för rumsliga referenssystem, och kringgå de förinstallerade data i Aspose.GIS‑biblioteket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| srs_query | string | Fråga för att hämta information om ytterligare rumsliga koordinatsystem som används i huvudfrågan för att hämta funktioner. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


