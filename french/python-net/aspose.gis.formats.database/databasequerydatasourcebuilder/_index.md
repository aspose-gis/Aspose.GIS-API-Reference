---
title: "DatabaseQueryDataSourceBuilder Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Configure le nom du champ qui contiendra les informations pour l'attribut de l'entité. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Configurez la couche résultante pour suivre les modifications et créez une source de données afin de synchroniser les changements effectués. |
| [build()](#build__3) | La méthode récupère une implémentation de l'[IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Configure le nom du champ à partir duquel la géométrie sera extraite. |
| [srid_field(name)](#srid_field_name_5) | Configuration du nom du champ de requête qui contiendra l'identifiant du système de référence spatiale (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Vous permet de configurer la source de données pour utiliser des données de système de référence spatiale tierces, en contournant les données préinstallées dans la bibliothèque Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Configure le nom du champ qui contiendra les informations pour l'attribut de l'entité.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du champ de requête pour l'attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Type de données dans lesquelles les données de la base de données doivent être converties. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Configurez la couche résultante pour suivre les modifications et créez une source de données afin de synchroniser les changements effectués.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| table_name | string | Le nom de la table où les modifications seront effectuées. |
| identity_attribute | string | Un attribut d'une entité qui sera traité comme identifiant unique de l'entité. |
| overwrite_same_key | bool | Si ce drapeau est défini sur true, alors les nouvelles entités ajoutées avec un identifiant unique déjà présent dans la couche seront écrasées, et les données seront lues comme mises à jour si des différences sont détectées. |
| db_func | string | Fonction qui sera fournie dans la requête SQL pour transformer les données binaires en représentation de données géographiques de la base de données actuelle. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

La méthode récupère une implémentation de l'[IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Type | Description |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Implémentation de l'[IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


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
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Configuration du nom du champ de requête qui contiendra l'identifiant du système de référence spatiale (srid).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du champ de requête contenant l'identifiant du système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Vous permet de configurer la source de données pour utiliser des données de système de référence spatiale tierces, en contournant les données préinstallées dans la bibliothèque Aspose.GIS.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| srs_query | string | Requête pour récupérer des informations sur les systèmes de coordonnées spatiales supplémentaires utilisés dans la requête principale pour récupérer les entités. |

**Returns**

| Type | Description |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


