---
title: "KmlDriver Klasse"
type: docs
weight: 50
url: /nl/python-net/aspose.gis.formats.kml/kmldriver/
---

**Summary:** A driver for the KML format

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlDriver

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
| [create_layer(path)](#create_layer_path_5) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path)](#create_layer_path_6) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path, options)](#create_layer_path_options_7) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options)](#create_layer_path_options_8) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options)](#create_layer_path_options_9) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options)](#create_layer_path_options_10) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Maakt een laag aan en opent deze om nieuwe objecten toe te voegen. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Maakt de laag aan en opent deze voor toevoegen. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Maakt de laag aan en opent deze voor toevoegen. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Opent een laag voor bewerking. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Opent een laag voor bewerking. |
| [open_as_kml_layer(path, options)](#open_as_kml_layer_path_options_18) | Opent een Kml-laag voor lezen. |
| [open_dataset(path)](#open_dataset_path_19) | Opent de dataset. |
| [open_dataset(path)](#open_dataset_path_20) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Opent de dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Opent de dataset. |
| [open_layer(path)](#open_layer_path_23) | Opent de laag voor lezen. |
| [open_layer(path)](#open_layer_path_24) | Opent de laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_25) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_26) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_27) | Opent een laag voor lezen. |
| [open_layer(path, options)](#open_layer_path_options_28) | Opent een laag voor lezen. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_29) | Bepaalt of het opgegeven ruimtelijk referentiesysteem wordt ondersteund door de driver. |


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
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

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


### Method: create_layer(path) {#create_layer_path_5}


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


### Method: create_layer(path) {#create_layer_path_6}


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


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |

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
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

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
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Maakt een laag aan en opent deze om nieuwe objecten toe te voegen.

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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


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


### Method: open_as_kml_layer(path, options) {#open_as_kml_layer_path_options_18}


```
 open_as_kml_layer(path, options) 
```

Opent een Kml-laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [KmlLayer](/psd/python-net/aspose.gis.formats.kml/kmllayer) | KmlLayer met specifieke velden |


### Method: open_dataset(path) {#open_dataset_path_19}


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


### Method: open_dataset(path) {#open_dataset_path_20}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


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


### Method: open_layer(path) {#open_layer_path_23}


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


### Method: open_layer(path) {#open_layer_path_24}


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


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


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


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Opent een laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | Driver-specifieke opties. |

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
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_29}


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


