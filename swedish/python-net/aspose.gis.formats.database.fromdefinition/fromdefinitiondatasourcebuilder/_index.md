---
title: "FromDefinitionDataSourceBuilder klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Konfigurerar namnet på fältet som kommer att innehålla information för funktionens attribut. |
| [build()](#build__2) | Metoden hämtar en implementation av [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Konfigurerar namnet på fältet från vilket geometrin kommer att extraheras. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Obligatorisk inställning som möjliggör spårning av ändringar. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Konfigurerar namnet på fältet som kommer att innehålla information för funktionens attribut.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på databasfält för attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datatyp som data från databasen ska konverteras till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Metoden hämtar en implementation av [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implementering av [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Obligatorisk inställning som möjliggör spårning av ändringar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Ett attribut för ett objekt som kommer att behandlas som unikt identifierande objektet. |
| overwrite_same_key | bool | Om denna flagga är satt till true, kommer nyss tillagda funktioner med en unik identifierare som redan finns i lagret, <br/>            den aktuella kommer att skrivas över, och data kommer att läsas som uppdaterade om skillnader hittas.<br/>            Annars kommer ett undantag att kastas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


