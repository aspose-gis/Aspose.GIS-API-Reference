---
title: "Classe GeoPackageDataset"
type: docs
weight: 10
url: /it/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Ottiene un valore che indica se questo dataset può creare layer vettoriali. |
| can_remove_layers | bool | r | Ottiene un valore che indica se questo dataset può rimuovere layer vettoriali. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Ottiene il [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) che ha istanziato questo dataset. |
| layers_count | int | r | Ottiene il numero di layer in questo dataset. |
| tile_layers_count | int | r | Ottiene il numero di layer tile in questo dataset. |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Questo metodo è ancora in fase di sviluppo. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Questo metodo è ancora in fase di sviluppo. |
| [get_layer_name(index)](#get_layer_name_index_12) | Ottiene il nome del layer all'indice specificato. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Ottiene il nome del layer tile all'indice specificato. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Verifica se il dataset corrente ha un layer con nome specifico. |
| [open(path, driver)](#open_path_driver_15) | Apre il dataset. |
| [open(path, driver)](#open_path_driver_16) | Apre il dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Apre il dataset. |
| [open(path, driver, options)](#open_path_driver_options_18) | Apre il dataset. |
| [open(path, options)](#open_path_options_19) | Metodo factory per creare un dataset da un file gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Apre il layer con il nome specificato per la lettura. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Apre il layer all'indice specificato per la lettura. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Apre il layer all'indice specificato per la lettura. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Apre il layer tile con il nome specificato per la lettura. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Apre il layer tile all'indice specificato per la lettura. |
| [remove_layer(name)](#remove_layer_name_25) | Rimuove il layer vettoriale con il nome specificato. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Rimuove il layer vettoriale all'indice specificato. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Rinomina il layer nel dataset |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso al file gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Impostazioni relative alle particolarità della lettura del file gpkg. |

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

Questo metodo è ancora in fase di sviluppo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer da modificare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale per le nuove geometrie. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Questo metodo è ancora in fase di sviluppo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer da modificare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni di apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale per le nuove geometrie. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


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


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Ottiene il nome del layer tile all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Nome del layer. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


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


### Method: open(path, driver)  [static] {#open_path_driver_15}


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


### Method: open(path, driver)  [static] {#open_path_driver_16}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


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


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Metodo factory per creare un dataset da un file gpkg.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso al file gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Impostazioni relative alle particolarità della lettura del file gpkg. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Apre il layer all'indice specificato per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer da aprire. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opzioni di apertura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer aperto per la lettura. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Apre il layer tile con il nome specificato per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer da aprire. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opzioni di apertura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | Il livello tile è stato aperto per la lettura. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Apre il layer tile all'indice specificato per la lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del layer da aprire. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opzioni di apertura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Rimuove il layer vettoriale con il nome specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del layer |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Rimuove il layer vettoriale all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice del livello |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Rinomina il layer nel dataset

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| current_name | string | Nome corrente del livello |
| new_name | string | Nuovo nome per il livello |

