---
title: "ShapefileDriver Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.formats.shapefile/shapefiledriver/
---

**Summary:** A driver for the Shapefile format.

**Module:** [aspose.gis.formats.shapefile](/psd/python-net/aspose.gis.formats.shapefile/)

**Full Name:** aspose.gis.formats.shapefile.ShapefileDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Treiber Datensätze erstellen kann. |
| can_create_layers | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Treiber Vektorlayer erstellen kann. |
| can_open_datasets | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Treiber Datensätze öffnen kann. |
| can_open_layers | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Treiber Vektorlayer öffnen kann. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Erstellt einen Datensatz. |
| [create_dataset(path)](#create_dataset_path_2) | Erstellt einen Datensatz. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Erstellt einen Datensatz. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Erstellt einen Datensatz. |
| [create_layer(path)](#create_layer_path_5) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create_layer(path)](#create_layer_path_6) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create_layer(path, options)](#create_layer_path_options_7) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options)](#create_layer_path_options_8) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options)](#create_layer_path_options_9) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options)](#create_layer_path_options_10) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Erstellt das Layer und öffnet es zum Anhängen. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Öffnet eine Ebene zum Bearbeiten. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Öffnet eine Ebene zum Bearbeiten. |
| [open_dataset(path)](#open_dataset_path_18) | Öffnet den Datensatz. |
| [open_dataset(path)](#open_dataset_path_19) | Öffnet den Datensatz. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Öffnet den Datensatz. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Öffnet den Datensatz. |
| [open_layer(path)](#open_layer_path_22) | Öffnet die Ebene zum Lesen. |
| [open_layer(path)](#open_layer_path_23) | Öffnet die Ebene zum Lesen. |
| [open_layer(path, options)](#open_layer_path_options_24) | Öffnet eine Ebene zum Lesen. |
| [open_layer(path, options)](#open_layer_path_options_25) | Öffnet eine Ebene zum Lesen. |
| [open_layer(path, options)](#open_layer_path_options_26) | Öffnet eine Ebene zum Lesen. |
| [open_layer(path, options)](#open_layer_path_options_27) | Öffnet eine Ebene zum Lesen. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Bestimmt, ob das angegebene räumliche Referenzsystem vom Treiber unterstützt wird. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Erstellt einen Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [ShapefileOptions](/psd/python-net/aspose.gis.formats.shapefile/shapefileoptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [ShapefileOptions](/psd/python-net/aspose.gis.formats.shapefile/shapefileoptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [ShapefileOptions](/psd/python-net/aspose.gis.formats.shapefile/shapefileoptions) | Treiber-spezifische Optionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Erstellt eine Ebene und öffnet sie zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

Öffnet eine Ebene zum Bearbeiten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

Öffnet eine Ebene zum Bearbeiten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zum Datensatz. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

Öffnet den Datensatz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zum Datensatz. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Eine Instanz von [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_22}


```
 open_layer(path) 
```

Öffnet die Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

Öffnet die Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Öffnet eine Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [ShapefileOptions](/psd/python-net/aspose.gis.formats.shapefile/shapefileoptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Öffnet eine Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Öffnet eine Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| options | [ShapefileOptions](/psd/python-net/aspose.gis.formats.shapefile/shapefileoptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Öffnet eine Ebene zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Bestimmt, ob das angegebene räumliche Referenzsystem vom Treiber unterstützt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Boolescher Wert, der angibt, ob das angegebene räumliche Referenzsystem vom Treiber unterstützt wird. |


