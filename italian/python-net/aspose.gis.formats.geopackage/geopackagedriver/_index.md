---
title: "Classe GeoPackageDriver"
type: docs
weight: 20
url: /it/python-net/aspose.gis.formats.geopackage/geopackagedriver/
---

**Summary:** A driver for the GPKG file format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GeoPackageDriver()](#GeoPackageDriver__1) | Inizializza una nuova istanza della classe GeoPackageDriver |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Restituisce un valore che indica se questo driver può creare set di dati. |
| can_create_layers | bool | r | Restituisce un valore che indica se questo driver può creare livelli vettoriali. |
| can_open_datasets | bool | r | Restituisce un valore che indica se questo driver può aprire set di dati. |
| can_open_layers | bool | r | Restituisce un valore che indica se questo driver può aprire livelli vettoriali. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Crea un set di dati. |
| [create_dataset(path)](#create_dataset_path_2) | Crea un set di dati. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Crea un set di dati. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Crea un set di dati. |
| [create_layer(path)](#create_layer_path_5) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path)](#create_layer_path_6) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, options)](#create_layer_path_options_7) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, options)](#create_layer_path_options_8) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_9) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_11) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_12) | Crea il livello e lo apre per l'aggiunta. |
| [edit_layer(path, options)](#edit_layer_path_options_13) | Apre un layer per la modifica. |
| [edit_layer(path, options)](#edit_layer_path_options_14) | Apre un layer per la modifica. |
| [open_dataset(path)](#open_dataset_path_15) | Apre il dataset. |
| [open_dataset(path)](#open_dataset_path_16) | Apre il dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_17) | Apre il dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_18) | Apre il dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_19) | Apre il dataset. |
| [open_layer(path)](#open_layer_path_20) | Apre il layer per la lettura. |
| [open_layer(path)](#open_layer_path_21) | Apre il layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_22) | Apre il layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_23) | Apre il layer per la lettura. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_24) | Determina se il sistema di riferimento spaziale specificato è supportato dal driver. |


### Constructor: GeoPackageDriver() {#GeoPackageDriver__1}


```
 GeoPackageDriver() 
```

Inizializza una nuova istanza della classe GeoPackageDriver

### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_9}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_11}


```
 create_layer(path, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_12}


```
 create_layer(path, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_13}


```
 edit_layer(path, options) 
```

Apre un layer per la modifica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_14}


```
 edit_layer(path, options) 
```

Apre un layer per la modifica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_15}


```
 open_dataset(path) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_16}


```
 open_dataset(path) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_17}


```
 open_dataset(path, options) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_18}


```
 open_dataset(path, options) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_19}


```
 open_dataset(path, options) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_20}


```
 open_layer(path) 
```

Apre il layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_21}


```
 open_layer(path) 
```

Apre il layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_22}


```
 open_layer(path, options) 
```

Apre il layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_23}


```
 open_layer(path, options) 
```

Apre il layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_24}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Determina se il sistema di riferimento spaziale specificato è supportato dal driver.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Valore booleano, che indica se il sistema di riferimento spaziale specificato è supportato dal driver.<br/>            <see langword="null" /> è considerato supportato da qualsiasi driver. |


