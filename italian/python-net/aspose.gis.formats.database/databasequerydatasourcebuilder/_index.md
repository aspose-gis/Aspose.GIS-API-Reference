---
title: "Classe DatabaseQueryDataSourceBuilder"
type: docs
weight: 40
url: /it/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configura il nome del campo che conterrà le informazioni per l'attributo della feature. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Configura lo strato risultante per tracciare le modifiche e crea una fonte dati per sincronizzare le modifiche effettuate. |
| [build()](#build__3) | Il metodo recupera un'implementazione di [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Configura il nome del campo da cui verrà estratta la geometria. |
| [srid_field(name)](#srid_field_name_5) | Configurazione del nome del campo di query che conterrà l'identificatore del sistema di riferimento spaziale (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Consente di configurare la fonte dati per utilizzare dati di sistemi di riferimento spaziale di terze parti, aggirando i dati preinstallati nella libreria Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configura il nome del campo che conterrà le informazioni per l'attributo della feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del campo di query per l'attributo. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipo di dati in cui i dati del database devono essere convertiti. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Configura lo strato risultante per tracciare le modifiche e crea una fonte dati per sincronizzare le modifiche effettuate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| table_name | string | Il nome della tabella in cui verranno apportate le modifiche. |
| identity_attribute | string | Un attributo di una feature che sarà considerato come identificatore unico della feature. |
| overwrite_same_key | bool | Se questo flag è impostato su true, le nuove feature aggiunte con un identificatore unico già presente nello strato verranno sovrascritte, e i dati saranno letti come aggiornati se vengono trovate differenze. |
| db_func | string | Funzione che verrà fornita nella query SQL per trasformare i dati binari nella rappresentazione geografica dei dati del database corrente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Il metodo recupera un'implementazione di [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementazione di [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Configura il nome del campo da cui verrà estratta la geometria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del campo geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Configurazione del nome del campo di query che conterrà l'identificatore del sistema di riferimento spaziale (srid).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del campo di query contenente l'identificatore del sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Consente di configurare la fonte dati per utilizzare dati di sistemi di riferimento spaziale di terze parti, aggirando i dati preinstallati nella libreria Aspose.GIS.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| srs_query | string | Query per recuperare informazioni sui sistemi di coordinate spaziali aggiuntivi utilizzati nella query principale per recuperare le feature. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


