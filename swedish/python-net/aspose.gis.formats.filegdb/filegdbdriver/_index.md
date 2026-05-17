---
title: "FileGdbDriver klass"
type: docs
weight: 20
url: /sv/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Hämtar ett värde som indikerar om den här drivrutinen kan skapa dataset. |
| can_create_layers | bool | r | Hämtar ett värde som indikerar om den här drivrutinen kan skapa vektorlager. |
| can_open_datasets | bool | r | Hämtar ett värde som indikerar om den här drivrutinen kan öppna dataset. |
| can_open_layers | bool | r | Hämtar ett värde som indikerar om den här drivrutinen kan öppna vektorlager. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Skapar ett dataset. |
| [create_dataset(path)](#create_dataset_path_2) | Skapar ett dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Skapar ett dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Skapar ett dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_5) | Skapar ett dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_6) | Skapar ett dataset. |
| [create_layer(path)](#create_layer_path_7) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path)](#create_layer_path_8) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, options)](#create_layer_path_options_9) | Skapar ett lager och öppnar det för att lägga till nya funktioner. |
| [create_layer(path, options)](#create_layer_path_options_10) | Skapar ett lager och öppnar det för att lägga till nya funktioner. |
| [create_layer(path, options)](#create_layer_path_options_11) | Skapar ett lager och öppnar det för att lägga till nya funktioner. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Skapar ett lager och öppnar det för tillägg. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Skapar ett lager och öppnar det för tillägg. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | Skapar ett lager och öppnar det för tillägg. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | Skapar ett lager och öppnar det för tillägg. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | Skapar lagret och öppnar det för tillägg. |
| [edit_layer(path, options)](#edit_layer_path_options_18) | Öppnar ett lager för redigering. |
| [edit_layer(path, options)](#edit_layer_path_options_19) | Öppnar ett lager för redigering. |
| [open_dataset(path)](#open_dataset_path_20) | Öppnar datasetet. |
| [open_dataset(path)](#open_dataset_path_21) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_23) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_24) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_25) | Öppnar datasetet. |
| [open_layer(path)](#open_layer_path_26) | Öppnar lagret för läsning. |
| [open_layer(path)](#open_layer_path_27) | Öppnar lagret för läsning. |
| [open_layer(path, options)](#open_layer_path_options_28) | Öppnar ett lager för läsning. |
| [open_layer(path, options)](#open_layer_path_options_29) | Öppnar ett lager för läsning. |
| [open_layer(path, options)](#open_layer_path_options_30) | Öppnar ett lager för läsning. |
| [open_layer(path, options)](#open_layer_path_options_31) | Öppnar ett lager för läsning. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | Avgör, om det angivna rumsliga referenssystemet stöds av drivrutinen. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


```
 create_dataset(path, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_7}


```
 create_layer(path) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_8}


```
 create_layer(path) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Skapar ett lager och öppnar det för att lägga till nya funktioner.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Skapar ett lager och öppnar det för att lägga till nya funktioner.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

Skapar ett lager och öppnar det för att lägga till nya funktioner.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


```
 create_layer(path, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


```
 create_layer(path, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


```
 edit_layer(path, options) 
```

Öppnar ett lager för redigering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


```
 edit_layer(path, options) 
```

Öppnar ett lager för redigering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_21}


```
 open_dataset(path) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


```
 open_dataset(path, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


```
 open_dataset(path, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_26}


```
 open_layer(path) 
```

Öppnar lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_27}


```
 open_layer(path) 
```

Öppnar lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

Öppnar ett lager för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_29}


```
 open_layer(path, options) 
```

Öppnar ett lager för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

Öppnar ett lager för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_31}


```
 open_layer(path, options) 
```

Öppnar ett lager för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Avgör, om det angivna rumsliga referenssystemet stöds av drivrutinen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Booleskt värde som indikerar om det angivna rumsliga referenssystemet stöds av drivrutinen. |


