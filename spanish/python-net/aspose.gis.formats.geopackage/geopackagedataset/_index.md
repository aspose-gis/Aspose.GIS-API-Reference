---
title: "Clase GeoPackageDataset"
type: docs
weight: 10
url: /es/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Obtiene un valor que indica si este conjunto de datos puede crear capas vectoriales. |
| can_remove_layers | bool | r | Obtiene un valor que indica si este conjunto de datos puede eliminar capas vectoriales. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtiene el [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) que instanció este conjunto de datos. |
| layers_count | int | r | Obtiene el número de capas en este conjunto de datos. |
| tile_layers_count | int | r | Obtiene el número de capas de mosaico en este conjunto de datos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Crea un conjunto de datos. |
| [create(path, driver)](#create_path_driver_2) | Crea un conjunto de datos. |
| [create(path, driver, options)](#create_path_driver_options_3) | Crea un conjunto de datos. |
| [create(path, driver, options)](#create_path_driver_options_4) | Crea un conjunto de datos. |
| [create_layer()](#create_layer__5) | Crea una nueva capa vectorial y la abre para añadir. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Crea una nueva capa vectorial con el nombre especificado y la abre para añadir. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Crea una nueva capa vectorial con el nombre especificado y la abre para añadir. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Crea una nueva capa vectorial y la abre para añadir. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Crea una nueva capa vectorial y la abre para añadir. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Este método aún está en desarrollo. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Este método aún está en desarrollo. |
| [get_layer_name(index)](#get_layer_name_index_12) | Obtiene el nombre de la capa en el índice especificado. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Obtiene el nombre de la capa de mosaico en el índice especificado. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Comprueba si el conjunto de datos actual tiene una capa con un nombre específico |
| [open(path, driver)](#open_path_driver_15) | Abre el conjunto de datos. |
| [open(path, driver)](#open_path_driver_16) | Abre el conjunto de datos. |
| [open(path, driver, options)](#open_path_driver_options_17) | Abre el conjunto de datos. |
| [open(path, driver, options)](#open_path_driver_options_18) | Abre el conjunto de datos. |
| [open(path, options)](#open_path_options_19) | Método de fábrica para crear un conjunto de datos a partir de un archivo gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Abre la capa con el nombre especificado para lectura. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Abre la capa en el índice especificado para lectura. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Abre la capa en el índice especificado para lectura. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Abre la capa de mosaico con el nombre especificado para lectura. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Abre la capa de mosaico en el índice especificado para lectura. |
| [remove_layer(name)](#remove_layer_name_25) | Elimina la capa vectorial con el nombre especificado. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Elimina la capa vectorial en el índice especificado. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Renombrar capa en el conjunto de datos |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Configuraciones relacionadas con las particularidades de la lectura del archivo gpkg. |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Crea una nueva capa vectorial y la abre para añadir.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) abierta para escritura. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Crea una nueva capa vectorial con el nombre especificado y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial de la nueva capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) abierta para escritura. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Crea una nueva capa vectorial con el nombre especificado y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial de la nueva capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) abierta para escritura. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Crea una nueva capa vectorial y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial de la nueva capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) abierta para escritura. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Crea una nueva capa vectorial y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial de la nueva capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) abierta para escritura. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Este método aún está en desarrollo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa a editar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial para nuevas geometrías. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Este método aún está en desarrollo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa a editar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial para nuevas geometrías. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Obtiene el nombre de la capa en el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Nombre de la capa. |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Obtiene el nombre de la capa de mosaico en el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Nombre de la capa. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

Comprueba si el conjunto de datos actual tiene una capa con un nombre específico

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" />, si el conjunto de datos tiene una capa con este nombre; de lo contrario, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Método de fábrica para crear un conjunto de datos a partir de un archivo gpkg.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Configuraciones relacionadas con las particularidades de la lectura del archivo gpkg. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

Abre la capa con el nombre especificado para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa a abrir. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La capa abierta para lectura. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

Abre la capa en el índice especificado para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa a abrir. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones de apertura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La capa abierta para lectura. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Abre la capa en el índice especificado para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa a abrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opciones de apertura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La capa abierta para lectura. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Abre la capa de mosaico con el nombre especificado para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa a abrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opciones de apertura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | La capa de mosaico se abrió para lectura. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Abre la capa de mosaico en el índice especificado para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa a abrir. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opciones de apertura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Elimina la capa vectorial con el nombre especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de la capa |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Elimina la capa vectorial en el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice de la capa |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Renombrar capa en el conjunto de datos

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| current_name | string | Nombre actual de la capa |
| new_name | string | Nuevo nombre para la capa |

