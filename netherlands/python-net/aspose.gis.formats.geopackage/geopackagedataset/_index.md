---
title: "GeoPackageDataset Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Haalt een waarde op die aangeeft of deze dataset vectorlagen kan maken. |
| can_remove_layers | bool | r | Haalt een waarde op die aangeeft of deze dataset vectorlagen kan verwijderen. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Haalt de [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) op die deze dataset heeft geïnstantiëerd. |
| layers_count | int | r | Haalt het aantal lagen in deze dataset op. |
| tile_layers_count | int | r | Haalt het aantal tegellagen in deze dataset op. |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Deze methode is nog in ontwikkeling. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Deze methode is nog in ontwikkeling. |
| [get_layer_name(index)](#get_layer_name_index_12) | Haalt de naam op van de laag op de opgegeven index. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Haalt de naam van de tegellaag op op de opgegeven index. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Controleer of de huidige dataset een laag heeft met een specifieke naam. |
| [open(path, driver)](#open_path_driver_15) | Opent de dataset. |
| [open(path, driver)](#open_path_driver_16) | Opent de dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Opent de dataset. |
| [open(path, driver, options)](#open_path_driver_options_18) | Opent de dataset. |
| [open(path, options)](#open_path_options_19) | Factory-methode voor het maken van een dataset uit een gpkg-bestand. |
| [open_layer(name, options)](#open_layer_name_options_20) | Opent de laag met opgegeven naam voor lezen. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Opent de laag op de opgegeven index voor lezen. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Opent de laag op de opgegeven index voor lezen. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Opent de tegellaag met de opgegeven naam voor lezen. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Opent de tegellaag op de opgegeven index voor lezen. |
| [remove_layer(name)](#remove_layer_name_25) | Verwijdert de vectorlaag met opgegeven naam. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Verwijdert de vectorlaag op de opgegeven index. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Hernoem de laag in de dataset |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar gpkg-bestand. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Instellingen met betrekking tot de bijzonderheden van het lezen van het gpkg-bestand. |

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

Deze methode is nog in ontwikkeling.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de te bewerken laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem voor nieuwe geometrieën. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Deze methode is nog in ontwikkeling.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de te bewerken laag. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Openopties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem voor nieuwe geometrieën. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


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


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Haalt de naam van de tegellaag op op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Naam van de laag. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


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


### Method: open(path, driver)  [static] {#open_path_driver_15}


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


### Method: open(path, driver)  [static] {#open_path_driver_16}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


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


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Factory-methode voor het maken van een dataset uit een gpkg-bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar gpkg-bestand. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Instellingen met betrekking tot de bijzonderheden van het lezen van het gpkg-bestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Opent de laag op de opgegeven index voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de te openen laag. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Openopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De laag geopend voor lezen. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Opent de tegellaag met de opgegeven naam voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de te openen laag. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Openopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | De tegellaag is geopend voor lezen. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Opent de tegellaag op de opgegeven index voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de te openen laag. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Openopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Verwijdert de vectorlaag met opgegeven naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van de laag |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Verwijdert de vectorlaag op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van de laag |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Hernoem de laag in de dataset

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| current_name | string | Huidige naam van de laag |
| new_name | string | Nieuwe naam voor de laag |

