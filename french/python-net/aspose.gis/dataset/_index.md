---
title: "Classe Dataset"
type: docs
weight: 590
url: /fr/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Obtient une valeur indiquant si cet ensemble de données peut créer des couches vectorielles. |
| can_remove_layers | bool | r | Obtient une valeur indiquant si cet ensemble de données peut supprimer des couches vectorielles. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtient le [Dataset.driver](/psd/python-net/aspose.gis/dataset/) qui a instancié cet ensemble de données. |
| layers_count | int | r | Obtient le nombre de couches dans cet ensemble de données. |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Ouvre la couche avec le nom spécifié pour la modification. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Ouvre la couche avec le nom spécifié pour la modification. |
| [get_layer_name(index)](#get_layer_name_index_12) | Obtient le nom de la couche à l'index spécifié. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Vérifie si le jeu de données actuel possède une couche avec un nom spécifique |
| [open(path, driver)](#open_path_driver_14) | Ouvre le jeu de données. |
| [open(path, driver)](#open_path_driver_15) | Ouvre le jeu de données. |
| [open(path, driver, options)](#open_path_driver_options_16) | Ouvre le jeu de données. |
| [open(path, driver, options)](#open_path_driver_options_17) | Ouvre le jeu de données. |
| [open_layer(name, options)](#open_layer_name_options_18) | Ouvre la couche avec le nom spécifié pour la lecture. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Ouvre la couche à l'index spécifié pour la lecture. |
| [remove_layer(name)](#remove_layer_name_20) | Supprime la couche vectorielle avec le nom spécifié. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Supprime la couche vectorielle à l'index spécifié. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Renommer la couche dans le jeu de données |


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

Ouvre la couche avec le nom spécifié pour la modification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche à modifier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale pour les nouvelles géométries. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche ouverte pour la modification. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Ouvre la couche avec le nom spécifié pour la modification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche à modifier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options d'ouverture. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale pour les nouvelles géométries. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche ouverte pour la modification. |


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


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


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


### Method: open(path, driver)  [static] {#open_path_driver_14}


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


### Method: open(path, driver)  [static] {#open_path_driver_15}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


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


### Method: open_layer(name, options) {#open_layer_name_options_18}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


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


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Supprime la couche vectorielle avec le nom spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de la couche |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Supprime la couche vectorielle à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index de la couche |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Renommer la couche dans le jeu de données

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| current_name | string | Nom actuel de la couche |
| new_name | string | Nouveau nom pour la couche |

