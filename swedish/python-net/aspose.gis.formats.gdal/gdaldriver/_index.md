---
title: "GdalDriver-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.formats.gdal/gdaldriver/
---

**Summary:** A driver for the GDAL format.

**Module:** [aspose.gis.formats.gdal](/psd/python-net/aspose.gis.formats.gdal/)

**Full Name:** aspose.gis.formats.gdal.GdalDriver

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
| [create_layer(path)](#create_layer_path_5) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path)](#create_layer_path_6) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, options)](#create_layer_path_options_7) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, options)](#create_layer_path_options_8) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_9) | Skapar ett lager och öppnar det för att lägga till nya funktioner. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | Skapar ett lager och öppnar det för att lägga till nya funktioner. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_11) | Skapar lagret och öppnar det för tillägg. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_12) | Skapar lagret och öppnar det för tillägg. |
| [edit_layer(path, options)](#edit_layer_path_options_13) | Öppnar ett lager för redigering. |
| [edit_layer(path, options)](#edit_layer_path_options_14) | Öppnar ett lager för redigering. |
| [open_dataset(path)](#open_dataset_path_15) | Öppnar datasetet. |
| [open_dataset(path)](#open_dataset_path_16) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_17) | Öppnar datasetet. |
| [open_dataset(path, options)](#open_dataset_path_options_18) | Öppnar datasetet. |
| [open_layer(path)](#open_layer_path_19) | Öppnar lagret för läsning. |
| [open_layer(path)](#open_layer_path_20) | Öppnar lagret för läsning. |
| [open_layer(path, options)](#open_layer_path_options_21) | Öppnar ett lager för läsning. |
| [open_layer(path, options)](#open_layer_path_options_22) | Öppnar ett lager för läsning. |
| [open_layer(path, options)](#open_layer_path_options_23) | Öppnar ett lager för läsning. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_24) | Avgör, om det angivna rumsliga referenssystemet stöds av drivrutinen. |


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
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

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


### Method: create_layer(path) {#create_layer_path_5}


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


### Method: create_layer(path) {#create_layer_path_6}


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


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_9}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för att lägga till nya funktioner.

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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

Skapar ett lager och öppnar det för att lägga till nya funktioner.

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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_11}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_12}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_13}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_14}


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


### Method: open_dataset(path) {#open_dataset_path_15}


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


### Method: open_dataset(path) {#open_dataset_path_16}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_17}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_18}


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


### Method: open_layer(path) {#open_layer_path_19}


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


### Method: open_layer(path) {#open_layer_path_20}


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


### Method: open_layer(path, options) {#open_layer_path_options_21}


```
 open_layer(path, options) 
```

Öppnar ett lager för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| options | [GdalOptions](/psd/python-net/aspose.gis.formats.gdal/gdaloptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_22}


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


### Method: open_layer(path, options) {#open_layer_path_options_23}


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


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_24}


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


