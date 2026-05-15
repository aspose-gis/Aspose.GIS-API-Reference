---
title: "Classe GeoPackageDataset"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Obtient une valeur indiquant si cet ensemble de données peut créer des couches vectorielles. |
| can_remove_layers | bool | r | Obtient une valeur indiquant si cet ensemble de données peut supprimer des couches vectorielles. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtient le [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) qui a instancié cet ensemble de données. |
| layers_count | int | r | Obtient le nombre de couches dans cet ensemble de données. |
| tile_layers_count | int | r | Obtient le nombre de couches de tuiles dans cet ensemble de données. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Crée un ensemble de données. |
| [create(path, driver)](#create_path_driver_2) | Crée un ensemble de données. |
| [create(path, driver, options)](#create_path_driver_options_3) | Crée un ensemble de données. |
| [create(path, driver, options)](#create_path_driver_options_4) | Crée un ensemble de données. |
| [create_layer()](#create_layer__5) | Crée une nouvelle couche vectorielle et l'ouvre en mode ajout. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Crée une nouvelle couche vectorielle avec le nom spécifié et l'ouvre en mode ajout. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Crée une nouvelle couche vectorielle avec le nom spécifié et l'ouvre en mode ajout. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Crée une nouvelle couche vectorielle et l'ouvre en mode ajout. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Crée une nouvelle couche vectorielle et l'ouvre en mode ajout. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Cette méthode est encore en cours de développement. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Cette méthode est encore en cours de développement. |
| [get_layer_name(index)](#get_layer_name_index_12) | Obtient le nom de la couche à l'index spécifié. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Obtient le nom de la couche de tuiles à l'index spécifié. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Vérifie si le jeu de données actuel possède une couche avec un nom spécifique |
| [open(path, driver)](#open_path_driver_15) | Ouvre le jeu de données. |
| [open(path, driver)](#open_path_driver_16) | Ouvre le jeu de données. |
| [open(path, driver, options)](#open_path_driver_options_17) | Ouvre le jeu de données. |
| [open(path, driver, options)](#open_path_driver_options_18) | Ouvre le jeu de données. |
| [open(path, options)](#open_path_options_19) | Méthode d'usine pour créer un ensemble de données à partir d'un fichier gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Ouvre la couche avec le nom spécifié pour la lecture. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Ouvre la couche à l'index spécifié pour la lecture. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Ouvre la couche à l'index spécifié pour la lecture. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Ouvre la couche de tuiles avec le nom spécifié en lecture. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Ouvre la couche de tuiles à l'index spécifié en lecture. |
| [remove_layer(name)](#remove_layer_name_25) | Supprime la couche vectorielle avec le nom spécifié. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Supprime la couche vectorielle à l'index spécifié. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Renommer la couche dans le jeu de données |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Paramètres concernant les particularités de la lecture du fichier gpkg. |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Crée une nouvelle couche vectorielle et l'ouvre en mode ajout.

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ouvert en écriture. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Crée une nouvelle couche vectorielle avec le nom spécifié et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale de la nouvelle couche. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ouvert en écriture. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Crée une nouvelle couche vectorielle avec le nom spécifié et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale de la nouvelle couche. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ouvert en écriture. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Crée une nouvelle couche vectorielle et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale de la nouvelle couche. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ouvert en écriture. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Crée une nouvelle couche vectorielle et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale de la nouvelle couche. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ouvert en écriture. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Cette méthode est encore en cours de développement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche à modifier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale pour les nouvelles géométries. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Cette méthode est encore en cours de développement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche à modifier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale pour les nouvelles géométries. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Obtient le nom de la couche à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche. |

**Returns**

| Type | Description |
| :- | :- |
| string | Nom de la couche. |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Obtient le nom de la couche de tuiles à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche. |

**Returns**

| Type | Description |
| :- | :- |
| string | Nom de la couche. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

Vérifie si le jeu de données actuel possède une couche avec un nom spécifique

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword="true" />, si le jeu de données possède une couche avec ce nom ; sinon, <see langword="false" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Méthode d'usine pour créer un ensemble de données à partir d'un fichier gpkg.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Paramètres concernant les particularités de la lecture du fichier gpkg. |

**Returns**

| Type | Description |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

Ouvre la couche avec le nom spécifié pour la lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche à ouvrir. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche ouverte pour la lecture. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

Ouvre la couche à l'index spécifié pour la lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche à ouvrir. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche ouverte pour la lecture. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Ouvre la couche à l'index spécifié pour la lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche à ouvrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Options d'ouverture. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche ouverte pour la lecture. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Ouvre la couche de tuiles avec le nom spécifié en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche à ouvrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Options d'ouverture. |

**Returns**

| Type | Description |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | La couche de tuiles ouverte pour la lecture. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Ouvre la couche de tuiles à l'index spécifié en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche à ouvrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Options d'ouverture. |

**Returns**

| Type | Description |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Supprime la couche vectorielle avec le nom spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Supprime la couche vectorielle à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Renommer la couche dans le jeu de données

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| current_name | string | Nom actuel de la couche |
| new_name | string | Nouveau nom pour la couche |

