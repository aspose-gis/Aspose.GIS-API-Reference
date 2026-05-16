---
title: "FromDefinitionDataSourceBuilder klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configureert de naam van het veld dat informatie voor het attribuut van het object zal bevatten. |
| [build()](#build__2) | De methode haalt een implementatie op van de [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Configureert de naam van het veld waaruit de geometrie wordt geëxtraheerd. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Verplichte instelling die het bijhouden van wijzigingen mogelijk maakt. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configureert de naam van het veld dat informatie voor het attribuut van het object zal bevatten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het databaseveld voor attribuut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Type gegevens waarin data uit de database moet worden geconverteerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

De methode haalt een implementatie op van de [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implementatie van de [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Verplichte instelling die het bijhouden van wijzigingen mogelijk maakt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Een attribuut van een object dat wordt beschouwd als uniek identificerend voor het object. |
| overwrite_same_key | bool | Als deze vlag op true is ingesteld, dan worden nieuw toegevoegde objecten met een unieke identifier die al aanwezig is in de laag, <br/>            de huidige overschreven, en worden de gegevens gelezen als bijgewerkt als er verschillen worden gevonden.<br/>            Anders wordt er een uitzondering gegooid. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


