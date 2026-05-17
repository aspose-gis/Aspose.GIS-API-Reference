---
title: "FileGdbDriver Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Bu sürücünün veri kümeleri oluşturup oluşturamayacağını gösteren bir değer alır. |
| can_create_layers | bool | r | Bu sürücünün vektör katmanları oluşturup oluşturamayacağını gösteren bir değer alır. |
| can_open_datasets | bool | r | Bu sürücünün veri kümelerini açıp açamayacağını gösteren bir değer alır. |
| can_open_layers | bool | r | Bu sürücünün vektör katmanlarını açıp açamayacağını gösteren bir değer alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Bir veri kümesi oluşturur. |
| [create_dataset(path)](#create_dataset_path_2) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_5) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_6) | Bir veri kümesi oluşturur. |
| [create_layer(path)](#create_layer_path_7) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path)](#create_layer_path_8) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options)](#create_layer_path_options_9) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options)](#create_layer_path_options_10) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options)](#create_layer_path_options_11) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Bir katman oluşturur ve ekleme için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Bir katman oluşturur ve ekleme için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | Bir katman oluşturur ve ekleme için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | Bir katman oluşturur ve ekleme için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | Katmanı oluşturur ve ekleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_18) | Bir katmanı düzenleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_19) | Bir katmanı düzenleme için açar. |
| [open_dataset(path)](#open_dataset_path_20) | Veri kümesini açar. |
| [open_dataset(path)](#open_dataset_path_21) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_23) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_24) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_25) | Veri kümesini açar. |
| [open_layer(path)](#open_layer_path_26) | Katmanı okuma için açar. |
| [open_layer(path)](#open_layer_path_27) | Katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_28) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_29) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_30) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_31) | Bir katmanı okuma için açar. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini belirler. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_layer(path) {#create_layer_path_7}


```
 create_layer(path) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path) {#create_layer_path_8}


```
 create_layer(path) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


```
 create_layer(path, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


```
 create_layer(path, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


```
 edit_layer(path, options) 
```

Bir katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


```
 edit_layer(path, options) 
```

Bir katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path) {#open_dataset_path_21}


```
 open_dataset(path) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_layer(path) {#open_layer_path_26}


```
 open_layer(path) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path) {#open_layer_path_27}


```
 open_layer(path) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_29}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_31}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini gösteren Boolean değer. |


