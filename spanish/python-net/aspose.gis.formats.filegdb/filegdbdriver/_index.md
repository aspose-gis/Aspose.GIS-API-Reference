---
title: "Clase FileGdbDriver"
type: docs
weight: 20
url: /es/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Obtiene un valor que indica si este controlador puede crear conjuntos de datos. |
| can_create_layers | bool | r | Obtiene un valor que indica si este controlador puede crear capas vectoriales. |
| can_open_datasets | bool | r | Obtiene un valor que indica si este controlador puede abrir conjuntos de datos. |
| can_open_layers | bool | r | Obtiene un valor que indica si este controlador puede abrir capas vectoriales. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Crea un conjunto de datos. |
| [create_dataset(path)](#create_dataset_path_2) | Crea un conjunto de datos. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Crea un conjunto de datos. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Crea un conjunto de datos. |
| [create_dataset(path, options)](#create_dataset_path_options_5) | Crea un conjunto de datos. |
| [create_dataset(path, options)](#create_dataset_path_options_6) | Crea un conjunto de datos. |
| [create_layer(path)](#create_layer_path_7) | Crea la capa y la abre para añadir. |
| [create_layer(path)](#create_layer_path_8) | Crea la capa y la abre para añadir. |
| [create_layer(path, options)](#create_layer_path_options_9) | Crea una capa y la abre para agregar nuevas características. |
| [create_layer(path, options)](#create_layer_path_options_10) | Crea una capa y la abre para agregar nuevas características. |
| [create_layer(path, options)](#create_layer_path_options_11) | Crea una capa y la abre para agregar nuevas características. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Crea una capa y la abre para añadir. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Crea una capa y la abre para añadir. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | Crea una capa y la abre para añadir. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | Crea una capa y la abre para añadir. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | Crea la capa y la abre para añadir. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | Crea la capa y la abre para añadir. |
| [edit_layer(path, options)](#edit_layer_path_options_18) | Abre una capa para editar. |
| [edit_layer(path, options)](#edit_layer_path_options_19) | Abre una capa para editar. |
| [open_dataset(path)](#open_dataset_path_20) | Abre el conjunto de datos. |
| [open_dataset(path)](#open_dataset_path_21) | Abre el conjunto de datos. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Abre el conjunto de datos. |
| [open_dataset(path, options)](#open_dataset_path_options_23) | Abre el conjunto de datos. |
| [open_dataset(path, options)](#open_dataset_path_options_24) | Abre el conjunto de datos. |
| [open_dataset(path, options)](#open_dataset_path_options_25) | Abre el conjunto de datos. |
| [open_layer(path)](#open_layer_path_26) | Abre la capa para lectura. |
| [open_layer(path)](#open_layer_path_27) | Abre la capa para lectura. |
| [open_layer(path, options)](#open_layer_path_options_28) | Abre una capa para lectura. |
| [open_layer(path, options)](#open_layer_path_options_29) | Abre una capa para lectura. |
| [open_layer(path, options)](#open_layer_path_options_30) | Abre una capa para lectura. |
| [open_layer(path, options)](#open_layer_path_options_31) | Abre una capa para lectura. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | Determina si el sistema de referencia espacial especificado es compatible con el controlador. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


```
 create_dataset(path, options) 
```

Crea un conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_7}


```
 create_layer(path) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_8}


```
 create_layer(path) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Crea una capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Crea una capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

Crea una capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea una capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea una capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea una capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


```
 create_layer(path, options, spatial_reference_system) 
```

Crea una capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


```
 create_layer(path, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


```
 create_layer(path, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


```
 edit_layer(path, options) 
```

Abre una capa para editar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


```
 edit_layer(path, options) 
```

Abre una capa para editar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_21}


```
 open_dataset(path) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


```
 open_dataset(path, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al conjunto de datos. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


```
 open_dataset(path, options) 
```

Abre el conjunto de datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al conjunto de datos. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Una instancia de [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_26}


```
 open_layer(path) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_27}


```
 open_layer(path) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

Abre una capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_29}


```
 open_layer(path, options) 
```

Abre una capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

Abre una capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_31}


```
 open_layer(path, options) 
```

Abre una capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Determina si el sistema de referencia espacial especificado es compatible con el controlador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Valor booleano que indica si el sistema de referencia espacial especificado es compatible con el controlador. |


