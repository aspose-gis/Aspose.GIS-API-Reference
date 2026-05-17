---
title: "Dataset-klass"
type: docs
weight: 590
url: /sv/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Hämtar ett värde som indikerar om detta dataset kan skapa vektorlager. |
| can_remove_layers | bool | r | Hämtar ett värde som indikerar om detta dataset kan ta bort vektorlager. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Hämtar [Dataset.driver](/psd/python-net/aspose.gis/dataset/) som skapade detta dataset. |
| layers_count | int | r | Hämtar antalet lager i detta dataset. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Skapar ett dataset. |
| [create(path, driver)](#create_path_driver_2) | Skapar ett dataset. |
| [create(path, driver, options)](#create_path_driver_options_3) | Skapar ett dataset. |
| [create(path, driver, options)](#create_path_driver_options_4) | Skapar ett dataset. |
| [create_layer()](#create_layer__5) | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Öppnar lagret med angivet namn för redigering. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Öppnar lagret med angivet namn för redigering. |
| [get_layer_name(index)](#get_layer_name_index_12) | Hämtar namnet på lagret vid angivet index. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Kontrollera om det aktuella datasetet har ett lager med specifikt namn |
| [open(path, driver)](#open_path_driver_14) | Öppnar datasetet. |
| [open(path, driver)](#open_path_driver_15) | Öppnar datasetet. |
| [open(path, driver, options)](#open_path_driver_options_16) | Öppnar datasetet. |
| [open(path, driver, options)](#open_path_driver_options_17) | Öppnar datasetet. |
| [open_layer(name, options)](#open_layer_name_options_18) | Öppnar lagret med angivet namn för läsning. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Öppnar lagret vid angivet index för läsning. |
| [remove_layer(name)](#remove_layer_name_20) | Tar bort vektorlager med angivet namn. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Tar bort vektorlager vid angivet index. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Byt namn på lager i datasetet |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Skapar ett dataset.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Skapar ett nytt vektorlager och öppnar det för tillägg.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öppnat för skrivning. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Lagrets namn. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för det nya lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öppnat för skrivning. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Lagrets namn. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för det nya lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öppnat för skrivning. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Skapar ett nytt vektorlager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för det nya lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öppnat för skrivning. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Skapar ett nytt vektorlager och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för det nya lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öppnat för skrivning. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Öppnar lagret med angivet namn för redigering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på lagret att redigera. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för nya geometrier. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lagret öppnat för redigering. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Öppnar lagret med angivet namn för redigering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för lagret att redigera. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spatialt referenssystem för nya geometrier. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lagret öppnat för redigering. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Hämtar namnet på lagret vid angivet index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Lagrets index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Lagrets namn. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Kontrollera om det aktuella datasetet har ett lager med specifikt namn

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Lagrets namn |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword=\"true\" />, om datasetet har ett lager med detta namn; annars, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Öppnar datasetet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till datasetet. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | En instans av [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Öppnar lagret med angivet namn för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på lagret att öppna. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lagret öppnat för läsning. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Öppnar lagret vid angivet index för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för lagret att öppna. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Öppningsalternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lagret öppnat för läsning. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Tar bort vektorlager med angivet namn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Lagrets namn |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Tar bort vektorlager vid angivet index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för lagret |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Byt namn på lager i datasetet

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| current_name | string | Aktuellt namn på lagret |
| new_name | string | Nytt namn för lagret |

