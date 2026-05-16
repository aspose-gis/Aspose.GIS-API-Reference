---
title: "Classe GeoJsonDriver"
type: docs
weight: 10
url: /it/python-net/aspose.gis.formats.geojson/geojsondriver/
---

**Summary:** A driver for the GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

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
| [create_layer(path, options)](#create_layer_path_options_7) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options)](#create_layer_path_options_8) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options)](#create_layer_path_options_9) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options)](#create_layer_path_options_10) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Crea un layer e lo apre per aggiungere nuove feature. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Crea il livello e lo apre per l'aggiunta. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Crea il livello e lo apre per l'aggiunta. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Apre un layer per la modifica. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Apre un layer per la modifica. |
| [open_dataset(path)](#open_dataset_path_18) | Apre il dataset. |
| [open_dataset(path)](#open_dataset_path_19) | Apre il dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Apre il dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Apre il dataset. |
| [open_layer(path)](#open_layer_path_22) | Apre il layer per la lettura. |
| [open_layer(path)](#open_layer_path_23) | Apre il layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_24) | Apre un layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_25) | Apre un layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_26) | Apre un layer per la lettura. |
| [open_layer(path, options)](#open_layer_path_options_27) | Apre un layer per la lettura. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Determina se il sistema di riferimento spaziale specificato è supportato dal driver. |


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

Crea un layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [GeoJsonOptions](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Crea un layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [GeoJsonOptions](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Crea un layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Crea un layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea un layer e lo apre per aggiungere nuove feature.

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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea un layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [GeoJsonOptions](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions) | Opzioni specifiche del driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea un layer e lo apre per aggiungere nuove feature.

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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


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


### Method: open_dataset(path) {#open_dataset_path_18}


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


### Method: open_dataset(path) {#open_dataset_path_19}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


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


### Method: open_layer(path) {#open_layer_path_22}


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


### Method: open_layer(path) {#open_layer_path_23}


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


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Apre un layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [GeoJsonOptions](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Apre un layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Apre un layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| options | [GeoJsonOptions](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Apre un layer per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


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
| bool | Valore booleano che indica se il sistema di riferimento spaziale specificato è supportato dal driver. |


