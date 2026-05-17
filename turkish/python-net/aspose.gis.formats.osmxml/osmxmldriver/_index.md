---
title: "OsmXmlDriver Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.formats.osmxml/osmxmldriver/
---

**Summary:** A driver for the OSM XML format.

**Module:** [aspose.gis.formats.osmxml](/psd/python-net/aspose.gis.formats.osmxml/)

**Full Name:** aspose.gis.formats.osmxml.OsmXmlDriver

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
| [create_layer(path)](#create_layer_path_5) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path)](#create_layer_path_6) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options)](#create_layer_path_options_7) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options)](#create_layer_path_options_8) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options)](#create_layer_path_options_9) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Bir katman oluşturur ve yeni özellikler eklemek için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Katmanı oluşturur ve ekleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Bir katmanı düzenleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Bir katmanı düzenleme için açar. |
| [open_dataset(path)](#open_dataset_path_18) | Veri kümesini açar. |
| [open_dataset(path)](#open_dataset_path_19) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Veri kümesini açar. |
| [open_layer(path)](#open_layer_path_22) | Katmanı okuma için açar. |
| [open_layer(path)](#open_layer_path_23) | Katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_24) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_25) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_26) | Bir katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_27) | Bir katmanı okuma için açar. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini belirler. |


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
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

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


### Method: create_layer(path) {#create_layer_path_5}


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


### Method: create_layer(path) {#create_layer_path_6}


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


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_8}


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


### Method: create_layer(path, options) {#create_layer_path_options_9}


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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Bir katman oluşturur ve yeni özellikler eklemek için açar.

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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


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


### Method: open_dataset(path) {#open_dataset_path_18}


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


### Method: open_dataset(path) {#open_dataset_path_19}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


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


### Method: open_layer(path) {#open_layer_path_22}


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


### Method: open_layer(path) {#open_layer_path_23}


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


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_25}


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


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Bir katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [OsmXmlOptions](/psd/python-net/aspose.gis.formats.osmxml/osmxmloptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_27}


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


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


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


