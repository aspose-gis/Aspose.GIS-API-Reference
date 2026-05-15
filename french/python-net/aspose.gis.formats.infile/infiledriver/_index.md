---
title: "InFileDriver Classe"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.formats.infile/infiledriver/
---

**Summary:** A driver for work with data and temporary save in file.

**Module:** [aspose.gis.formats.infile](/psd/python-net/aspose.gis.formats.infile/)

**Full Name:** aspose.gis.formats.infile.InFileDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Obtient une valeur indiquant si ce pilote peut créer des ensembles de données. |
| can_create_layers | bool | r | Obtient une valeur indiquant si ce pilote peut créer des couches vectorielles. |
| can_open_datasets | bool | r | Obtient une valeur indiquant si ce pilote peut ouvrir des ensembles de données. |
| can_open_layers | bool | r | Obtient une valeur indiquant si ce pilote peut ouvrir des couches vectorielles. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Crée un ensemble de données. |
| [create_dataset(path)](#create_dataset_path_2) | Crée un ensemble de données. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Crée un ensemble de données. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Crée un ensemble de données. |
| [create_layer(path)](#create_layer_path_5) | Crée la couche et l'ouvre en mode ajout. |
| [create_layer(path)](#create_layer_path_6) | Crée la couche et l'ouvre en mode ajout. |
| [create_layer(path, options)](#create_layer_path_options_7) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options)](#create_layer_path_options_8) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options)](#create_layer_path_options_9) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options)](#create_layer_path_options_10) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Crée une couche et l'ouvre pour ajouter de nouvelles entités. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Crée la couche et l'ouvre en mode ajout. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Crée la couche et l'ouvre en mode ajout. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Ouvre une couche pour la modification. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Ouvre une couche pour la modification. |
| [open_dataset(path)](#open_dataset_path_18) | Ouvre le jeu de données. |
| [open_dataset(path)](#open_dataset_path_19) | Ouvre le jeu de données. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Ouvre le jeu de données. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Ouvre le jeu de données. |
| [open_layer(path)](#open_layer_path_22) | Ouvre la couche en lecture. |
| [open_layer(path)](#open_layer_path_23) | Ouvre la couche en lecture. |
| [open_layer(path, options)](#open_layer_path_options_24) | Ouvre une couche en lecture. |
| [open_layer(path, options)](#open_layer_path_options_25) | Ouvre une couche en lecture. |
| [open_layer(path, options)](#open_layer_path_options_26) | Ouvre une couche en lecture. |
| [open_layer(path, options)](#open_layer_path_options_27) | Ouvre une couche en lecture. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Détermine si le système de référence spatiale spécifié est pris en charge par le pilote. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Crée un ensemble de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [InFileOptions](/psd/python-net/aspose.gis.formats.infile/infileoptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [InFileOptions](/psd/python-net/aspose.gis.formats.infile/infileoptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [InFileOptions](/psd/python-net/aspose.gis.formats.infile/infileoptions) | Options spécifiques au pilote. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Crée une couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

Ouvre une couche pour la modification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

Ouvre une couche pour la modification.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le jeu de données. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

Ouvre le jeu de données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le jeu de données. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Une instance de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_22}


```
 open_layer(path) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Ouvre une couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [InFileOptions](/psd/python-net/aspose.gis.formats.infile/infileoptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Ouvre une couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Ouvre une couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| options | [InFileOptions](/psd/python-net/aspose.gis.formats.infile/infileoptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Ouvre une couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Détermine si le système de référence spatiale spécifié est pris en charge par le pilote.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Valeur booléenne indiquant si le système de référence spatiale spécifié est pris en charge par le pilote. |


