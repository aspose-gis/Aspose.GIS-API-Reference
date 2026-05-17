---
title: "Clase DatabaseQueryDataSourceBuilder"
type: docs
weight: 40
url: /es/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configura el nombre del campo que contendrá la información del atributo de la entidad. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Configure la capa resultante para rastrear cambios y cree una fuente de datos para sincronizar los cambios realizados. |
| [build()](#build__3) | El método recupera una implementación de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Configura el nombre del campo del cual se extraerá la geometría. |
| [srid_field(name)](#srid_field_name_5) | Configurando el nombre del campo de consulta que contendrá el identificador del sistema de referencia espacial (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Le permite configurar la fuente de datos para usar datos de sistemas de referencia espacial de terceros, evitando los datos preinstalados en la biblioteca Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configura el nombre del campo que contendrá la información del atributo de la entidad.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del campo de consulta para el atributo. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipo de datos al que deben convertirse los datos de la base de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Configure la capa resultante para rastrear cambios y cree una fuente de datos para sincronizar los cambios realizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| table_name | string | El nombre de la tabla donde se realizarán los cambios. |
| identity_attribute | string | Un atributo de una entidad que se tratará como identificador único de la entidad. |
| overwrite_same_key | bool | Si esta bandera se establece en true, entonces las características recién añadidas con un identificador único que ya está presente en la capa, la actual será sobrescrita, y los datos se leerán como actualizados si se encuentran diferencias. |
| db_func | string | Función que se suministrará en la consulta SQL para transformar datos binarios en una representación de datos geográficos de la base de datos actual. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

El método recupera una implementación de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implementación de [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Configura el nombre del campo del cual se extraerá la geometría.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del campo de geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Configurando el nombre del campo de consulta que contendrá el identificador del sistema de referencia espacial (srid).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del campo de consulta que contiene el identificador del sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Le permite configurar la fuente de datos para usar datos de sistemas de referencia espacial de terceros, evitando los datos preinstalados en la biblioteca Aspose.GIS.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| srs_query | string | Consulta para obtener información sobre sistemas de coordenadas espaciales adicionales utilizados en la consulta principal para obtener características. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


