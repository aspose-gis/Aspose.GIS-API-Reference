---
title: "Classe FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /it/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configura il nome del campo che conterrà le informazioni per l'attributo della feature. |
| [build()](#build__2) | Il metodo recupera un'implementazione di [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Configura il nome del campo da cui verrà estratta la geometria. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Impostazione obbligatoria che consente di tracciare le modifiche. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configura il nome del campo che conterrà le informazioni per l'attributo della feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del campo del database per l'attributo. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipo di dati in cui i dati del database devono essere convertiti. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Il metodo recupera un'implementazione di [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implementazione di [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Impostazione obbligatoria che consente di tracciare le modifiche.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Un attributo di una feature che sarà considerato come identificatore unico della feature. |
| overwrite_same_key | bool | Se questo flag è impostato su true, allora le feature appena aggiunte con un identificatore unico uguale a quello già presente nel layer, <br/>            quella corrente verrà sovrascritta e i dati saranno letti come aggiornati se vengono trovate differenze.<br/>            Altrimenti, verrà sollevata l'eccezione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


