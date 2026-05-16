---
title: "Datasetklasse"
type: docs
weight: 590
url: /nl/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Haalt een waarde op die aangeeft of deze dataset vectorlagen kan maken. |
| can_remove_layers | bool | r | Haalt een waarde op die aangeeft of deze dataset vectorlagen kan verwijderen. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Haalt de [Dataset.driver](/psd/python-net/aspose.gis/dataset/) op die deze dataset heeft geïnstantiëerd. |
| layers_count | int | r | Haalt het aantal lagen in deze dataset op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Maakt een dataset aan. |
| [create(path, driver)](#create_path_driver_2) | Maakt een dataset aan. |
| [create(path, driver, options)](#create_path_driver_options_3) | Maakt een dataset aan. |
| [create(path, driver, options)](#create_path_driver_options_4) | Maakt een dataset aan. |
| [create_layer()](#create_layer__5) | Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Maakt een nieuwe vectorlaag met opgegeven naam aan en opent deze voor toevoegen. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Maakt een nieuwe vectorlaag met opgegeven naam aan en opent deze voor toevoegen. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Opent de laag met opgegeven naam voor bewerken. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Opent de laag met opgegeven naam voor bewerken. |
| [get_layer_name(index)](#get_layer_name_index_12) | Haalt de naam op van de laag op de opgegeven index. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Controleer of de huidige dataset een laag heeft met een specifieke naam. |
| [open(path, driver)](#open_path_driver_14) | Opent de dataset. |
| [open(path, driver)](#open_path_driver_15) | Opent de dataset. |
| [open(path, driver, options)](#open_path_driver_options_16) | Opent de dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Opent de dataset. |
| [open_layer(name, options)](#open_layer_name_options_18) | Opent de laag met opgegeven naam voor lezen. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Opent de laag op de opgegeven index voor lezen. |
| [remove_layer(name)](#remove_layer_name_20) | Verwijdert de vectorlaag met opgegeven naam. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Verwijdert de vectorlaag op de opgegeven index. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Hernoem de laag in de dataset |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Maakt een dataset aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) geopend voor schrijven. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Maakt een nieuwe vectorlaag met opgegeven naam aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem van de nieuwe laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) geopend voor schrijven. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Maakt een nieuwe vectorlaag met opgegeven naam aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de laag. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem van de nieuwe laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) geopend voor schrijven. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem van de nieuwe laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) geopend voor schrijven. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Maakt een nieuwe vectorlaag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem van de nieuwe laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) geopend voor schrijven. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Opent de laag met opgegeven naam voor bewerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de te bewerken laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem voor nieuwe geometrieën. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De laag geopend voor bewerken. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Opent de laag met opgegeven naam voor bewerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de te bewerken laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem voor nieuwe geometrieën. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De laag geopend voor bewerken. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Haalt de naam op van de laag op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Naam van de laag. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Controleer of de huidige dataset een laag heeft met een specifieke naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de laag |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" />, als de dataset een laag heeft met deze naam; anders, <see langword="false" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Opent de dataset.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Een exemplaar van [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Opent de laag met opgegeven naam voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de te openen laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De laag geopend voor lezen. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Opent de laag op de opgegeven index voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de te openen laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De laag geopend voor lezen. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Verwijdert de vectorlaag met opgegeven naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de laag |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Verwijdert de vectorlaag op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de laag |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Hernoem de laag in de dataset

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| current_name | string | Huidige naam van de laag |
| new_name | string | Nieuwe naam voor de laag |

