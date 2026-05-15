---
title: "Classe FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configure le nom du champ qui contiendra les informations pour l'attribut de l'entité. |
| [build()](#build__2) | La méthode récupère une implémentation de [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Configure le nom du champ à partir duquel la géométrie sera extraite. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Paramètre obligatoire qui permet le suivi des modifications. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configure le nom du champ qui contiendra les informations pour l'attribut de l'entité.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du champ de base de données pour l'attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Type de données dans lesquelles les données de la base de données doivent être converties. |

**Returns**

| Type | Description |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

La méthode récupère une implémentation de [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Type | Description |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implémentation de l'[IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


```
 geometry_field(name) 
```

Configure le nom du champ à partir duquel la géométrie sera extraite.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du champ de géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Paramètre obligatoire qui permet le suivi des modifications.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Un attribut d'une entité qui sera traité comme identifiant unique de l'entité. |
| overwrite_same_key | bool | Si ce drapeau est défini sur true, alors les nouvelles entités ajoutées avec un identifiant unique identique à celui déjà présent dans la couche, <br/>            la actuelle sera écrasée, et les données seront lues comme mises à jour si des différences sont trouvées.<br/>            Sinon, une exception sera levée. |

**Returns**

| Type | Description |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


