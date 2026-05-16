---
title: "Classe Dataset"
type: docs
weight: 590
url: /it/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Ottiene un valore che indica se questo dataset può creare layer vettoriali. |
| can_remove_layers | bool | r | Ottiene un valore che indica se questo dataset può rimuovere layer vettoriali. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Ottiene il [Dataset.driver](/psd/python-net/aspose.gis/dataset/) che ha istanziato questo dataset. |
| layers_count | int | r | Ottiene il numero di layer in questo dataset. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Crea un set di dati. |
| [create(path, driver)](#create_path_driver_2) | Crea un set di dati. |
| [create(path, driver, options)](#create_path_driver_options_3) | Crea un set di dati. |
| [create(path, driver, options)](#create_path_driver_options_4) | Crea un set di dati. |
| [create_layer()](#create_layer__5) | Crea un nuovo layer vettoriale e lo apre per l'aggiunta. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Crea un nuovo layer vettoriale con il nome specificato e lo apre per l'aggiunta. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Crea un nuovo layer vettoriale con il nome specificato e lo apre per l'aggiunta. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Crea un nuovo layer vettoriale e lo apre per l'aggiunta. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Crea un nuovo layer vettoriale e lo apre per l'aggiunta. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Apre il layer con il nome specificato per la modifica. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Apre il layer con il nome specificato per la modifica. |
| [get_layer_name(index)](#get_layer_name_index_12) | Ottiene il nome del layer all'indice specificato. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Verifica se il dataset corrente ha un layer con nome specifico. |
| [open(path, driver)](#open_path_driver_14) | Apre il dataset. |
| [open(path, driver)](#open_path_driver_15) | Apre il dataset. |
| [open(path, driver, options)](#open_path_driver_options_16) | Apre il dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Apre il dataset. |
| [open_layer(name, options)](#open_layer_name_options_18) | Apre il layer con il nome specificato per la lettura. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Apre il layer all'indice specificato per la lettura. |
| [remove_layer(name)](#remove_layer_name_20) | Rimuove il layer vettoriale con il nome specificato. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Rimuove il layer vettoriale all'indice specificato. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Rinomina il layer nel dataset |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Crea un set di dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Crea un nuovo layer vettoriale e lo apre per l'aggiunta.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) aperto per scrittura. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Crea un nuovo layer vettoriale con il nome specificato e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale del nuovo layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) aperto per scrittura. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Crea un nuovo layer vettoriale con il nome specificato e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale del nuovo layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) aperto per scrittura. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Crea un nuovo layer vettoriale e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale del nuovo layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) aperto per scrittura. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Crea un nuovo layer vettoriale e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale del nuovo layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) aperto per scrittura. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Apre il layer con il nome specificato per la modifica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer da modificare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale per le nuove geometrie. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer aperto per la modifica. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Apre il layer con il nome specificato per la modifica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer da modificare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale per le nuove geometrie. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer aperto per la modifica. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Ottiene il nome del layer all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Nome del layer. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Verifica se il dataset corrente ha un layer con nome specifico.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" />, se il dataset ha un layer con questo nome; altrimenti, <see langword="false" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Apre il dataset.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Un'istanza di [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Apre il layer con il nome specificato per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer da aprire. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer aperto per la lettura. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Apre il layer all'indice specificato per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer da aprire. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer aperto per la lettura. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Rimuove il layer vettoriale con il nome specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Rimuove il layer vettoriale all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del livello |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Rinomina il layer nel dataset

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| current_name | string | Nome corrente del livello |
| new_name | string | Nuovo nome per il livello |

