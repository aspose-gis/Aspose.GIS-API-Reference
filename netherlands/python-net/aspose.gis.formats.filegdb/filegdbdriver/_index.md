---
title: "FileGdbDriver Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Geeft een waarde terug die aangeeft of deze driver datasets kan maken. |
| can_create_layers | bool | r | Geeft een waarde terug die aangeeft of deze driver vectorlagen kan maken. |
| can_open_datasets | bool | r | Geeft een waarde terug die aangeeft of deze driver datasets kan openen. |
| can_open_layers | bool | r | Geeft een waarde terug die aangeeft of deze driver vectorlagen kan openen. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Maakt een dataset aan. |
| [create_dataset(path)](#create_dataset_path_2) | Maakt een dataset aan. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Maakt een dataset aan. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Maakt een dataset aan. |
| [create_dataset(path, options)](#create_dataset_path_options_5) | Maakt een dataset aan. |
| [create_dataset(path, options)](#create_dataset_path_options_6) | Maakt een dataset aan. |
| [create_layer(path)](#create_layer_path_7) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path)](#create_layer_path_8) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path, options)](#create_layer_path_options_9) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options)](#create_layer_path_options_10) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options)](#create_layer_path_options_11) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Maakt een laag aan en opent deze voor toevoegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Maakt een laag aan en opent deze voor toevoegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | Maakt een laag aan en opent deze voor toevoegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | Maakt een laag aan en opent deze voor toevoegen. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | Maakt de laag aan en opent deze voor toevoegen. |
| [edit_layer(path, options)](#edit_layer_path_options_18) | Opent een laag voor bewerking. |
| [edit_layer(path, options)](#edit_layer_path_options_19) | Opent een laag voor bewerking. |
| [open_dataset(path)](#open_dataset_path_20) | Opent de dataset. |
| [open_dataset(path)](#open_dataset_path_21) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_23) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_24) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_25) | Opent de dataset. |
| [open_layer(path)](#open_layer_path_26) | Opent de laag voor lezen. |
| [open_layer(path)](#open_layer_path_27) | Opent de laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_28) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_29) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_30) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_31) | Opent een laag voor lezen. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | Bepaalt of het opgegeven ruimtelijk referentiesysteem wordt ondersteund door de driver. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


```
 create_dataset(path, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_7}


```
 create_layer(path) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_8}


```
 create_layer(path) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


```
 create_layer(path, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


```
 create_layer(path, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


```
 edit_layer(path, options) 
```

Opent een laag voor bewerking.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


```
 edit_layer(path, options) 
```

Opent een laag voor bewerking.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_21}


```
 open_dataset(path) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


```
 open_dataset(path, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


```
 open_dataset(path, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_26}


```
 open_layer(path) 
```

Opent de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_27}


```
 open_layer(path) 
```

Opent de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_29}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_31}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Bepaalt of het opgegeven ruimtelijk referentiesysteem wordt ondersteund door de driver.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Booleaanse waarde die aangeeft of het opgegeven ruimtelijk referentiesysteem wordt ondersteund door de driver. |


