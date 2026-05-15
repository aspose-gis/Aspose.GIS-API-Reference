---
title: "Dataset-Klasse"
type: docs
weight: 590
url: /de/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Gibt einen Wert zurück, der angibt, ob dieses Dataset Vektorlayer erstellen kann. |
| can_remove_layers | bool | r | Gibt einen Wert zurück, der angibt, ob dieses Dataset Vektorlayer entfernen kann. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Gibt den [Dataset.driver](/psd/python-net/aspose.gis/dataset/) zurück, der dieses Dataset instanziiert hat. |
| layers_count | int | r | Gibt die Anzahl der Layer in diesem Dataset zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Erstellt einen Datensatz. |
| [create(path, driver)](#create_path_driver_2) | Erstellt einen Datensatz. |
| [create(path, driver, options)](#create_path_driver_options_3) | Erstellt einen Datensatz. |
| [create(path, driver, options)](#create_path_driver_options_4) | Erstellt einen Datensatz. |
| [create_layer()](#create_layer__5) | Erstellt eine neue Vektorebene und öffnet sie zum Anhängen. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Erstellt eine neue Vektorebene mit angegebenem Namen und öffnet sie zum Anhängen. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Erstellt eine neue Vektorebene mit angegebenem Namen und öffnet sie zum Anhängen. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Erstellt eine neue Vektorebene und öffnet sie zum Anhängen. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Erstellt eine neue Vektorebene und öffnet sie zum Anhängen. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Öffnet die Ebene mit angegebenem Namen zum Bearbeiten. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Öffnet die Ebene mit angegebenem Namen zum Bearbeiten. |
| [get_layer_name(index)](#get_layer_name_index_12) | Gibt den Namen der Ebene am angegebenen Index zurück. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Prüft, ob das aktuelle Dataset eine Ebene mit einem bestimmten Namen hat |
| [open(path, driver)](#open_path_driver_14) | Öffnet den Datensatz. |
| [open(path, driver)](#open_path_driver_15) | Öffnet den Datensatz. |
| [open(path, driver, options)](#open_path_driver_options_16) | Öffnet den Datensatz. |
| [open(path, driver, options)](#open_path_driver_options_17) | Öffnet den Datensatz. |
| [open_layer(name, options)](#open_layer_name_options_18) | Öffnet die Ebene mit angegebenem Namen zum Lesen. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Öffnet die Ebene am angegebenen Index zum Lesen. |
| [remove_layer(name)](#remove_layer_name_20) | Entfernt die Vektorebene mit angegebenem Namen. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Entfernt die Vektorebene am angegebenen Index. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Ebene im Dataset umbenennen |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Erstellt eine neue Vektorebene und öffnet sie zum Anhängen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ein [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) zum Schreiben geöffnet. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Erstellt eine neue Vektorebene mit angegebenem Namen und öffnet sie zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der Ebene. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem der neuen Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ein [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) zum Schreiben geöffnet. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Erstellt eine neue Vektorebene mit angegebenem Namen und öffnet sie zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der Ebene. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem der neuen Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ein [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) zum Schreiben geöffnet. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Erstellt eine neue Vektorebene und öffnet sie zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem der neuen Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ein [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) zum Schreiben geöffnet. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Erstellt eine neue Vektorebene und öffnet sie zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem der neuen Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ein [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) zum Schreiben geöffnet. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Öffnet die Ebene mit angegebenem Namen zum Bearbeiten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der zu bearbeitenden Ebene. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem für neue Geometrien. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Die zum Bearbeiten geöffnete Ebene. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Öffnet die Ebene mit angegebenem Namen zum Bearbeiten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index der zu bearbeitenden Ebene. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem für neue Geometrien. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Die zum Bearbeiten geöffnete Ebene. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Gibt den Namen der Ebene am angegebenen Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index der Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Name der Ebene. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Prüft, ob das aktuelle Dataset eine Ebene mit einem bestimmten Namen hat

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der Ebene |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" />, wenn das Dataset eine Ebene mit diesem Namen hat; andernfalls <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Öffnet die Ebene mit angegebenem Namen zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der zu öffnenden Ebene. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Die zum Lesen geöffnete Ebene. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Öffnet die Ebene am angegebenen Index zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index der zu öffnenden Ebene. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öffnungsoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Die zum Lesen geöffnete Ebene. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Entfernt die Vektorebene mit angegebenem Namen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name der Ebene |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Entfernt die Vektorebene am angegebenen Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index der Ebene |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Ebene im Dataset umbenennen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| current_name | string | Aktueller Name der Ebene |
| new_name | string | Neuer Name für die Ebene |

