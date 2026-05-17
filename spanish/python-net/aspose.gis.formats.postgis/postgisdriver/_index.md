---
title: "Clase PostGisDriver"
type: docs
weight: 10
url: /es/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | Permite iniciar el proceso de configuración de la fuente de datos [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) para trabajar con ella. |
| [from_query(query)](#from_query_query_2) | Configurando la fuente de datos para consultas de base de datos personalizadas. |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

Permite iniciar el proceso de configuración de la fuente de datos [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) para trabajar con ella.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| table_name | string | Nombre de la tabla de base de datos de la que se extraerán los datos |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

Configurando la fuente de datos para consultas de base de datos personalizadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| query | string | Cadena de consulta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


